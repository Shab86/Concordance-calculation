# Concordance-calculation
Script to calculate concordances between imputed &amp; typed SNP's

</b> Imputation output:
imputedfile.gen
imputedfile.sample

Typed output in Plink raw output --recodeA option:
typed_plink.raw

To run:
Rscript concordance.R imputedfile.gen imputedfile.sample typed_plink.raw rsA
/n
Output:
1). Scatter plot PNG file
2). Scatter plot data file 
3). Correlation summary for rsA

