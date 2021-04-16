# rapidEELS

RapidEELS is a Autoencoder-Classifier Framework for denoising low SNR electron energy loss spectroscopy (EELS) spectra and classifying their oxidation state.

This code supplements the paper:    
**RapidEELS: Machine Learning for Denoising and Classification in Rapid Acquisition Electron Energy Loss Spectroscopy.**  
    *by Cassandra Pate (Johns Hopkins University, Department of Materials Science & Engineering);   
    James Hart (Yale University, Department of Mechanical Engineering & Materials Science);   
    Mitra Taheri (Johns Hopkins University, Department of Materials Science & Engineering)*  

## About 
This work was done as part of a study using SrFeO3-δ(δrepresents the oxygendeficiency) thin films, as a starting point for rapid identification of real-time EELS data. The films undergo an oxidation state changes from nominally SrFeO3(Fe4+) to SrFeO2.5(Fe3+) as target metrics to benchmark our algorithms.


## Descriptions
- [EELS_model_training_GH.ipynb](https://github.com/patecm/rapidEELS/blob/main/EELS_model_training_GH.ipynb)
    - Notebook to train your own AEC and Classifier on binary state EELS data. 
    - DM4 files should end with 'a' if annealad (e.g. EELS thick 1_1a.dm4) for binary oxidation state data to be created correctly
-
 

### Usage

## Requirements
- Requires the open source Python library [HyperSpy](https://hyperspy.org/) to process DM4 data. 
- lmfit 1.0.2 (if training data has not been previously PowerLaw background subtracted)
- Tensorflow version 2.4.1
- Python 3.7.10
