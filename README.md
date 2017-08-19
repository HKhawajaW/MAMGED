# MAMGED (Meta-analyis for Microarray Gene Expression Data)
**MAMGED** Is a tool written in R to perform meta-analysis  of  microarray  gene  expression  data  to
* Quantify  absolute  expression  calls.
* Quantification of differential expression calls. 

The current version of this tool is able to handle raw/processed data from three different platforms:
* item 1 Affymetrix
* item 2 Codelink
* item 3 Illumina

The process is to quantify the consistency of absolute expression calls (transcribed or not) made across experiments. The tool can be used to analyze the data from multiple studies across different types of microarray platforms to derive a consensus expression status of genes in a specific tissue or cell-type and a condition of interest. In addition, the tool extends the application of the method to provide a score for the consistency of differential expression pattern for each gene. MAMGED supports single study analysis, multiple study analysis and cross platform study analysis. 
The tool can be run online/offline. For online version user need not to install any package (R and Rstudio) to use the tool. Hoever, for using offline version, [R](https://cran.r-project.org/) and [Rstudio](https://www.rstudio.com/products/RStudio/#Desktop)
