---
# **PyCaret for Machine Learning**
- It is a bundle of many Machine Learning algorithms.
- Only three lines of code is required to compare 20 ML models.
- Pycaret is available for:
    - Classification
    - Regression
    - Clustering

---
### **Self Learning Resource**
Tutorial on Pycaret for Regression, Classification and Clustering <a href="https://pycaret.readthedocs.io/en/latest/tutorials.html"> Click Here</a> 


---
### **In this tutorial we will learn:**
- Getting Data: How to import data from PyCaret repository
- Setting up Environment: How to setup an experiment in PyCaret and get started with building regression/classfication/clustering models
- Create Model: How to create a model, perform cross validation and evaluate regression metrics
- Tune Model: How to automatically tune the hyperparameters of a regression model
- Plot Model: How to analyze model performance using various plots
- Finalize Model: How to finalize the best model at the end of the experiment
- Predict Model: How to make prediction on new / unseen data
- Save / Load Model: How to save / load a model for future use

---
### **Three line of code for model comparison for "Insurance" dataset**
```
from pycaret.datasets import get_data
from pycaret.regression import *

insuranceDataSet = get_data("insurance")
s = setup(data = insuranceDataSet, target='charges', silent=True)
cm = compare_models()
```
---
### **Outcome for Regression**
![image](https://user-images.githubusercontent.com/7460892/130013128-d5c349bd-5aca-4eea-b9bc-81cf09e5d1ed.png)

---
### **Outcome for Classification**
![image](https://user-images.githubusercontent.com/7460892/131240694-4ef0cbc8-d76f-416c-b6cf-b739be16d308.png)

---
### **Outcome for Clustering**
![image](https://user-images.githubusercontent.com/7460892/131206252-10a4e5ec-ec8f-4017-8617-ae46d47dcdcf.png)


