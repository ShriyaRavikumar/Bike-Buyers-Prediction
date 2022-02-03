# BIKE BUYERS PREDICTION
Bike Buyers Prediction is a machine learning model which uses linear regression to predict whether the buyer is interested to buy the bike or not.
# PROJECT SUMMARY
Prediction of the bike buyers whether they are willing to buy the bike or not.
We have used certain attributes like age, marital status, gender, Income, and some other attributes. 
If he/she is going to buy the bike, further steps will be carried over. 
It can be predicted by resources given by the buyer.
# AZURE SERVICES
Microsoft Azure Machine Learning Studio is used to create, train and evaluate the machine learning model in which the dataset will be selected or imported. After uploading the dataset as CSV file, select the required blocks for the model and then connect and visualize the blocks. 
# MACHINE LEARNING MODELS in BIKE BUYERS PREDICTION
![image](https://user-images.githubusercontent.com/89641257/152337927-373b2687-7c50-47b8-8388-fc03e6cb65e0.png)
# PREDICTIVE EXPERIMENT
![image](https://user-images.githubusercontent.com/89641257/152339255-4ba4949f-776b-49cf-b6dc-6bfdfc5310a3.png)
# DETAILED DESCRIPTION OF THE PROJECT
Create Project/Experiment and import the data set from local file system. After creating experiment, we need to drag and drop the required modules.
The following are the modules I have used in my project:
Data set: 
Data set required for experiment is added as CSV file.
Editing Metadata:
It is used to change data type of fields, etc.
Splitting data: 
Split the data for training and evaluation.
Score labels: 
Score labels provide the output . We can visualize the datasets.
Evaluate model: 
Evaluate model will give the accurate values. The model gives an accuracy of 96.9% and precision of 93.6%.
After creating these models, run the model by clicking run button which is in the bottom side. After running successfully, we can score and evaluate the model.
# DEPLOYING THE MODEL
Deploy the model by Setting up Web Service in Machine Learning Studio. If it is first time, select Update Predictive Experiment. After deployment of model, it can be used in webs.
Consumption options:
Excel 2010 or earlier
Request-Response Web App Template
