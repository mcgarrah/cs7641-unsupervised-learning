README

########################################################################################################################################################
DATASETS

Dataset from Assignment 1 (Dataset 1)

Source: 
Name: Covertype Data Set
Link: https://archive.ics.uci.edu/ml/datasets/Covertype
Number of instances: 581012 (Only small subset of random instances are used to perform the experiments)

Dataset 2

Source: UCI Machine learning repository
Name: Breast Cancer Wisconsin (Diagnostic) Data
Link: https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)
Number of instances: 559

########################################################################################################################################################

Instructions to run the code:

1. Install Anaconda 3 and Jupyter Notebook
2. Open Notebook files and review

Or

View on Github found in https://github.com/mcgarrah/cs7641-unsupervised-learning

Note: Code contains lines with reads the dataset so the dataset should be in the same location where the code is present.
      Few files will generate and save data and plotting files will take data and plot the graphs.

########################################################################################################################################################

Folder contains:

README.txt

#Analysis
jmcgarrah6-analysis.pdf (Analysis)

#datasets
covtype.data (Covertype data)
cancerless_drive_diagnosis.csv (cancer data)


#Code 

Exp1
####
cluster_covtype.ipynb   (Experiment 1 clusters for Covtype dataset)
cluster_func.py      (General functions to create clusters)
cluster_cancer.ipynb    (Experiment 1 clusters for cancer dataset)

Exp2
####
dim_reduce_cluster_pca_cancer.ipynb (PCA cancer)
dim_reduce_cluster_fa_cancer.ipynb (FA cancer)            
dim_reduce_cluster_rp_cancer.ipynb (RP cancer)
dim_reduce_cluster_ica_cancer.ipynb (ICA cancer)
cluster_func.py                     (General cluster functions required for this experiment as well)
dim_reduce_cluster_rp_covtype.ipynb  (RP covtype)                             
dim_reduce_cluster_fa_covtype.ipynb   (FA covtype)
dim_reduce_cluster_ica_covtype.ipynb  (ICA covtype)
dim_reduce_cluster_pca_covtype.ipynb (PCA covtype)

#For plotting Exp2
###################
plot_dimensional_cluster.ipynb (Above exp 2 files generates data, this takes the data and plots)

Exp3
####
re_neural_network_covtype.ipynb
re_neural_network_cancer.ipynb


