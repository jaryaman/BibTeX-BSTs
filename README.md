# BibTeX-BSTs

A set of `.bst` files intended to resemble the bibliography style of common academic journals for use with the LaTeX bibliography managing system BibTeX. `makefiles` are also included to create your own `.bst` files.

## BSTs

Some example `.bst` files can be found in the `./BSTs` subdirectory. Where the corresponding `.dbj` file is available, the `.bst` appears as a subdirectory of `./BSTs`. The style files available here are:

- `author_year_whole_title_all_authors.bst`: To have the citation style displaying [authorYear] in text and show all authors in the bibliography
- `BiochemJ.bst`: To resemble the citation style of *Biochemical Journal*
- `Bioessays.bst`: To resemble the citation style of *Bioessays*
- `AJHG.bst`: To resemble the citation style of *American Journal of Human Genetics*
- `cell.bst`: To resemble the citation style of *Cell*
- `nature.bst`: To resemble the citation style of *Nature*
- `one_author_no_title.bst`: To show a single author in the bibliography, with no title. This loosely resembles Physical Review Letters

## How to make your own BibTeX style files

To make your own `.bst` files, run

```bash
latex makebst
```

and answer the questions after being prompted. Alternatively, comment/ uncomment the appropriate lines in `imsi.dbj` in the subdirectory `./makefiles` then run

```bash
latex imsi.dbj
```
