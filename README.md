# Temperature_shocks_Ztritici
## Heat and cold temperature shocks response phenotypic and transcriptomic analysis of the major pathogen Zymoseptoria tritici
These are the scripts that I have written to study the phenotypic response of *Zymoseptoria tritici* worldwide collections using around 122 strains to heat and cold temperature shocks and the transcriptomic response of the reference strain IPO323 (Goodwin et al. 2011; https://journals.plos.org/plosgenetics/article?id=10.1371/journal.pgen.1002070). The paper has been submitted. I will update this readme once I have the link to the publication. The Genome Wide Associations Studies (GWAS) performed with the 122 strains genomes and the phenotypes analysis can be found in https://github.com/afeurtey/Kmer_GWAS/.


## Phenotypic_data_analysis

In this folder you can find the R Markdown script and its accompaning .html file. This script was made to analyze the data from PDA plates with colonies of the different strains growth after a 15 hour temperature shock treatments. This is a very long script that describes the filtering steps and how I obtained the seven post-shock variables. 

## Transcriptomic analysis

Here there is an R Markdown and its accompaning .html files that all explain how I analyzed the RNAseq data analysis.
The pre processing of the RNA sequences: alignment and Kallisto (https://github.com/pachterlab/kallisto) RNA-seq quantification can be found in https://github.com/afeurtey/Gene_coexpression_network/.   

--- 
### Disclaimer

My .Rmd files were in R Projects, which explains why there might not be a lot of paths to files in my scripts. Some issues might arise depending of system or software versions used, therefore, I cannot promise these scripts can be used directly as they are without a few tweaks. I annotated the scripts and I hope they are clear enough, however, there might be a few missmatches between the comments and the code here and there.  

