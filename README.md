# Digit_Recognizer
MNIST ("Modified National Institute of Standards and Technology") is the de facto “hello world” dataset of computer vision. Since its release in 1999, this classic dataset of handwritten images has served as the basis for benchmarking classification algorithms. As new machine learning techniques emerge, MNIST remains a reliable resource for researchers and learners alike.

## Objective
Using this [Kaggle competition](https://www.kaggle.com/c/digit-recognizer/overview) to explore the various implementation options for classification algorithms and find ones that return the highest categorization accuracy.

## Data

* Dataset: [MNIST Handwritten Digits](https://www.kaggle.com/c/digit-recognizer/data)
* Data Description: handwritten digits (numbers), 10 classes (0-9).
* Dataset size: 
   * training: 37,800 images
   * Validation: 4,200 images
   * Test: 28,000 images
* Image sizes(all):
   * Height: 28 pixels
   * Width: 28 pixels
   * Total: 748 pizels
* The training data set, (train.csv), has 785 columns. The first column, called "label", is the digit that was drawn by the user. The rest of the columns contain the pixel-values of the associated image.
* The test data set, (test.csv), is the same as the training set, except that it does not contain the "label" column.
   
## Models

### [PyTorch] (https://pytorch.org/)

An open source, Python-First, deep learning platform with a focus on connecting research prototyping to production deployment.

![Chart](https://github.com/SamLingle/Digit_Recognizer/blob/master/Images/15_Epock_Chart.png)

Though the overall test yeilded a result of 97% Accuracy a 15 epoch test is showing an amount of overfitting to the test data that grows after the 12th epoch. Moving forward I will have to tweak the model to correct the issue. 

![Test](https://github.com/SamLingle/Digit_Recognizer/blob/master/Images/15_Epoch_Test.png)
