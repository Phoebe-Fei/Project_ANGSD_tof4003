# Project_ANGSD_tof4003
NMR liver RNASeq Analysis, differential analysis between sex; breed status

## Vignette.Rmd
The main project workflow is described in this .Rmd. Guides from step 1 to the final results. Analysis in R is also done in this file.

## Vignette.html
Rendered html file of the Vignette.Rmd file

## QC htmls (directory)
Contains all QC htmls for quality access of the fastq and alignment

## Result Plot (directory)
Contains all output plots from this analysis, some are used in the results section of the report

## Checkpoint1_scratch.html
Copied from the previous checkpoint homework. Use as a code guidance and also contains some Q & A. Rendered to Checkpoint1_scratch.Rmd (not included) - some pictures are in local directory are not shown in Rmd

## SraRunTable_liver.txt
Downloaded NMR liver metadata file from ensembl 

## NMR_female_ref.gz
Downloaded .bed file for alignment QC analysis (from UCSC table browser)

## hisat2_featCounts_femaleNMR.txt.summary
HISAT2 female count table summary

## hisat2_featCounts_maleNMR.txt.summary
HISAT2 male count table summary

## star_featCounts_femaleNMR.txt.summary
Star female count table summary

## star_featCounts_maleNMR.txt.summary
Star male count table summary

## hisat2_featCounts_femaleNMR.txt.gz
Zipped HISAT2 female feature count table

## hisat2_featCounts_maleNMR.txt.gz
Zipped HISAT2 male feature count table

## star_featCounts_femaleNMR.txt.gz
Zipped STAR female feature count table

## star_featCounts_maleNMR.txt.gz
Zipped STAR male feature count table

## Results_test_breed_HISAT2_top100.csv	
**Key data output**: Top 100 differentially expressed genes filtered for breeds status, aligned by HISAT2. Contains gene name, gene biotype, the p-values, significance level (y/n) and more information. 

## Results_test_breed_STAR_top100.csv
**Key data output**: Top 100 differentially expressed genes filtered for breeds status, aligned by STAR. Contains gene name, gene biotype, the p-values, significance level (y/n) and more information. 

## Results_test_sex_HISAT2_top100.csv	
**Key data output**: Top 100 differentially expressed genes filtered for sex status, aligned by HISAT2. Contains gene name, gene biotype, the p-values, significance level (y/n) and more information. 

## Results_test_sex_STAR_top100.csv
**Key data output**: Top 100 differentially expressed genes filtered for sex status, aligned by STAR. Contains gene name, gene biotype, the p-values, significance level (y/n) and more information. 