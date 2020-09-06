#### R Markdown vs Notebooks
![](./extra/images/md-vs-notebook.png)

#### knit function
This function takes an input file, extracts the R code in it according to a list of patterns, evaluates the code and writes the output in another file. It can also tangle R source code from the input document.

#### Knitr
knitr is the R package that we use to convert an R Markdown document into another, more user friendly format like .html or .pdf.

#### R Code blocks
- 3 instead of 2 backticks

``{r}
  
``

#### Assinging values to variables in R ( <- operator )
name <- "name1"