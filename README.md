# IVGC
Efficient two-step procedure to achieve variable selection and estimation under an IV regression framework by incorporating gene network information. The method is applicable in both low and high dimensional situations and the cyclical coordinate descent algorithm is used to solve them.

# Usage
Download the IVGC_1.0.1.tar.gz for Windows user to loacal computer, and install it loacally.

    IVGC-manual.pdf ---------------- Details of the usage of the package.
    IVGC_1.0.1.tar.gz  ------------- The package for Windows user.
    IVGC_1.0.1_mac.tar.gz  --------- The package for Mac user.
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
