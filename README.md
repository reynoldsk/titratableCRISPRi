# titratableCRISPRi
code (iPython notebooks) used in analyzing titratable CRISPRi experiments
This is a collection of notebooks, necessary inputs, and relevant outputs to recreate all data analysis and figures from Mathis et al. 2020.

Notebooks are analyzed using iPython 2 in most cases, barring Mathis_Figure_5_Media_Condition_4_Param_Logistic_Python3.ipynb, which must be run in an iPython 3 environment (venn library is only accessible in Python 3). The ordering of notebooks in this README is the recommended execution order for new data.

This code was created and edited by Andrew Mathis, Ryan Otto, and Kimberly A. Reynolds

Copyright (C) 2020 Andrew Mathis, Ryan Otto, Kimberly Reynolds
This program is free software distributed under the BSD 3-clause
license, please see the file LICENSE for details.

Contents:

Mathis_hiSeq_analysis.ipynb: Takes sgRNA counts at all timepoints and calculates and normalizes growth rates to a non-targeting negC. Creates Figure S3, Table S1, Table S3, and Table S4.

Mathis_Figure_2_Growth_Rate_vs_Timepoint.ipynb: Analyzes how growth rate changes over time following complete induction of CRISPRi. Also visualizes data quality before and after correcting for escapers - cell lineages that overcome CRISPRi-dependent growth defects during the time course of our experiment. Creates Figure 2 (barring Figure 2A, which is synthetic data), Figure S4, Figure S5A-G, and Figure S6A-C. 

Mathis_Figure_3_CRISPRi_heatmap.ipynb: Clusters genes based on growth effects of SG1 compounding mismatch sgRNAs in glucose. Plots heat maps of growth rate over time for all genes and sgRNAs according to this clustering. Creates Figure 3.

Mathis_Figure_4_Resolvable_Steps.ipynb: Calculates the maximum number of statistically resolvable growth effects that can be achieved using a set of sgRNAs targeting the same gene. Creates Figure 4 and Figure S6D.

Mathis_Figure_5_Media_Condition_4_Param_Logistic_Python3.ipynb: Must use an iPython 3 environment to execute this notebooks. Fits a four-parameter logistic curve to the relationship between growth effect and mismatch number for SG1 compounding mismatch sgRNAs. Identifies statistically significant changes in each of these four parameters between glucose and glycerol. Creates Figure 5, Figure S8, Figure S9, and Figure S10.

Mathis_Figure_S1_qPCR.ipynb: Calculates relative mRNA abundance of targeted genes following CRISPRi using qPCR data. Correlates these abundances to growth rate in a pilot turbidostat experiment. Creates Figure S1.

Mathis_Figure_S5H-I_Plate_Reader_Growth_Rate.ipynb: Calculates relative growth rate from plate reader data of individual cell lines expressing a single sgRNA targeting either metK or glyA, as opposed to the pooled populations measured in the turbidostat. Correlates plate reader growth rate data to turbidostat growth rate data. Creates Figure S5H-I.

Mathis_Figure_S7A_Plate_Reader_Growth_Rate.ipynb: Calculates relative growth rate from plate reader data of individual cell lines expressing a single sgRNA targeting a gene of interest, as opposed to the pooled populations measured in the turbidostat. Correlates plate reader growth rate data to turbidostat growth rate data. Creates Figure S7A.

Mathis_Figure_S7B_qPCR.ipynb: Calculates relative mRNA abundance of targeted genes following CRISPRi using qPCR data. Correlates these abundances to growth rate in a pilot turbidostat experiment. Creates Figure S7B.

Figures: Folder containing all figures output by these notebooks. Figures included in Mathis et al. 2020 end in '_Fig*.pdf'.

inputs: Folder containing all inputs needed for these notebooks prior to any analysis. An additional README exists in inputs describing these files individually.

Library_Design: Folder containing scripts and outputs for the gene selection and sgRNA design strategies used in this work. Gene selection contains random sampling, so future iterations will not always reproduce identical results. All results and sequences used in this analysis, including some output from initial instances of Library_Design scripts, are located in the main inputs folder. An additional README exists in Library_Design describing these files individually.

outputs: Folder containing all non-pickled outputs of these notebooks. Output stored here by one notebook may be referenced by another.

pickle: Folder containing all pickled outputs of these notebooks. Output stored here by one notebook may be referenced by another.

Tables: Folder containing all tables output by these notebooks. Table S2, which lists sequences used for common primers, was placed in this folder as well, though it is not created by any notebook in this repo.

README.txt: This file.


Written by Ryan Otto
Updated 23 July 2020.
