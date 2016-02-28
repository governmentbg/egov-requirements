Генериране на .docx файлове от Markdown файлове, използвайки <a href="http://pandoc.org/">Pandoc</a>:

    pandoc -s -i README.md -f markdown+compact_definition_lists -o EgovRequirements-Draft.docx
	pandoc -s -i integration.md -f markdown+compact_definition_lists -o IntegrationRequirements-Draft.docx
	pandoc -s -i quality.md -f markdown+compact_definition_lists -o QualityRequirements-Draft.docx
	
Заб: Вътрешните хипервръзки в генерираните файлове не функционират