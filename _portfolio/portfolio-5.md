---
title: "Prediction of the solubility of molecules"
excerpt: "Building of a linear regression model for predicting the solubility of molecules. <br/><img src='/images/regression_plot.png'>"
collection: portfolio
---

This is a reproduction of the work by [Delaney](https://pubs.acs.org/doi/10.1021/ci034243x).

In this project **linear regression** is applied to predict the solubility of molecules. To achieve that we use the SMILES notation of the molecules in order to obtain some molecular descriptors of interest using **rdkit**.

Specifically, the 4 molecular descriptors employed to predict the solubility (LogS) in the linear regression model are:

* cLogP: Octanol-water partition coefficient.
* MolWt: Molecular weigth.
* RB: Number of rotatable bonds.
* AP: Aromatic proportion = number of aromatic atoms / number of heavy atoms.

After building the linear regression model, the **pycaret** module is employed to compare the performance of several machine learning models at once.

The code for this project can be found [here](https://github.com/frodbej/solubility-prediction).
