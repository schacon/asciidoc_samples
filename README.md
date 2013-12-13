# asciidoc_samples

This directory contains samples of Asciidoc source files, for use with our internal publishing tools.

----
NOTE: If you update any boilerplate in this repo, please update the DocBook version as well:

https://github.com/oreillymedia/docbook_samples

----

Please note that if you view the file contents in the GitHub UI, you'll need to click on the "Raw" link to see the raw unformatted Asciidoc markup.

Files are organized as follows:

## Boilerplate/skeleton files for common book components

* Standard files:
  * book.asciidoc (model for book with includes)
  * preface/animal/preface.asciidoc (model for Animal preface; for other series, use preface/all_other_series/preface.asciidoc)
  * ch01.asciidoc (model for chapters)
* Optional (copy any of these you need for your book):
  * dedication.asciidoc (model for book with a dedication)
  * forword.asciidoc (model for book with a foreword)
  * afterword.asciidoc  (model for book with an afterword)
  * appendix.asciidoc  (model for book with an appendix)
  * part1.asciidoc  (model for book organized in Parts)
* Extras (generally for internal use, during later production stages): 
  * colophon/<series>/colo.asciidoc (colophon)
  * book-docinfo.xml (contains ISBN and author information)

## Further info

Please see the Atlas Authoring Guidelines for further information:

http://chimera.labs.oreilly.com/books/1230000000065
