# Visium Data Preprocessing

[![R build status](https://github.com/lmweber/Visium-data-preprocessing/workflows/R-CMD-bioc/badge.svg)](https://github.com/lmweber/Visium-data-preprocessing/actions)

Repository containing source files for 'Visium Data Preprocessing' online book.


## Website

The website for the compiled version of the book is at: https://lmweber.org/Visium-data-preprocessing/


## Source files

The main content of the book is in the RMarkdown `.Rmd` files in the [chapters/](chapters/) subdirectory, with one `.Rmd` file per chapter.

Compiling and deployment to the website uses the GitHub Actions workflow in: [.github/workflows/](.github/workflows/)


## Compile locally

To compile the book locally, run `bookdown::render_book()` in the root directory.

