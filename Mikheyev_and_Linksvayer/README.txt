README FOR 

Mikheyev SM and TAL Linksvayer. Genes associated with ant social behavior show distinct transcriptional and evolutionary patterns.

CONTENTS

1. README.txt	-	this file
2. monomorium_2014-12-08.sql.gz	- MySQL database for the transcriptional, network connectedness, molecular evolution, and GO term analysis
3. monomorium tables.zip	- separated data tables from MySQL database as zipped .csv files  
4. data summary by gene.csv	- summary of data listed by M. pharaonis gene in comma deliminated (.csv) format. Header line with variables: gene is the M. pharaonis gene name; evalue, hit, and species describe the best BLAST hit; kTotal, kWithin, kOut, kDiff are the estimated of network connectedness from WGCNA; behavioral cateogry is whether the gene is upregulated in foragers, nurses, or not differentially expressed ("all others"); fire ant ortholog is whether the gene has an identified ortholog in Solenopsis invicta; honey bee ortholog is whether the gene has an identified ortholog in Apis mellifera; fpkm is the level of expression; ortholog is whether the gene has an identified ortholog for both A. mellifera and S. invicta, neither, or Sinv or Amel only; dNdS is the estimate of rate of molecular evolution;
5. raw behavioral scan data.csv	- table in .csv format of raw behavioral scan data showing each observation of age-marked individuals.Header line with variables: colony is whether the observation is from replicate colony b or c; date is the data of observation; age is the age of observed age-marked individual workers; behavior is the behavioral code, which is described in the Supplemental Table 1.csv
6. total behavioral counts by age class.csv - table in csv format of total counts for each age cohort. Header column with variable: age is the age cohort of individuals observed; the remaining columns are the behavioral categories that significantly changed over the course of the study