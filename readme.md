BibTeX Bibliography njhigham.bib
===========

A BibTeX bibliography for papers, books, EPrints, articles, etc. of
Nicholas J. Higham.

Contents
---------

* `njhigham.bib`:    Main bibliography file.
Contains nonstandard fields
`doi`, `bibdate` (which I no longer use), `created` and `updated`.

* `strings.bib`: String definitions use by `njhigham.bib`.

* `njhigham_nostrings.bib`:   Main bibliography file with no strings
(does not require strings.bib). Converted automatically using
bibexport script.

* `njhigham_bibbase.bib`: Modified version of `njhigham_nostrings.bib` with
minor changes to work optimally with BibBase for generating web page.  Not
intended for other uses.

* `njhigham.tex`:  LaTeX file that creates a document with a bibliography
containing all the entries in `njhigham.bib`.

* `njhigham.pdf`:  The result of running pdfLaTeX on `njhigham.tex`.

* `myplain2-doi.bst`: BST file needed by `njhigham.tex`.  My modified
version of `is-plain.bst` that handles DOIs.
