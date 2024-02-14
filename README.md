# The_spatially_resolved_transcriptome_signatures_of_glomeruli_in_chronic_kidney_disease
 Data analysis of the spatially resolved transcriptome for the paper by Geremy Clair et al.

This repository contains the details of the GeoMX data analysis for the paper  titled : “The spatially resolved transcriptome signatures of glomeruli in chronic kidney disease“ by Hasmik Soloyan and collaborators. 

The data was pre-processed using Nanostrings tools.

The R markdown and the knitR html report are located in the main folder of the repository

All the files generated during the data analysis are located in the folder 03_Output_files.

We used the following packages under their current version as of 10-09-2023 for the analyses
- [ExperimentHub](https://bioconductor.org/packages/release/bioc/html/ExperimentHub.html) to create spatial data format compatible with StandR
- [StandR](https://bioconductor.org/packages/release/bioc/html/standR.html) was used to evaluate the normalization method
- [EdgeR](https://bioconductor.org/packages/release/bioc/html/edgeR.html) to perform the TMM normalization
- [RomicsProcessor](https://github.com/PNNL-Comp-Mass-Spec/RomicsProcessor) to perform statistics and visualization of the data
- [Protein-MiniOn] (https://github.com/GeremyClair/Protein_MiniOn) to perform enrichment analyses.
- [Limma] (https://bioconductor.org/packages/release/bioc/html/limma.html) for some specific plots
- [ggpubr] (https://cran.r-project.org/web/packages/ggpubr/index.html) for the visualization of transcript boxplot with values
- [ggalluvial](https://cran.r-project.org/web/packages/ggalluvial/vignettes/ggalluvial.html) for the visualization of metadata
- [scater] (https://bioconductor.org/packages/release/bioc/html/scater.html) for some map visualization
- [DT] (https://rstudio.github.io/DT/) for the visualization of some tables
Please let us know if you need any assistance in executing or understanding this code.
