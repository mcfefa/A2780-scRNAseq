# A2780-scRNAseq
single-cell RNAseq analysis pipeline for A2780 treatment resistance

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
 
 