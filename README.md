# brain-tumor-classification using deep learning

This project uses deep learning to classify brain MRI images into two categories: 
healthy and tumor. It implements transfer learning for improved accuracy.

**Dataset**
[link text]https://www.kaggle.com/datasets/hamzahabib47/brain-cancer-detection-mri-images/data

# Setting up the project

1. Download the dataset from the link above.
2. Clone this repository and make sure the code and dataset are in the same folder.
3. Create a new environment and install the required libraries (matplotlib, Keras, TensorFlow)

## Results

Accuracy when the model was built from scratch: 91%
Accuracy when transfer learning was used: 97%

**Notes**

In the code file, all the code that has been commented (appearing in red) is the code which was used to
build the classification model from scratch. It was commented so that a similar transfer learning code could
be tested. The code currently uses transfer learning but if you want to run the code with the initial model, 
then uncomment it and comment out the transfer learning one.

In both cases, dividing the data and image preprocessing remains the same.

## License
This project is licensed under the MIT License.
