# covid-19
I have retrieved the covid 19 data set from kaggle website (link:)<br/>
The first step was the EDA(Exploratory data analysis) in this process i have used a lot the seaborn and matplotlib libraries to understand the relationship between the target and the features, then I have done some feature engineering , I have seperated the positive cases and the negative ones to understand the behaviour of my features and if they show significant difference when the patient has covid 19.<br/>
The second step was Data preprocessing, so i have removed the columns which they have more than 90% nan values and i decided to drop the nan variables in the process of data cleaning after this i have created an encoding function called 'encoded' to transform the categorical variables into numerical ones.
Finally , I moved to the modelization step , so after splitting the data set i have created a list of models then i have evaluated them baes on their learning curve also on their accuarcy , so i chose to work with the RandomForestClassifier for two main reasons :<br/>
to avoid the overfitting problem<br/>
it can be improved if we use the right hyperparametrs <br/>
The next step was the model optimization using the gridsearchcv model , to improve the model performance .<br/>
And that' it <br/>
## Thank You 
