##The most important introductory part in Machine Learning is data preprocessing, we shall follow the following steps to preprocess our data.

#Step1: Importing the necessary dependencies
    There are two most essential buildin libraries in python which we will import everytime.
    Numpy as np - numerical python to perform mathematical computation
    Pandas as pd - used to import the data and managing it.
    
#Step2: Importing the dataset
    Most datasets are available in comma separated format (.csv). read_csv is a function in pandas that will read the csv as a data frame. We     will then separate independent and dependent variables.
    
#Step3: Handling null values.
    Most data may have missing values and need to be handled to avoid reducing the performance of Machine Learning algorithmn. There are maily     two functions; .fillna() and imputer from sklearn.preprocessing library.
    
#Step4: Encoding the Categorical Data.
    These are variables which are in labels form e.g, male or female. They cannot fit into a model so their is need to encode it to numeric       values. LabelEncoder and OneHotEncoder functions from sklearn.preprocessing library.
    
#Step5:Splitting the dataset into training and testing set.
     Models need to be trained the later measured for performance. We split the dataset into two i.e, training set - fitting the
     model,testing     set - measuring the performance of the model. We use train_test_split() from sklearn.model_selection library.
    
#Step6: Feature Scaling
    Machine Leearning algorithms oftenly used Euclidean distance between two data points in their computations. Most features vary  in             magnitudes and may pose problems. This can be done using StandardScaler or MinMaxScaler form sklearn.preprocessing library.
    
# Enjoy your data preprocessing
