# Evaluate-the-performance-of-two-machine-learning-models
Develop and evaluate the performance of two machine learning models, k-Nearest Neighbors (k-NN) and Multilayer Perceptron (MLP), for spam classification. k-Nearest Neighbors (k-NN) and Multilayer Perceptron (MLP), for spam classification. The dataset consists of 4,601 email samples, where 58 numerical features represent different characteristics of emails. The k-NN classifier uses a k-value of 3 and Euclidean distance, while the MLP classifier has two hidden layers with 10 and 5 neurons respectively, and uses a logistic function as the activation function. We train the model using a pre-split training set and evaluate its accuracy, precision, recall, and F1-score using the test set. The purpose of this project is to contribute to spam detection systems and improve email security.

Functionality:

1- Loading Data: The script loads spam data from a CSV file, separating features and labels.

2- Preprocessing: Features are normalized by subtracting the mean and dividing by the standard deviation.

3- Model Training and Evaluation:

- 1-Nearest Neighbor (1-NN): It trains a 1-NN model and evaluates its performance using accuracy, precision, recall, and F1-score.

- Multi-Layer Perceptron (MLP): An MLP classifier is trained and evaluated using the same metrics.

Structure:

1- Main Function: The main() function serves as the entry point, orchestrating the loading, preprocessing, training, and evaluation processes.

2- Data Loading and Preprocessing Functions:

-  load_data(filename): Loads data from a CSV file and separates features and labels.

-  preprocess(features): Normalizes features by subtracting mean and dividing by standard deviation.

3- Model Training and Evaluation Functions:

- train_mlp_model(features, labels): Trains an MLP classifier using sklearn implementation.

- evaluate(labels, predictions): Evaluates model performance using accuracy, precision, recall, and F1-score.

4- Nearest Neighbor Class (NN):

Contains methods for initializing the model and making predictions based on the k-nearest neighbor algorithm.

5- Dependencies:

The script imports necessary libraries such as NumPy for numerical operations, CSV for file handling, and scikit-learn for machine learning functionalities.
