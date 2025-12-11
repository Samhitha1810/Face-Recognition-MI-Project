# Face-Recognition-MI-Project
MI-project
Project on Face Recognition using different types on CNNs, using the lfw dataset, was pretty fun. This was a project for course UE20CS302 on Machine Intelligence at PES, University.

Execution Steps:

Import all the essential libraries
Load the dataset from kaggle the link for this is : https://www.kaggle.com/datasets/jessicali9530/lfw-dataset
Pre-Processing Involves cropping out the middle part and converting to greyscale (done for one iteration of code, rest are left colored)
Run the model blocks and compile. It is defined as model(), multi_classifier() or resnet(), depending on the model
Run the model for the dataset over the number of epochs specified (this will take a while)
Evaluate for test data
Run the accuracy metrics calculations, either confusion matrix, or accuracy score, formulae in code
Import random file and predict with model.
All these steps could also be achieved by downloading the .ipynb file and clicking run all on a jupyter notebook environment.
