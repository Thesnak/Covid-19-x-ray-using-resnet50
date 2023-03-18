# Covid-19-x-ray-using-resnet50


This repository contains a Jupyter notebook implementing a Convolutional Neural Network (CNN) based on ResNet50 architecture to classify CT scans as either positive or negative for SARS-CoV-2 (COVID-19) infection. The notebook is trained and tested on a public dataset of real patients CT scans collected from hospitals in Sao Paulo, Brazil. The dataset is available at [Kaggle](https://www.kaggle.com/plameneduardo/sarscov2-ctscan-dataset) and contains 1252 positive and 1230 negative scans.


The notebook achieves an accuracy of 96% on the test set and can be used as a starting point for further research and development of AI methods to identify SARS-CoV-2 infection from CT scans.
Upvote the notebool on kaggle [Covid-19 X-ray using resnet50 | Accuracy 96.26%](https://www.kaggle.com/code/thesnak/covid-19-x-ray-using-resnet50-accuracy-96-26) .


# Dependencies
The notebook is written in Python 3 and requires the following dependencies:

tensorflow
numpy
pandas
matplotlib
scikit-learn
seaborn
opencv-python
These dependencies can be installed using pip or conda package managers. The versions used in the development of the notebook are listed in the requirements.txt file.

# Usage
To run the notebook, clone or download the repository and open the Covid-19-x-ray-using-resnet50.ipynb file in a Jupyter notebook environment. The notebook is designed to be self-contained and includes code for data preprocessing, model training, evaluation, and visualization.

The notebook assumes that the dataset is stored in the data folder, which should contain two subfolders positive and negative with the corresponding CT scan images. The dataset can be downloaded from Kaggle using the link provided above.

# Acknowledgments
The notebook is based on the ResNet50 architecture and training techniques developed by He et al. (2016) and Simonyan and Zisserman (2015), respectively.

The dataset used in this notebook was collected by Soares et al. (2020) and is described in their paper ["SARS-CoV-2 CT-scan dataset: A large dataset of real patients CT scans for SARS-CoV-2 identification"](https://www.medrxiv.org/content/10.1101/2020.04.24.20078584v2). We thank the authors for making this dataset publicly available and encourage researchers to cite their work when using this dataset.



