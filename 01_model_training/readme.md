Folder Structure
 


Details of directories:

Packages: Root folder containing the package
Regression_model: Name of the package

Datasets:
•	Test.csv and train.csv – Kaggle datasets on Housing price predictions downloaded from https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data

Trained_model: place for saving the models in .pkl file

Files:

Pipeline.py : Build a pipeline with all the operations
Preprocessors.py: All the fit and transform functions used in the pipeline
Train_pipeline.py: Running the model and saving the models

Requirements.txt: All the necessary packages with versions which needs to be installed
•	Pip install -r requirements.txt needs to be run


Running: 
 

Output: a new file regression_model.pkl is generated in the packages/regression_model/trained_models folder


