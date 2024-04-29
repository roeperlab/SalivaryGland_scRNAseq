Welcome to the github repo for May et al 2024!

* Final dataset can be found at GEO acession number XXXX - the final dataset used in the paper is file may2024.rds which can be loaded into R and be used as the starting point for any of the analyses below.
* Complete.analysis contains all analysis from loading data the raw data through all generated figures in the paper.

If you are looking for only a specific analysis/figure please see a breakdown of the files below:
* Cellranger_output_to_final_dataset: Supplemental Figure S2, take cellranger outputs found in may_2024_raw and process through seurat to generate may2024.rds 
* Salivary_vs_Epidermal: Figure 1C and 1D, load in may2024.rds and compare marker genes between salivary gland and epidermal sorted cells. Generates tables used for lit review and volcano plots used to compare the two cell types
* Cell_type_markers: Figure 2, load in may2024.rds, generates tables for cluster markers and plots them on the may2024 UMAP
* Additional_subclustering: Figure 3A-C: load in may2024.rds, recluster at a higher resultion (0.3) plot new subgroup of salivary gland cells, generate markers, plot dotplot and volcano plot of markers
* Pseudotime: Figure 3E and F, load in may2024.rds apply subclustering rules and use monocle3 to plot pseudotime values, identfy genes differentially expressed across pseudotime
* Excluded_genes_volcano_plot: Figure 4A and 4C, load in may2024.rds and plot the excluded genes across the different timed cluster points as well as the enhancer of split genes.

Analysis performed by Annabel May - https://github.com/annabel-may
