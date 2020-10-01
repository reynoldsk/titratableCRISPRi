Mathis et al. 2020

This folder contains all necessary inputs to run the notebooks in the full repo. Note: For some file types (ex: luna_rtqpcr data), more files of the same format can be added into inputs and the appropriate notebooks for additional analysis.



Contents:

counts: Folder containing sgRNA count data from all timepoints for glucose and glycerol media conditions. Data counted using scripts for supercomputing on UT Southwestern's BioHPC.

20190808_luna_rtqpcr_quant.csv: Raw qPCR data file for serC mRNA abundance. Column 3 lists the gene quantified in a given well. Column 5 lists the sgRNA used in this well. Column 6 lists the raw Cq value for this gene in this well.

20191111_sgRNA_lib.fasta: Fasta file containing sgRNA sequence information.

20200203_turb_growth.pickle: Contains rescaling information for timepoints in each media condition.

20200207_selected_genes_chem.csv: Basic information on all genes selected for CRISPRi titration. Includes gene name, length, growth in MOPS, and others.

20200212_luna_rtqpcr_quant.csv: Raw qPCR data file for dapA/dapB mRNA abundance. Column 3 lists the gene quantified in a given well. Column 5 lists the sgRNA used in this well. Column 6 lists the raw Cq value for this gene in this well.

20200221_luna_rtqpcr_quant.csv: Additional raw qPCR data file for serC mRNA abundance. Column 3 lists the gene quantified in a given well. Column 5 lists the sgRNA used in this well. Column 6 lists the raw Cq value for this gene in this well.

20200304_plate_reader_metK_glyA.txt: Raw plate reader OD data for cell lines expressing metK or glyA sgRNAs. Column 3 lists the well measured. Column 5 lists the time of the first measurement. Column 6 lists the OD of the first measurements. Columns 7 and 8 are the same for the second measurement, and 9 and 10 are the same for the third measurement.

20200307_plate_reader_metK_glyA.txt: Additional raw plate reader OD data for cell lines expressing metK or glyA sgRNAs. Column 3 lists the well measured. Column 5 lists the time of the first measurement. Column 6 lists the OD of the first measurements. Columns 7 and 8 are the same for the second measurement, and 9 and 10 are the same for the third measurement.

20200509_turb_pilot.csv: Contains growth rate information from a pilot turbidostat experiment using CRISPRi on a smaller sample of genes using fewer sgRNAs per gene.

20200730_plate_reader.txt: Raw plate reader OD data for cell lines expressing sgRNAs targeting select genes of interest. Column 3 lists the well measured. Column 5 lists the time of the first measurement. Column 6 lists the OD of the first measurements. Columns 7 and 8 are the same for the second measurement, and 9 and 10 are the same for the third measurement.

20200806_luna_rtqpcr_quant.csv: Raw qPCR data file for mRNA abundance of select genes of interest. Column 3 lists the gene quantified in a given well. Column 5 lists the sgRNA used in this well. Column 6 lists the raw Cq value for this gene in this well.

20200813_luna_rtqpcr_quant.csv: Additional raw qPCR data file for mRNA abundance of select genes of interest. Column 3 lists the gene quantified in a given well. Column 5 lists the sgRNA used in this well. Column 6 lists the raw Cq value for this gene in this well.

df_guides_dict.csv: Contains lists of guide names included in different families or groups of guides, such as guides with compounding mismatches.

e_coli_gene_sequences_NC_000913p3.txt: Fasta information for all annotated genes in E. coli MG1655.

e_coli_genome_CP032667p1.txt: Full E. coli MG1655 genome sequence.

gene_selection_Aebersold_p_conc.csv: Information on protein concentration from E. coli genes to use in gene selection.

gene_selection_chromosomal_location.csv: Information on chromosomal location of E. coli genes to use in gene selection.

gene_selection_Keio_essential.csv: Information on growth effect following E. coli gene knockout to use in gene selection.

gene_selection_yfp_fusion.csv: Information on YFP fusion availability for E. coli genes to use in gene selection.

miSeq_raw_counts.pickle: sgRNA count data from a MiSeq run on the untransformed sgRNA library.

README.txt: This file



Written by Ryan Otto

Updated July 8, 2020