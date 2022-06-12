Credit Risk Analysis Report: 

The purpose of this analysis is to create a predictive model to identify healthy and high-risk loans based on a set of feature data. A standard regression model is used to train and test the model using the original data that is imbalanced, which could create biases in the outcome.  We will manipulate the dataset to balance the data for more accurate results.  

Model_1: 
> Balanced accuracy -  0.9348689535044776 ; 
> precision -  0.93
> recall -  0.95

Model_2: 
> Balanced accuracy -  0.9951689767124503
> precision - 1.0 
> recall - 1.0   

The resampled data using the overfitting method has improved the predictability of the model, but not by much.  I recommend using the original dataset to train and test the model. The predictability of the model is good enough using the original data while preserving the integrity of the universe without overestimating the frequency of the minority class which could impact the reliability of the model overtime.  