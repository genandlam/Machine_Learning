
## Allstate Claim Severity

In a serious car accident, it can be a hassle to go through insurance papers with your insurance agent. Thus, Allstate is developing an algorithm to predict claim severity accurately. This is to ensure Allstate customer can have less of a hassle when meeting an accident. The purpose of this project is to predict the claim severity and evaluate the accuracy and compare with the leaderboard in Kaggle competition.
Getting Started
The following instruction will show how the codes can be run so as to replicate the results for our kaggle competition.
Setup
We have used several jupyter notebooks (.ipynb file extension) for this competition on the Google colaboratory so as to make use of its free GPU and computation power. Google Colaboratory also provide 12GB RAM in case we run out of RAM in our 8GB local machine. Using Google Colaboratory also allows the team to easily communicate our ideas and share codes in real time.

The setup to run the codes is simply to import all the .ipynb files to Google Colaboratory. Each file can be run in any order because the intermediate files are in Google drive and the script will load those files and read them.
 
## Notebooks
The following are the information of each of the .ipynb files

## 1_feature_engineering.ipynb
-	Read in raw data, encode the variables and output processed data
## 2_xgboost.ipynb
-	Train xgboost model with (manually) selected hyperparamaters with seed=0 and predict the loss
## 3_xgboost.ipynb
-	Train xgboost model with (manually) selected hyperparamaters with seed=1 and predict the loss
## 4_xgboost.ipynb
-	Train xgboost model with (manually) selected hyperparamaters with seed=2 and predict the loss
## 5_second_level_xgboost.ipynb
-	Train a second-level xgboost on data concatenated with outputs from previous 3 models and predict the loss
## 11_neural_network.ipynb
-	Train a neural network (9 layers) and predict the loss
## 12_neural_network.ipynb
-	Train a neural network (11 layers) and predict the loss
## 13_second_level_xgboost.ipynb
-	Train a second level xgboost on data concatenated with outputs from previous 5 models and predict the loss

