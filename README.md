# Resources for analyzing and visualizing bench experiments in the informatics space

## Overview:

Welcome! This repository is intended for storing code and providing external resources for analyzing/visualizing experimental data in biomedical sciences. For example:

* Visualizing pyrosequencing data in R
* Reading and visualizing DNA fragment data files (instrument) into R
* Genomic data visualization in R with example data sets

We aim to provide resources to better translate bench-top data into the computational realm. We try to bridge the gaps in tools that are currently lacking or requires improvement.

Please note relevant references, which may include the names of software packages used/dependent upon and journal articles reporting the software. We thank authors and developers who distributed their software packages.

While the main programming language is R, tools based in other languages such as Unix/Linux, python, matlab, and C may be included in the future. Tutorials may be written in R Markdown (.rmd) or LaTex (.tex).

## General R software packages for analyzing bench experiments:

* Analysis of flow-cytometry data using the [`flowCore` R/Bioconductor pakcage] (https://bioconductor.org/packages/release/bioc/html/flowCore.html)
* Analysis of quantitative polymerase chain reaction (qPCR) in R: [`qpcR`] (https://cran.r-project.org/web/packages/qpcR/index.html), [`HTqPCR`] (https://www.bioconductor.org/packages/release/bioc/html/HTqPCR.html), [`EasyqPCR`] (https://www.bioconductor.org/packages/release/bioc/html/EasyqpcR.html)
* Analysis of [dose response curve in R] (https://cran.r-project.org/web/packages/drc/index.html)

## Useful bioinformatics tools:

* [PAM50 gene list and sample R code by J.S. Parker et al. (J Clin. Oncol. 2009; .zip folder)] (https://genome.unc.edu/pubsup/breastGEO/PAM50.zip)
* [SWITCHdna R functions and sample dataset by Weigman V.J. et al. (Breast Cancer Res. Treat. 2011)] (https://genome.unc.edu/pubsup/SWITCHdna/)
* [Estimation of STromal and Immune cells in MAlignant Tumours using Expression data (ESTIMATE), Yoshihara et al. 2013 Nature Comm.]  (http://bioinformatics.mdanderson.org/main/ESTIMATE:Overview)

## Other resources:

* [Good coding practice for R, python, and shell (courtesy of Dr. M. Steinbaugh)] (http://steinbaugh.com/guides/programming_style)
* [`tableone` R package for generating summary statistics; especially suitable for reporting epidemiological/clinical results] (https://github.com/kaz-yos/tableone/)

## Coming soon:

* Genomic data visualization using the `Gviz` and `genomation` R/Bioconductor packages
* Reproducible preparation of multiplex ligation-dependent probe amplification training data set in R (original tutorial was in Excel)
