# MAMGED (Meta-analyis for Microarray Gene Expression Data)
**MAMGED** Is a tool written in R to perform meta-analysis  of  microarray  gene  expression  data  to  quantify  absolute  expression  calls  and differential expression calls. The current version of this tool is able to handle raw/processed data from three different platforms i.e. Affymetrix, Codelink and Illumina. The process is to quantify the consistency of absolute expression calls (transcribed or not) made across experiments. The tool can be used to analyze the data from multiple studies across different types of microarray platforms to derive a consensus expression status of genes in a specific tissue or cell-type and a condition of interest. In addition, the tool extends the application of the method to provide a score for the consistency of differential expression pattern for each gene. MAMGED supports single study analysis, multiple study analysis and cross platform study analysis. 
The tool can be run online/offline. For online version user need not to install any package (R and Rstudio) to use the tool. Hoever, for using offline version, [R](https://cran.r-project.org/ R) and [Rstudi](https://www.rstudio.com/products/RStudio/#Desktop RStudio)
