# Machine Learning model to classify prices of properties in Colombia

Using data from different properties in Colombia I implement a classification machine learning model to predict wether a property in Colombia is expensive based on the price mean. If the price is less than the mean, the property is categorized as cheap. Otherwise it's categorized as expensive.


## Data Cleaning and Feature Engineering

Before applying the model the data should be preprocessed:
- All prices must be set to the same currency.
- Latitudes and longitudes should correspond to a place in Colombia.
- Missing data handling: ***Natural Language Processing*** to extract information from another column.
- Selection of relevant features.


## Model Building

I implement a ***K-Nearest Neighbors*** algorithm to train the model and make the predictions.
I split the data into test and training sets and calculate the accuracy for different number of neighbors in order to find an optimal number.


## Model Performance

Once the model is built, I use it to predict the test set obtaining a ***recall*** of 0.61 and an ***accuracy*** of	0.86.
