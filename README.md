# Checking errors in ALSPAC round 1 and 2 imputed data

Create a `config.json` file:

```json
{
    "round1bfile": "/path/to/round1/data_chr22",
    "round2bfile": "/path/to/round2/data_chr22"
}
```

Make sure plink 1.90 is installed on your PATH.

Render the `analysis.rmd` file in R using

```r
library(rmarkdown)
render("analysis.rmd")
```

