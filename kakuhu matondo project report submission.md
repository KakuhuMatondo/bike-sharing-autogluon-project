# Report: Predict Bike Sharing Demand with AutoGluon Solution
#### Kakuhu Matondo

## Initial Training
### What did you realize when you tried to submit your predictions? What changes were needed to the output of the predictor to submit your results?
TODO: My model did not have negative values so there was no need for adjustment

### What was the top ranked model that performed?
TODO: WeightedEnsemble_L3

## Exploratory data analysis and feature creation
### What did the exploratory analysis find and how did you add additional features?
TODO: Some of the features were not in the correct data type hence, they were not shown in the histogram. I added the hour column by extracting hour from the datetime column.

### How much better did your model preform after adding additional features and why do you think that is?
TODO: It performed nearly twice as better because the additional feature was in the right format allowing the model to correctly utilize it to make better predictions

## Hyper parameter tuning
### How much better did your model preform after trying different hyper parameters?
TODO: The overall score improved despite the root mean squared error increasing slightly compared to the previous addition of a parameter

### If you were given more time with this dataset, where do you think you would spend more time?
TODO: I would spend more time with the hyperparameter tuning because it gave me a bit of trouble at first.

### Create a table with the models you ran, the hyperparameters modified, and the kaggle score.

model	hpo1	hpo2	hpo3	score
0	initial	NaN	NaN	None	1.81057
1	add_features	NaN	NaN	None	0.62489
2	hpo	10.0	200.0	[10, 0.01, relu, 0.2]	0.47470

### Create a line plot showing the top model score for the three (or more) training runs during the project.

TODO: Replace the image below with your own.

https://d-rcsvnnledsop.studio.us-east-1.sagemaker.aws/jupyter/default/files/data/cd0385-project-starter/project/model_test_score.png?_xsrf=2%7C1926d420%7C82f3c94e42b865f0bd9124678e3129d5%7C1714662380


### Create a line plot showing the top kaggle score for the three (or more) prediction submissions during the project.

TODO: Replace the image below with your own.
https://d-rcsvnnledsop.studio.us-east-1.sagemaker.aws/jupyter/default/files/data/cd0385-project-starter/project/model_train_score.png?_xsrf=2%7C1926d420%7C82f3c94e42b865f0bd9124678e3129d5%7C1714662380


## Summary
TODO: This project showed how effective addition of new features and hyperparameter tuning can be in improving model performance.
