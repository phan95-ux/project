# covid19_xray_cnn
 
Convolutional Neural Network for the Classification of COVID-19 X-Rays

This repository contains the following files and folders:

FOLDER:
- raw_data
   --> contains the raw dataset.
- model_data
  --> contains the filtered dataset.
 - my_model 
  --> contains the developed CNN-model without parameter optimization.
- my_best_model 
  --> contains the developed CNN-model with parameter optimization.
  
FILES:
- CNN_Covid_classification_hyperparameter_tuning.ipynb 
  --> Script to tune the parameters of CNN-model.
- CNN_Covid_classification_simple_model.ipynb
  --> Script to develop and train CNN-model with initial parameters.
- confusion_matrix_generate.ipynb
  --> function to plot confusion matrix.
- data_extraction.ipynb 
  --> script to extract relevant data from the raw_data folder.
- generate_data_cnn.ipynb 
  --> script to generate data for training/testing from the model_data folder.
