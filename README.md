# ASL_Model_Selection
A Clear documentation on selecting the best model for ASL prediction

##How to access data?

We have used data from Kaggle, here is the link to the dataset:
https://www.kaggle.com/datasets/grassknoted/asl-alphabet

##Setup for running the code notebook:
Download the data from above link. We have created a folder structure and accessed the data with path in the code with jupyter notebook.
Create same folder structure to avoid code change, once setup is ready code file will run without any change with jupyter notebook. 
Here is the folder structure:

![Picture1](https://github.com/vimaleshraja/ASL_Model_Selection/assets/54736154/9ddda780-3ab6-4727-8e54-d5902cbfefe9)

To avoid the huge data volume, and improve computational performance, we have only accessed data from ‘asl_alphabet_train’ folder and performed train, validation and test split on this data with Stratify sampling from each class.

