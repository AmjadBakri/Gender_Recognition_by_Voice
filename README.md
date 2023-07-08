# Gender_Recognition_by_Voice
This project aims to classify the gender of a speaker based on acoustic properties of their voice and speech.

The dataset used for this project contains pre-processed audio features extracted from voice recordings of males and females.

# implementation Details
The gender recognition model is implemented using Python and Scikit-learn. The dataset is preprocessed by scaling the features using a standard scaler, 

and the data is then split into training and testing sets. The model is trained using a 
- (SVM) linear kernel
- KNeighborsClassifier
- Logistic Regression

# Results
On the voice dataset, 

- the SVM model achieved an accuracy on test set = 95%. 
- the KNeighborsClassifier model achieved an accuracy on test set = 96%
- the Logistic Regression model achieved an accuracy on test set = 94%

This demonstrates the effectiveness of the model in classifying the gender of a speaker based on acoustic properties of their voice and speech.
