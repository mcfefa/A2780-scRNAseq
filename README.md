# A2780-scRNAseq
single-cell RNAseq analysis pipeline for A2780 treatment resistance

### Overview 
This repository contains code used in the analysis of A2780 cell line. The code is written in R (tested on versions 4.3.3) and is presented in a R Markdown (A2780S_DE+Trajectory.Rmd). The code chunks within the markdown are designed to be dependent on the previous chunk. 

### Requirements 
 - R version 4.0 or newer
 - R studio
 
### Package requirements 
 - future
 - ggplot2
 - bigmemory
 - Seurat
 - clustree
 - dplyr
 - data.table
 - SeuratWrappers
 - monocle3
 - SingleCellExperiment
 - slingshot
 
### Project contents
 - `README.md` : this file with information about the repository 
 - `A2780S_DE+Trajectory.Rmd` : R Markdown containing code chunk for data analysis and figures of differential expressed genes and trajectory. The code chunks within the markdown are designed to be dependent on the previous chunk. Nevertheless, data from each chunk are saved sequentially and can be loaded to execute in the subsequent step.
 - `A2780S_Pathway_Analysis.Rmd` : R Markdown containing code chunk for pathway analysis. The code chunks within the markdown are designed to be run after Step 8 from `A2780S_DE+Trajectory.Rmd`
 - `A2780S_DE+Trajectory (0_1).docx` : Word document of R Markdown containing code and figure for resolution 0.1
 - `A2780S_DE+Trajectory (0_15).docx` :  Word document of R Markdown containing code and figure for resolution 0.15
 - `A2780_Final_Report.docx` : Report file for A2780 
 
### Acknowledgments
We would like to thank Meghan C. Ferrall-Fairbanks and Adriana Del Pino Herrera for support and guidance. Figure 10 and 11 were created with GraphPad
