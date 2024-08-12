The data that is going to be analyzed in this study was obtained from four different experiments on two different epithelial cell lines, MCF7 and HCC1806, that were isolated from patients with a metastatic adenocarcinoma.

Each cell line was sequenced using two different single cell RNA sequencing techniques called SMARTseq and DROPseq. Our aim is to understand the cells' behaviour under certain environmental conditions.

In particular, we want to predict the different levels of oxygen the cell is under. The oxygen levels we are considering are hypoxia (low) and normoxia (normal). The way we are going to do this is by applying different machine learning methods to our data.

First of all we tried to understand the data in depth and prepared it to be put in different algorithms; this was done by visualizing the data, cleaning it(studying the sparsity of the data and removing missing variables,outliers, and irregularities).

After we applied different learning methods: supervised and unsupervised. The unsupervised learning will help us find any hidden patterns or intrinsic structures in our data, hence dimensionality reduction if allowed. The supervised learning will allow us to build classifiers that apply different algorithms(SVC, binary trees..) to predict the state of each cell based on the given data.
