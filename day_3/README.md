# Day 3

## Runing a Seurat tutorial

Please log into your lab computer and create a working directory `day_3`. Alternatively you can login into https://vlab.humboldt.edu if working remotely.

You first need to download the data to `day_3` from the tuorial found here https://satijalab.org/seurat/articles/pbmc3k_tutorial.html

Install the following packages and follow the tutorial

***NOTE*** when the Rstudio asks "Do you want to install from sources the package which needs compilation?" answer "NO"

```
install.packages("dplyr")
install.packages("Seurat")
install.packages("patchwork")


library(dplyr)
library(Seurat)
library(patchwork)
```

Once your libraries are working, move the data to the working directory and `setwd()` appropiately
