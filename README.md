# CV

This directory contains the raw files needed to construct my CV. The `render.R` file, calls the rmarkdown::render function to create the PDF version of the `cv.RMD` file. These files are necessary because I like the `vitae` package pdf format. The same formatting could likely be achieved using Quarto, but it currently seems difficult to do so.

## Important Files

- publication.bib
  - This file contains the bibtex formating for all the publications or citable stuff in my CV (not a lot).
- vita.Rmd
  - This file contains the main text for my CV. It relies heavily on the vitae package.
