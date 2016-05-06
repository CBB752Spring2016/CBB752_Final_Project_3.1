# CBB752_Final_Project_3.1
A tool that calculates co-expressed gene network from GCT file of gene expressions.
# Usage notes for Python Code: 

Usage:      python GCT_to_net.py -i (input .txt file in GCT format) -p (p value in [0,1]) -o (output .csv file name)

Example:    ```python GCT_to_net.py -i input.gct -p 0.01 -o output.csv```

Note:       

              Input: GCT file, which is a text file with 1st row = column titles
              Columns: Name, Description, Experiment1, Experiment 2, exp3, exp4 ...
              One row per gene
              Output: a csv. of pairwise gene interactions, Pearson R values, p-values and Bonferroni-adjusted p-values, comma-delimited
              example.gct: constructed from all_aml_train.gct, remove 2 header lines, keep first 100 genes

