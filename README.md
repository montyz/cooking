A place to keep my own recipes in markdown so I can format them and put them on my nook.

Instructions for pandoc at http://johnmacfarlane.net/pandoc/epub.html

    pandoc -f markdown_phpextra  -o r.epub *.md

Markdown syntax at http://daringfireball.net/projects/markdown/syntax

To-do:
- build.sh file
- how to do one recipe per page
- styling to remove bullets from lists
- proper symbols for 1/2, etc.
- standardization on units & measures
- proper index? -- may have to generate it using [Header identifiers](http://johnmacfarlane.net/pandoc/README.html#header-identifiers-in-html-latex-and-context)
- do it in lyx instead?
- may want to use http://www.nltk.org/ to do natural language parsing to recognize ingredient lists and properly format them