New Files:

MANIFEST.in: provides detail on what files to keep in the package

Setup.py: Other details on the model, meta-data, requirements, license information and other details

Packages/regression_model/regression_model/requirements.txt: This is another requirements.txt file inside the package. This needs to be provided. There are two additional packages that needs to be installed for packaging, so make sure you run $pip install -r packages/regression_model/regression_model/requirements.txt

# production requirements
numpy==1.15.4
scikit-learn==0.20.2
pandas==0.23.4

# packaging
setuptools==40.6.3
wheel==0.32.3

# testing requirements
pytest>=4.6.6,<5.0.0



Run
$ python packages/regression_model/setup.py sdist bdist_wheel
This will generate distribution file - one tar.gz file and another wheel


Install Package
$ pip install -e packages/regression_model/

Use Package
$ python
>>>import regression_model
