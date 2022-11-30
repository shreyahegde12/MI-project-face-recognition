# MI-project

Project on Face Recognition using different types on CNNs, using the lfw dataset, was pretty fun.
This was a project for course UE20CS302 on Machine Intelligence at PES, University.

Execution Steps:
1. Import all the essential libraries
2. Load the dataset from kaggle the link for this is : https://www.kaggle.com/datasets/jessicali9530/lfw-dataset
3. Pre-Processing Involves cropping out the middle part and converting to greyscale (done for one iteration of code, rest are left colored)
4. Run the model blocks and compile. It is defined as model(), multi_classifier() or resnet(), depending on the model
5. Run the model for the dataset over the number of epochs specified (this will take a while)
6. Evaluate for test data
7. Run the accuracy metrics calculations, either confusion matrix, or accuracy score, formulae in code 
8. Import random file and predict with model. 
9. All these steps could also be achieved by downloading the .ipynb file and clicking run all on a jupyter notebook environment. 
