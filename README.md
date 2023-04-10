# COG-403-Final-Project

In this study, we examined the performance of three machine learning models on the Fashion-MNIST dataset: Naïve Bayes, Logistic Regression, and Support Vector Machine (SVM). The dataset comprises 70,000 grayscale images of clothing items, divided into 10 classes. 60000 images are in training dataset and 10000 images are in testing dataset. Model performance was evaluated using confusion matrices and classification reports, considering metrics such as precision, recall, and F1-score. The runtime of each model was also considered. The SVM model outperformed the other models, achieving an average accuracy of 89.66\%, followed by the Logistic Regression model with an average accuracy of 85.57\%, and the Naïve Bayes model with an average accuracy of 65.76\%. However, the SVM model also exhibited a longer run-time compared to the Naïve Bayes and Logistic Regression models. These results highlight the trade-off between model performance and computational efficiency when selecting the most suitable model for the classification task.

## Method

Our Project is divided into two main parts. In the first section, we will fit a Naïve Bayes model to the Fashion-MNIST dataset, Using this model to make predictions by generating new images from the same distribution. We will yield a confusion matrix as well as a classification report consisting of the precision, recall, F1-score for each of the 10 categories from the Fashion-MNIST dataset. Also, we will perform Naïve Bayes imputation to fill in artificially generated missing data. 

After evaluating the Naïve Bayes model, In the second section, we will perform the same evaluation process for the Logistic Regression and the Support Vector Machine (SVM) model, yielding a confusion matrix, and a classification report with the same evaluation matrix as that of Naïve Bayes. 

## Data and files

The githus include all code and data that are needed for replication.
