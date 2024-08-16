# machine-learning-project
import neccessary dependencies.
 Now load the data based on its extension i.e read_*. * represents the type of file like pdf,csv,html,word,excel.
 Now identify the dependent variables(y) and independent variable(x).
 Split the data into x_train,X_test,y_train,y_test.
 Select the necessary model based on the data which gives better performance.
 suppose if it is continous data then select linear model(regression model) else if it is categorical data then go to logistic regression(classification model).
 Then after train the model using fit() method using x_train and y_test.
 If the data having a large range of values then standardize the data so it reduce the complexity of the model using fit_transfrom() (import StandardScaler class)N now predict the using test data i.e x_test .
 Then evaluate the performance of the model.
 If the model is regression model then use the metrics sucha as accuracy_score() ,if it is classification problem then use metrics like prcision,recall,f1-score,accuracy etc.
 The model performs well if it has value near to 1(like 0.9777).
 If it is near to 0,the performance of the model is bad.
