# CIBERSORTx
Collaboration with Chang's Lab

File desciptions:

1) CIBERSORTx.Rmd
  R script for performing comparative analysis between Yunhua's ABIS cell deconvolution and Hernan's CIBERSORTx cell deconvolution, together with statistical analysis of CIBERSORTx cell deconvolution across the five experimental groups. 

2) R Notebook CIBERSORTx.pdf
  R notebook report from CIBERSORTx.Rmd
  
3) Mock_samples_from_scRNAseq.Rmd
  R script for generating mock samples from scRNAseq data and input file for signature matrix. It generates the following files:
  
    a) mock_expression_table_2.txt (Table with gene expression profiles in TPMs per sample for several unrelated mock samples)
    
    b) mock_expression_table_by_cell_2.txt (Table with gene expression profiles in TPMs per sample and per cell type for several unrelated mock samples)
    
    c) mock_composition_table_2.txt (Table with cell composition profiles in TPMs per sample for several unrelated mock samples)
    
    d) mock_expression_table_GEP.txt (Table with gene expression profiles in TPMs per sample from two simulated groups, A and B)
    
    e) mock_expression_table_by_cell_GEP.txt (Table with gene expression profiles in TPMs per sample and per cell type from two simulated groups, A and B)
    
    f) mock_composition_table_GEP.txt (Table with cell composition profiles in TPMs per sample from two simulated groups, A and B)
    
    g) sourat_signature_martix_RPKM.txt (Table that can be used as input for generating a signature matrix in TPMs)
