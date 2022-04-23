<image src="./doc/images/logo.png" width="400"> 
  
**High_order_SComparsion** is an R package for detecting differenital genes in single cell profiles in high-order level. This tool is developed and maintained by [Ken chen's lab](https://sites.google.com/view/kchenlab/Home) in MDACC. Although there are many tools avaiable for detecting cell abundacne difference among single cell samples, such as [miloR](https://github.com/MarioniLab/miloR) and [CNA](https://github.com/immunogenomics/cna)
  
  n of single cell profiles, such as [Seurat](https://satijalab.org/seurat/), [Liger](https://github.com/MacoskoLab/liger) and [Harmony (https://github.com/immunogenomics/harmony) did not work on this case unless match feature empricallcy. For example, integration of scRNA-seq and scATAC-seq data requires to calculate the gene/promoter activity by counting peaks in gene body, which always loses information. This strategy also did not work on integrating scRNA-seq and cytof data becasue gene pression and protein abundance level is not always correlated due to sparsity of scRNA-seq data or post translational modification. 
