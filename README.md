# predict_hiv_progression
Jupyter notebook for the Kaggle "Predict HIV Progression" competition. This is a practice project to demonstrate my python and machine learning skills.

In this project I build a model to predict a patient's short term disease progression based on the nucleotide sequences of two enzymes and 2 other scalar patient parameters. We use the dataset that was used in an old Kaggle competition located here: https://www.kaggle.com/c/hivprogression/data

The solution to the competition is present on the site, but I did not examine the solution nor any of the submitted notebooks. I developed the solution presented here independently.

I first do some prelimary exploration of the data. This is followed by a number of feature engineering steps that involve transformations of the data.

I develop a model and experiment with various parameters. I evaluate the parameter combinations using hold out validation with the StratifiedKFold class using only the training set. For each best combination we then run predictions on the test set to get an accuracy score.

The code is organized into a series of classes and functions that can be used to perform the various data transformation and model testing tasks required.
