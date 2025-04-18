# Final Project
This repository contains the scripts developed for the final project of the BINF6310 course.

- The analysis performed is based on the study *Expression and Prognosis of CDC45 in Cervical Cancer Based on the GEO Database* by Liu et al. (2021)
- The gene expression data used in this analysis was obtained from the **Gene Expression Omnibus (GEO)** under accession number [GSE63514](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE63514).

  ## Repository structure:

Notebooks for KEGG Pathway Analysis :
- Cell Cycle Pathway (hsa04110)
- DNA Replication Pathway (hsa03030)
  
R Markdown

- PART 1: 
Exploratory data analysis and data loading from GEO, PCA

https://rpubs.com/magal88/1298107

https://rpubs.com/magal88/1298599

- PART 2:
  Volcano plot and Heat map
  
https://rpubs.com/magal88/1298133

- PART 3 :
  ROC curve analysis

- PART 4:
  PPI network using STRING
  
https://rpubs.com/magal88/1298988

Images in png format

Volcano plot (part 2)
Heatmap (part 2)
Combined plot: pca, violin plot and barplot (part 1)
PPI network for CDC45 (part 4)
ROC curve (part 3)

Data sets:

string_interactions_short.tsv 


## Dependendies:
R
Bioconductor
ggplot2
dplyr
pROC

Phyton
Biophyton
pandas
matplotlib


## References

- [Bioconductor](https://bioconductor.org/) - An open-source repository for bioinformatics tools and packages in R.
- [Biostars: Bioinformatics Q&A](https://www.biostars.org/) - A community-driven platform for bioinformatics discussions and resources.
- [dplyr: Data Manipulation in R](https://dplyr.tidyverse.org/) - An R package for data manipulation in R.
- [ggplot2 Documentation](https://ggplot2.tidyverse.org/) - A tool for data visualization in R.
- [GSE63514 Dataset (NCBI GEO)](https://www.ncbi.nlm.nih.gov/geo/geo2r/?acc=GSE63514) - GSE63514 dataset used for cervical cancer analysis.
- HH. (2022). *STRINGdb*. RPubs. https://rpubs.com/HWH/913747
- Liu, Y., Zhang, Y., Wang, X., Wang, J., Yang, J., & Wang, D. (2021). *Expression and prognosis of CDC45 in cervical cancer based on the GEO database*. BMC Cancer, 21(1), 1–11. https://doi.org/10.1186/s12885-021-08789-6
- [pROC: ROC curves](https://cran.r-project.org/web/packages/pROC/index.html) - An R package for visualizing **ROC curves**.
- [R Graph Gallery - Viridis](https://r-graph-gallery.com/package/viridis.html) - A guide for visualizations in R using the **Viridis** color palette.
- [STRING Database](https://string-db.org/) - A tool for exploring protein-protein interactions.





