This repository contains code and data to reproduce analysis in the research article:

## **Antithrombotic Regimens for the Prevention of Major Adverse Cardiac Events in Chronic Coronary Syndrome: A Systematic Review and Network Meta-Analysis
**

PROSPERO: CRD42022308499

## Project organization

```
├── analyses         <- Data wrangle, model fitting, figures, tables and supplementary material code
├── data             <- Extracted data from included studies
├── functions        <- Custom function to automate model diagnostics
└── output           <- Model outputs and figures files
```

## Getting started

All analyses were conducted in R (R Environment version 4.1.2). 

1.  To download all files and reproduce our analyses, clone this repository using Git's integration with RStudio. Here is a tutorial article in case you are not familiar with this process:

    *Vuorre M, Curley JP. Curating Research Assets: A Tutorial on the Git Version Control System. Advances in Methods and Practices in Psychological Science 2018;1:219–36.* [https://doi.org/10.1177%2F2515245918754826](https://doi.org/10.1177%2F2515245918754826)

       After cloning this repository, open the `toci_sari_bari.Rproj` file and you will be able to run all files.

2. Bayesian models were fitted with the R package [multinmma](https://dmphillippo.github.io/multinma/) in this folder.

3. We used the R package [{renv}](https://rstudio.github.io/renv/) to make this R project as reproducible as possible. In summary, {renv} guarantees that all required R packages for this project are downloaded to your computer in their necessary versions. Please check their ["Get Started" vignette](https://rstudio.github.io/renv/articles/renv.html) in case you would like to learn more about it.
