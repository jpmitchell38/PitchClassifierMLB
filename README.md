# PitchClassifierMLB

In this project, I begin by importing a dataset using Pandas. I first drop any unnecessary columns that aren't relevant to the classification task. Next, I clean and preprocess the remaining columns, ensuring the data is in the best possible shape for the model. I then engineer additional features that help improve the classification accuracy.

The dataset is used to train a Random Forest Classifier. The model achieves an accuracy of 97.42%. To evaluate the model's performance, I generate and display a confusion matrix, providing a clear view of its predictions.

Additionally, I visualize the model's performance by plotting the accuracy for each pitch type and displaying the feature importance, helping to identify the most influential variables in the classification process.