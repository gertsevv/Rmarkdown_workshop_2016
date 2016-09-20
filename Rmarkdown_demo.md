R Markdown Examples
========================================================
author: Melissa Monk
date: October 2016
autosize: true

R Markdown
========================================================

In this section we're going to learn the R Markdown basics

- R Markdown renders easiest to a HTML, but we're interested
   in creating a PDF
- The assessment template is designed to only render to a PDF
- Includes flavors of R, LaTeX, and HTML
- It can be quirky at times, i.e. R code will still run within
an HTML comment unless also commented out


How it works
========================================================



When you run render, R Markdown feeds the .Rmd file to knitr, which executes all of the code chunks and creates a new markdown (.md) document which includes the code and it�s output.

The markdown file generated by knitr is then processed by pandoc which is responsible for creating the finished format.

Slide content from rmarkdown.rstudio.com

The YAML
========================================================
This may be the most confusing part of an R Markdown document

* 


Document Sections
========================================================


Lists
========================================================


Links
========================================================


Citations
========================================================


R code chunks
========================================================


Figures
========================================================



Tables
========================================================

Referencing Tables and Figures
========================================================


Italics and Bold
========================================================