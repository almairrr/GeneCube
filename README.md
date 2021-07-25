# The Gene Cube

Gene cube is a three-dimensional matrix, where the dimensions consist of ***genes***, ***observations***, and ***chromosomes***. The advantage of this gene cube approach is that the data structure is formed by considering the chromosomes of each gene. This approach can be useful in understanding the mechanisms of disease and tumors in general. By testing the gene cube using ***K-means algorithm*** which initial steps is optimized using ***K-means++ algorithm*** and ***𝛿-Trimax triclustering algorithm***, it has been proven that gene cube structure could provide information about groups of gene expression that have a similar pattern. <br>

This gene cube approach was proposed by George I. Lambrou, Maria Sdraka, and Dimitrios Koutsouris on [The "Gene Cube": A Novel Approach to Three-Dimensional Clustering of Gene Expression Data](https://www.eurekaselect.com/169062/article). <br>

This research used gene expression dataset from [bladder cancer](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE7476) with different stages of tumor. The dataset consisted of 9 bladder cancer observations and 3 control observations, where each observation consisted of 45,746 genes. <br>
