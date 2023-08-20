# HandWritingRecognition
A Machine Learning project for building the simple model of cnn architecuture. Here we provide the input dimension as the number of columns in the dataset. The dataset coontains i.e., " mnist_784 " is a multi class classification contains the digit ranges from 0-9. The no of records in the dataset are 7000. 
These are the steps which I have used for this project:

Step 1: Import the libraries such as keras, tensorflow, pandas, numpy, matplotlib etc..

Step 2: Load the dataset using the sklearn.dataset having method fetch_openml() and the name of the dataset is " mnist_784 ". Downlaod through the jupyter prompt line.

Step 3: Choose the dependent and independent variables where we assign the target variable.

Step 4: Visualization of the digit using the matplotlib library where we use imshow() method.

Step 5: Splitting the data into test and train set.

Step 6: Building the cnn model

  Step 6.1: Initialising the cnn model.
  
  Step 6.2: Adding the dense layer.
  
  Step 6.3: Adding a output layer. Since it is a multi-class classification we activation function as softmax.
  
  Step 6.4: Compiling the cnn model.
  
  Step 6.5: Training the cnn model on the training set and evaluating it on the test set.

Step 7: Identifying the digit based on the probability i.e., which has the highest while comparing with the other probabilities it will belong to the corresponding class.
