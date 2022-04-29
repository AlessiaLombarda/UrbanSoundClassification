
# UrbanSound8k Classification 

This project was developed for the *Statistical Methods for Machine Learning* course by Alessia Lombarda and Andrea Valota.
The goal of this project is to create different architectures that perform classification on the [*UrbanSound8k dataset*](https://urbansounddataset.weebly.com/urbansound8k.html).  
The specifics of each architectures and the methodologies of experimentation are better exposed in the [Report](https://github.com/AlessiaLombarda/UrbanSoundClassification/blob/main/Report/SMFML_Report.pdf).

## Requirements

All the used code and libraries are included in the notebooks and dowloadable through Colab.  

**Librosa** is used for preprocessing and feature extraction.  
**Tensorflow2** is used to build and manage the models.  

The **UrbanSoud8k** dataset can be obtained [here](https://urbansounddataset.weebly.com/download-urbansound8k.html).

## Project structure

### - Feature dataset

This folder contains a csv file with the feature dataset extracted from *UrbanSound8k*. More information about the content of this file can be found in Section 1 of the report.

### - Notebooks

This folder contains the Google Colab notebooks used to perform all the computation.   

The *UrbanSound8k_preprocessing* file contains the preprocessing of tha dataset, various examples of the features considered to train the different models and feature selection methods.  

In the *Models* notebook are illustrated the different MLP and CNN architectures, implemented using Tensorflow2, used to address the classification task. More information about the Models can be found in Section 3 of the report. 

### - Results

This folder contains the csv files with the results of the experiments performed on the different models. An analysis and explanation of the results can be found in the report.

### - Report

This folder contains the PDF report and all the latex files and images used to create it.



