# Farm Boundary Extraction using Earth Observation Data and Image Segmentation

This repository is dedicated to the results of an internship project at NASA SERVIR 2023.
The aim of the project is to develop a deep-learning based model for farm boundary extraction using Sentinel-2 Images.


The implementation is split into three different Jupyter notebooks. 

It is split into three different notebooks. All code files are well documented.


**Data_Collection_GEE.ipynb**

This notebook is desinged to collect and download Sentinel-2 images on Google Earth Engine (GEE) using geemap python library. This notebook designed to be runned in Google Colab.


**NL_FarmBoundaryExtraction_UNet.ipynb**

This notebook is designed to train U-Net model for farm boundary extraction on the Netherlands dataset. Data loading and pre-processing, U-Net model definition, model training, model prediction and testing are included and well documented in this notebook. The model weight will be saved as .h5 file and can be used as a pre-trained weight to train U-Net model for the other study area.

The data set is available online: [doi.org/10.17026/dans-za6-m8t7](https://doi.org/10.17026/dans-za6-m8t7)


**Kenya_FarmBoundaryExtraction_UNet.ipynb**

This notebook is designed to train U-Net model for farm boundary extraction on the Kenya dataset. Due to limited data for Kenya, this model used pre-trained weight from NL U-Net model. 



## UNet Model

The fully convolutional networks (FCN) applied in this project is based on [U-Net](https://arxiv.org/pdf/1505.04597.pdf). 



## Contributors

* Ali Surojaya
* Biplov Bhandari (SERVIR Mentor)
* Aparna R. Phalke (SERVIR Mentor)
* Claudio Persello (ITC Supervisor)



## Acknowledgement

This project is a modification based on [Field Boundary Delineation Project](https://github.com/resingm/field-boundary-delineation).


