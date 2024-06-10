# eQTL_analysis

## Purpose: Expression quantitative trait loci (eQTL) identification for a population of 33 healthy canines. 

1) Genotypes preprocessing
* I was provided with two tsv files including the genotype data from Axiom without their supporting files, therefore I was not able to use bcftools affy2vcf to create the vcf file so I wrote my own function to convert these files to vcf files (See genotyping_code.R)
* All data was then lifted over to canfam4 (code)
* The vcf file was then imputed using Beagle (code) 
2) Phenotypes preprocessing
3) Covariates
4) Running tensorQTL 


