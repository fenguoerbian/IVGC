# IVGC
Efficient two-step procedure to achieve variable selection and estimation under an IV regression framework by incorporating considerable correlation information between variables. The method is applicable in both low and high dimensional situations and the cyclical coordinate descent algorithm is used to solve them.

# Usage
IVGC-manual.pdf provides details of the usage of the package.
# Example

    library("mvtnorm")
    library("glmnet")

    load("simulatedData.RData")
    y=simulatedData$Y
    x=simulatedData$X   
    S=simulatedData$gene
    G=simulatedData$graph
    fit = main(y,x,S,G)
 
 # References
Gao, B., Liu, X., Li, H. and Cui, Y. (2019+) Integrative Analysis of Genetical Genomics Data Incorporating Network Structures. Manuscript.

# Development
The R-package is developed by Xu Liu (liu.xu@sufe.edu.cn) and Yiming Liu.
