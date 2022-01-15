# RNAseq
## Analyzing scRNA  sequencing dataset with the scanpy python package.

[retina_10x_smart](https://github.com/zsamadi/RNAseq/blob/main/retina_10x_smart.ipynb) Jupytert notebook performs an analysis of the cell types and their marker genes on the 10x single cell RNA-seq data from the developing mouse retina, [here](https://github.com/gofflab/developing_mouse_retina_scRNASeq/blob/master/README.md),  and [GSE118614_Smart](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE118614) dataset.

10X data files, including count matrix, and Cellular Phenotype Data should be copied into sdata10x folder. Rename count matrix to matrix.mtx before performing the analysis.

Minor modifications were made on the dataset to make it proper to be read with scabpy read_10x_mtx command. All necessary files for smartsed dataset are included in [sdata](https://github.com/zsamadi/RNAseq/tree/main/sdata) folder, except the [matrix.mtx](https://drive.google.com/uc?id=1yBlJ-lbGgYED3P_ziVffwZR1PmVDsFnT&export=download) file which I couldn't upload here due to its large size. This file should be downloaded, and copied into [sdata](https://github.com/zsamadi/RNAseq/tree/main/sdata) folder before running the notebook.

[retina_10x_Early](https://github.com/zsamadi/RNAseq/blob/main/retina_smart_Early.ipynb) performs the analysis of the cell types and their marker genes on the Early RPC cells of the 10x single cell RNA-seq data 

[retina_10x_Early_E14E18P2](https://github.com/zsamadi/RNAseq/blob/main/retina_10x_Early_E14E18P2.ipynb) performs the analysis of the cell types and their marker genes on the Early RPC cells of the 10x single cell RNA-seq data filtered to ages E14, E18 and P2

[retina_smart_Early](https://github.com/zsamadi/RNAseq/blob/main/retina_smart_Early.ipynb) performs the analysis of the cell types and their marker genes on the Early RPC cells of the GSE118614_Smart dataset. 

Ribosormal genes were highly expressed in Early RPC cells, and were excluded from downstream analysis along with mitochondrial and hemoglobin genes. 


