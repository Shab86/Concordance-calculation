# Concordance-calculation
Script to calculate concordances between imputed &amp; typed SNP's

</b> Imputation output:
imputedfile.gen
imputedfile.sample

Typed output in Plink raw output --recodeA option:
typed_plink.raw

To run:
Rscript concordance.R imputedfile.gen imputedfile.sample typed_plink.raw rsA

Output:
1). Scatter plot PNG file

2). Scatter plot data file 

3). Correlation summary for rsA:

MatchingSamples - typed and imputed samples overlap.
MatchingSamplesExclNoCall - typed and imputed samples overlap, excluding NoCalls.
Concordance - correlation between imputed and typed SNP.
         SNP MatchingSamples MatchingSamplesExclNoCall Concordance
1 rsA            1267                       911          0.9223097
