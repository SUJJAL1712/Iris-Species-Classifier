Iris Species Classifier
The Iris Species Classifier is a machine learning project that uses TensorFlow to train a deep neural network (DNN) model for classifying Iris flower species based on their sepal and petal measurements.

Dataset
The project utilizes the Iris dataset, which includes measurements for three different Iris species: Setosa, Versicolor, and Virginica. The dataset is divided into a training set and a test set.

Model Architecture
The classifier is built using TensorFlow's Estimator API and employs a DNNClassifier model with two hidden layers (30 and 10 units respectively). The input features consist of sepal length, sepal width, petal length, and petal width.

Training and Evaluation
The model is trained on the training dataset, with the training process including shuffling and repetition of the data. After training, the model is evaluated on the test dataset to measure its accuracy.

Making Predictions
To make predictions, users can input numeric values for sepal and petal measurements interactively. The trained model then predicts the most likely Iris species based on the provided input.

Benefits and Applications
The Iris Species Classifier project demonstrates the application of machine learning algorithms for species recognition tasks. It showcases the power of deep neural networks and TensorFlow in accurately classifying Iris flower species based on their physical characteristics. This project can be utilized in various domains, including botany, horticulture, and ecological research.

Requirements
The project requires TensorFlow and pandas libraries to be installed. The necessary CSV files containing the Iris dataset will be automatically downloaded from the TensorFlow website.
