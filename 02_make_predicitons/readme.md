New Directories:

Note the new structure – there is a regression_model folder inside regression_model inside packages

Packages/regression_model/regression_model/Config/config.py: 
•	Config files with all the fixed variable names, features, name of train and test data, target variable
•	This is done to clean up the code and make it more readable
•	Also if something needs to be changed (say the name of the file or removing a feature), it can be done only at one place rather than going through the code
•	from regression_model.config import config


Packages/regression_model/regression_model/processing/data_management.py
•	Functions to load_dataset, save_pipeline and load_pipeline
•	Cleaning up the train_pipeline.py code
•	from regression_model.processing.data_management import ( load_dataset, save_pipeline)


Training the model 
$ python packages/regression_model/regression_model/train_pipeline.py

Make Predictions:
python packages/regression_model/regression_model/predict.py

This will not print anything. To test if the modules are working fine, Test modules have to be added (covered later)
