# Predictive-Maintenance

The detection of failures and flaw in manufacturing tools and equipment has demonstrated, to be a challenge to scale its assurance and execution. Deflation in manufacturing tools and equipment takes place owing to many elements, generally tool wear, strain, heat failure and power failure. The aim of this study is to determine the machine failure by construction of classifier model on predictive maintenance dataset. The class imbalance data compromise the performance of the constructed model and this is addressed by assessing the oversampling methods with Multi-Task Learning (MTL)architecture. Also, to gauge the performance of auxiliary learning towards the advancement of the primary task learning.

Dataset Description- https://archive.ics.uci.edu/ml/datasets/AI4I+2020+Predictive+Maintenance+Dataset

Target variable Machine failure indicates machine failure at particular datapoint for any of following failure mode are true. Five independent failure modes of machine failure are as follow:

- tool wear failure (TWF)
- heat dissipation failure (HDF)
- power failure (PWF)
- overstrain failure (OSF)
- random failure (RNF)
If at least one of the above failure modes is true, the process fails and the 'machine failure' label is set to 1. It is therefore not transparent to the machine learning method, which of the failure modes has caused the process to fail. Considering timeline and resources of study, study is limited to machine failure only. Eliminating five failure mode from dataframe.
