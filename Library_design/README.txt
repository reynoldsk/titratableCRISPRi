Mathis et. al 2020

This folder contains notebooks and outputs used to select genes for titrated CRISPRi and construct the sgRNA library used in this research.



Contents: #######################################

Blast: Folder containing output files from BLASTn searches on potential sgRNAs. The files currently present in this folder were used in the design of our sgRNA library.

Gradients: Folder containing all possible sgRNAs for each targeted gene.

Outputs: Folder containing sgRNA sequences for BLAST analysis as well as a finalized .fasta file with all complete sgRNA and flanking squences.

Mathis_Gene_Selection.ipynb: Selects genes to be targeted for knockdown using CRISPRi titration. Contains random sampling, so subsequent executions will not always recreate the same results seen previously or in Mathis et al. 2020. Creates Figure 1A and Figure S2.

Titrated CRISPRi sgRNA Design.ipynb: Finds three on-target sgRNAs for each gene of interest and permutes a library of partially mismatched sequences for titrated CRISPRi.

README.txt: This file.



Written by Ryan Otto ############################

Updated July 9, 2020