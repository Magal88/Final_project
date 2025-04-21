# Final Project
This repository contains the scripts developed for the final project of the "Introduction to Computational Methods in Bioinformatics" (course BINF6310) at Northeastern University.

The analysis performed is based on the study Expression and Prognosis of CDC45 in Cervical Cancer Based on the GEO Database by Liu et al. (2021)

The gene expression data used in this analysis was obtained from the Gene Expression Omnibus (GEO) under accession number [GSE63514](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE63514).

This project investigates CDC45's role in cervical cancer by exploring molecular pathways, performing differential expression analysis (DEGs), and analyzing the protein-protein interaction (PPI) network to understand its impact on cancer progression and prognosis.

## Repository Structure

The repository is organized as follows:

- **R**: Contains the R scripts for the analysis.
- **Python**: Contains the Python scripts for the analysis.
- **Visualizations**: Contains the images of the visualizations generated during the analysis.
- **STRING**: Contains additional files such as instructional materials and useful resources.



## Notebooks for KEGG Pathway Analysis

- Cell Cycle Pathway (hsa04110)
- DNA Replication Pathway (hsa03030)

## Rpubs Links

- **PART 1: Exploratory data analysis (EDA)**: [Link](https://rpubs.com/magal88/1298599)
- **PART 2: Loading GEO Data and Principal Component Analysis (PCA)**: [Link](https://rpubs.com/magal88/1298107)
- **PART 3: Differential Expression Analysis: Volcano Plot and Heatmap**: [Link](https://rpubs.com/magal88/1298133)
- **PART 4: PPI network using STRING**: [Link](https://rpubs.com/magal88/1298988)

## Data sets:

- `string_interactions_short.tsv`

## Dependencies

### R

install.packages("BiocManager")
BiocManager::install()

install.packages(c("ggplot2", "dplyr"))

### Python

 pip install biopython pandas matplotlib


## Resources

STRING_PPI: How to Download the STRING Database for Use in R


## References

- [Bioconductor](https://bioconductor.org/) - An open-source repository for bioinformatics tools and packages in R.
- [Biostars: Bioinformatics Q&A](https://www.biostars.org/) - A community-driven platform for bioinformatics discussions and resources.
- Data to Viz. (n.d.). *From Data to Viz: A classification of chart types based on input data*. Retrieved from [https://www.data-to-viz.com/](https://www.data-to-viz.com/)
- [dplyr: Data Manipulation in R](https://dplyr.tidyverse.org/) - An R package for data manipulation in R.
- [ggplot2 Documentation](https://ggplot2.tidyverse.org/) - A tool for data visualization in R.
- [GSE63514 Dataset (NCBI GEO)](https://www.ncbi.nlm.nih.gov/geo/geo2r/?acc=GSE63514) - GSE63514 dataset used for cervical cancer analysis.
- HH. (2022). *STRINGdb*. RPubs. https://rpubs.com/HWH/913747
- Liu, Y., Zhang, Y., Wang, X., Wang, J., Yang, J., & Wang, D. (2021). *Expression and prognosis of CDC45 in cervical cancer based on the GEO database*. BMC Cancer, 21(1), 1–11. 
  https://doi.org/10.1186/s1288508789-6
- [R Graph Gallery - Viridis](https://r-graph-gallery.com/package/viridis.html) - A guide for visualizations in R using the **Viridis** color palette.
- [STRING Database](https://string-db.org/) - A tool for exploring protein-protein interactions.





