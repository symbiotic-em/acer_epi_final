<insert some brief description of the project>
<Emily - you can modify the outline below for your own files to include some descriptions and link to any other scripts or softwares used>

R scripts and input files for completing analyses described in "Host-specific epibiomes of distinct Acropora cervicornis genotypes persist after field transplantation", Emily Aguirre, emilyagu@usc.edu

We studied the epibiome of ten Acropora cervicornis genotypes residing at an in-situ nursery (T0) and after transplantation to nine different environments, one year later (T12) to investigate the relative roles of host genotype and environment in structuring the epibiome. We applied amplicon sequencing of the 16S rRNA gene to assess microbial composition, richness and beta-diversity throughout time and sites.

Annotations in the .R script describe input files, although all analyses can be re-created by starting with the raw .fastq files available for download at NCBI SRA under accession code: PRJNA630333.
	
Files in this repository 
-----------

1. final_script_acer1.txt: Annotated R script for 16S rRNA epibiome analysis, including alpha-diversity, beta-diversity, core microbiome and plotting visualizations
	- Input file: t0_sample2.csv                    sample data for T0
	- Input file: t0_seqtab2.rds                    sequence table for T0
	- Input file: t0_taxonomy.rds                   taxonomy table for T0
	- Input file: t1_merged_samdata.csv             sample data for T12
	- Input file: t1merged_seqtab2.rds              sequence table for T12
	- Input file: t1merged_taxonomy.rds             taxonomy table for T12
	
	
2. For phylogenetic analysis/placement of MD3-55 sequences in this dataset and input files, please visit https://github.com/symbiotic-em/md355_phylotree











