# Census-Income-Prediction
Datasets:
-----------------------------------------------
1. The data set is being attached in zip file and can be extracted to same directory as the project file
2. Data obtained from:   https://archive.ics.uci.edu/ml/datasets/census+income
	- adult.data for training the model.
	- adult.test for validating and testing the model. (crossvalidated)
3. If data is downloaded from above link, we need to add title rows to data in excel, else if the provided data is used we need not make any changes.


Requirements:
-----------------------------------------------
1. Jupyter Notebook
2. Python 3.6 ( Preferably Anaconda env)
3. Libraries:
	- Numpy
	- Pandas
	- Scikit Learn
	- matplotlib
	- seaborn
	- statistics


Execution:
--------------------------------------------------
1. Extract the zip  file into a single directory. (Make sure dataset and ipynb file are in same directory or might have to reset the path directory)
2. Make sure all libraries are imported.
3. Execute the cells inorder.
4. The project is developed in 2 methods
	-using label encoder
	-using one hot encoding with pd.get_dummies
5. The following are the output metrics:
	- Model Accuracy: Accuracy of the model on training dataset ("adult.csv")
	- Validation Set Accuracy: Accuracy of model on a cross validated testing dataset ("adult.test.csv")

***NOTE***
There might be a small variation in model accuracy each time it is run from outputs mentioned in report because of the randomness of train_test_split()
