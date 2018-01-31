# Mushroom-Classification

CLassification of mushrooms into two categories: Edible and Non-Edible

This data is taken from kaggle.

### Data PreProcessing

    Loading Data and checking for missing values.
    
    Converting the categorical values into encoded values using Label Encoder
    
    Standardizing the data using Standard Sclaer
    
    Applying Principal Component analysis for better dimensionality reduction of data.
    
    Visualising data using matplotlib and seaborn libraries.
    
### Modelling
    
    Using popular machine learning algorithms
    
    Default Logisitic Regression
      
      Score = 0.957
      
      Plotting Reciever Optimistic Curve(ROC) and Confusion matrix.
      
    Logistic Regression(Tuned model)
      
      Using Grid Search over posibble values of C and getting the best parameter value for our model.
      
      Score = 0.97
   
    Gaussian Naive Bayes 
      
      Score = 0.93
      
      Plotting ROC for better visualisation of results and confusion matrix for knowing the correct number of predictions.
      
    
     SVM(Tuned model)
      
      Score : 1.0
     
     Random Forest
      Score  : 1.0
  
  
Thus Random Forest and SVM give the best results for classification on this data.

For complete analaysis please see my ipyhton notebook 'Classification of mushrooms'.

