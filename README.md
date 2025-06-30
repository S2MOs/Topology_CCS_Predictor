# Topology_CCS_Predictor
Data and notebooks for "Classifying host-guest topology with ion mobility spectrometry and machine learning"

The "Under review" version of this repository has been uploaded to Zenodo @ [![DOI](https://zenodo.org/badge/956613146.svg)](https://doi.org/10.5281/zenodo.15211371)

### In this repository
- Experimental CCS data
- DFT inputs and outputs for the diamines included in the chemical space
- Jupyter notebooks for generating DFT inputs, processing and parsing the DFT data and training a regression model for predicting the CCS and topology of host-guest complexes 

### auto-qchem installation instructions

1. Install conda: https://www.anaconda.com.
2. Create and activate a Conda environment just for auto-qchem.
```
conda create --name autoqchem python=3.8 ipython

conda activate autoqchem
 ```
3. Install openbabel:
 ```
conda install -c conda-forge openbabel
 ```
4. Install auto-qchem using pip
 ```
pip install auto-qchem
 ```
