Welcome to paperplanning hub for May et al 2024!

* Final dataset can be found at GEO acession number XXXX - the final dataset used in the paper is file may2024.rds
* Complete.analysis contains all analysis from loading data through all generated figures.

If you are looking for a specific analysis/figure please see a breakdown of the files below:
* Cellranger_output_to_final_dataset: Supplemental Figure S2, take cellranger outputs found in may_2024_raw and process through seurat to generate may2024.rds 
* Salivary_vs_Epidermal: Figure 1C and 1D, load in may2024.rds and compare marker genes between salivary gland and epidermal sorted cells. Generates tables used for lit review
* Cell_type_markers: Figure 2, load in may2024.rds, generates tables for cluster markers and plots them on the may2024 UMAP
* Additional_subclustering: Figure 3A-C: load in may2024.rds, recluster at a higher resultion (0.3) plot new subgroup of salivary gland cells, generate markers, plot dotplot and volcano plot of markers
* Pseudotime: Figure 3E and F, load in may2024.rds apply subclustering rules and use monocle3 to plot pseudotime values, identfy genes differentially expressed across pseudotime
* Excluded_genes_volcano_plot: Figure 4A and 4C, load in may2024.rds and plot the excluded genes across the different timed cluster points as well as the enhancer of split genes.

All code written by me unless outlined in the comments. 
