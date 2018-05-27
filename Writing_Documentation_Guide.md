# AWG Writing Documentation

Good projects have good documentation. All our documentation is saved in [Markdown](https://en.wikipedia.org/wiki/Markdown), so it looks good in the repository, can be read as plain text and be easily transformed into printed matter.

Tables are a little awkward in plain text. But life get's a lot easier with some apropiate tools. Below some favourites. (There are many, many more)

## Dedicated tools

  * [MacDown](https://macdown.uranusjr.com)
  * [Quiver](http://happenapps.com/#quiver)
  * [TableFlip](http://tableflipapp.com)
  * [Typora](https://typora.io)

## Plugins for code editors

Patch your code editor with a [Markdown Table Formatter](https://github.com/alanwsmith/markdown_table_formatter)

  * [Atom](https://atom.io/packages/markdown-table-formatter-z)
  * [Sublime Text](https://packagecontrol.io/packages/Markdown%20Table%20Formatter)

Or use the Markdown table scripts for [BBEdit](http://www.leancrew.com/all-this/2012/11/markdown-table-scripts-for-bbedit/) or [TextMate](http://www.leancrew.com/all-this/2012/03/improved-markdown-table-commands-for-textmate/)

# What about complex spreadsheets?

We love them! Please save them in an open format. We prefer the [Open Document Format](https://en.wikipedia.org/wiki/OpenDocument) (`.ods`) But `.xslx` is acceptable. When we commit these files to the repository, make sure there is a flat Markdown/CSV version saved next to it.

    mySpreadSheet.xslx
    mySpreadSheet.md

We hope to automate this step completly in the future.

## Sheet/CSV Coversion tools

  * [csv2md](https://github.com/jonmagic/csv2md)
  * [atom-csv-markdown package](https://github.com/takezoe/atom-csv-markdown)
  * [sheetdown](https://github.com/jlord/sheetdown)
  * [table-magic](https://github.com/stevecat/table-magic)

