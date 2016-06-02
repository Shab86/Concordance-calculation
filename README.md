# Concordance-calculation
Script to calculate concordances between imputed &amp; typed SNP's

## Imputation files:
```
imputedfile.gen
imputedfile.sample
```

## Typed output in Plink raw format:
```
typed_plink.raw (use  --recodeA option)
```

## To run:
```
Rscript concordance.R imputedfile.gen imputedfile.sample typed_plink.raw rsA
```

## Output:
```
Scatter plot PNG file
Scatter plot data file 
Correlation summary for rsA
```
