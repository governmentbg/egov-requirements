Генериране на .docx файл от README.md, използвайки <a href="http://pandoc.org/">Pandoc</a>:

    pandoc -s -i README.md -f markdown+compact_definition_lists -o EgovRequirements-Draft.docx