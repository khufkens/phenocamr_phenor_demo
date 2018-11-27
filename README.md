# phenocamr & phenor demo

This repository contains some demonstration data to be downloaded directly during a lesson on the use of phenocamr and phenor. Preferrably the data is downloaded before the lesson to avoid network issues.

This demo will need the following R packages (and their dependencies) installed and running on your system. Use the code below to install and load the required packages. You should see no errors (messages are permitted).

```r
install.packages("devtools")
install_github("khufkens/phenor")
install.packages("phenocamr")
install.packages("maps")

library("phenocamr")
library("phenor")
library("maps")
library("raster")
```

The presentation which accompanies the data can be [(re)viewed in a browser](https://khufkens.github.io/phenocamr_phenor_demo/) and the [source R markdown file](https://github.com/khufkens/phenocamr_phenor_demo/blob/master/docs/index.Rmd) is located in the docs folder.