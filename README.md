# acer_epi_final for acropora cervicornis epibiome dataset for timepoints, T0 and T12
<insert some brief description of the project>
<Emily - you can modify the outline below for your own files to include some descriptions and link to any other scripts or softwares used>

Files in this repository 
-----------

1. Analyses_final.R: Annotated R script for plotting physiological data and generating linear mixed models 
	- Input file: Patchy_Porites_July2019_for_R.csv
	
2. DESeq_PoritesPatch.R: Annotated R script for conducting differential gene expression analysis and KOG term enrichments
	- Input file: AllCountsHost.txt
	- Input file: plob_iso2kogClassNR.tab
	- Input file: amil_iso2kogClassNR.tab
	- Input file: MetaAnalysisFiles.RData
	- Input file: plob_iso2gene.tab
	
	- Output file: hostVSDandPVALS_no_g4_deseq1_4jun_plusPC1.csv
	- Output file: GOpatchHost.csv
	- Output file: GObinaryHostPatch.csv
	- Output file: VSDs_GObinaryHostPatch.csv

3. For gene ontology enrichment scripts and example input files, please visit https://github.com/ckenkel/GO_MWU



# acer_epi_final for acropora cervicornis epibiome dataset for timepoints, T0 and T12

# final_script_acer1.txt            script 
# t0_sample2.csv                    sample data for T0
# t0_seqtab2.rds                    sequence table for T0
# t0_taxonomy.rds                   taxonomy table for T0
# t1_merged_samdata.csv             sample data for T12
# t1merged_seqtab2.rds              sequence table for T12
# t1merged_taxonomy.rds             taxonomy table for T12
