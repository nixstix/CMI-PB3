The original pipeline is specified under `MOFA_7assays`. Any changes to this pipeline are documented below.

## MOFA/first_pass_noScale_train.Rmd

Changed path in first chunk
Removed geneExp assay

```
knitr::opts_knit$set(root.dir = '/mnt/BioAdHoc/Groups/Peters/nthrupp/CMI-PB3/MOFA_6assays/MOFA/')
nr_factors = 15

assays = c( "ab" , "cytokineO" ,"cytokineL", "cell_freq" ,"tcellPol" ,"tcellAct")
```

## MOFA/prep_testData.R

At line 14 we have changed the number of assays from 7 to 6

```
assays = c( "ab" , "cytokineO" ,"cytokineL", "cell_freq" ,"tcellPol" ,"tcellAct")
```
