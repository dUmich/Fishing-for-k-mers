# Fishing-for-k-mers

Takes k-mer merger output as input. 
Conducts a fisher exact test for every k-mer and outputs a two column tsv with one column as k-mers and the second column as each k-mers
respective p-value. Only returns significant p-values at a cutoff of .01 and according to a bonferroni correction.
