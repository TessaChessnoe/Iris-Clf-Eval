\*\*\\\[Update\\]\*\* Originally created as part of FGCU's Data Mining course in Fall 2024.

I have updated this notebook to include the following:

1. Value distribution analysis for each feature of the 3 species
2. 5-fold cross validation to counteract sampling bias
3. Max-depth decision tree classification evaluation





This notebook compares the classification performance of 2 models: 3-NN and a max-depth decision tree on the Fisher Iris dataset \[1936] \[Link to Dataset](https://archive.ics.uci.edu/dataset/53/iris). The graphs and confusion matrices included in the repository were created using random\_state=0, and thus results should replicable to anyone testing the notebook. 

