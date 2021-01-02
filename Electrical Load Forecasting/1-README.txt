I have done this project in my 3rd Year 2nd Sem.
Actually, we were a group of 3 students doing this project.
We had done : Data Collection, Data Refining, Data Prediction, Data Visualization
In this project, we gathered electricity month bills data of timespan 2011-2020.
We had two goals in this project. 
1) To predict the future bill amounts using Linear Regression.
2) To predict the load (in KVA) using Recurrent Neural Network.
We studied many things in this Project.
A day is divided into 4 timezones : A zone, B zone, C zone, D zone (you can see the zone files seperately).
There are 4 pre-trained Linear Regression models for each zones.
And using RNN, there is a pre-trained model for Demand KVA(or Load).
The rest of the csv files are data sets which we taken from the bills and used to train the Respective models.
A 70-30 train-test data is used.
Output plots and electricity bills can be seen by executing respective files.
The predicted data is for timespan 2018-2023.
The Accuracy is about 80%.
