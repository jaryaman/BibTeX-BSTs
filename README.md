# BibTeX-BSTs

A set of `.bst` files intended to resemble the bibliography style of common academic journals for use with the LaTeX bibliography managing system BibTeX.

## Usage

To make your own `.bst` files, comment/ uncomment the appropriate lines in `imsi.dbj`then run 

```bash
latex imsi.dbj
```
## Examples

Some example `.bst` files can be found in the `BSTs` subdirectory. These are:

- author_year_whole_title_all_authors.bst: To have the citation style displaying [authorYear] in text and show all authors in the bibliography
- BiochemJ.bst: To resemble the citation style of *Biochemical Journal* 
- Bioessays.bst: To resemble the citation style of *Bioessays*
- one_author_no_title.bst: To show a single author in the bibliography, with no title. This is similar (but not identical) to Physical Review Letters



