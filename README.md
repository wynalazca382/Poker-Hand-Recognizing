
# Poker Hand Classification

This repository contains code for a machine learning model that predicts the classification of poker hands using TensorFlow and scikit-learn libraries in Python.


## Usage

1.Clone Repository:
```bash
git clone https://github.com/your_username/your_repository.git

```
2.Install Dependencies:
```bash
pip install pandas numpy scikit-learn tensorflow

```
3. Run the Code:
Ensure you have the required CSV files (poker-hand-testing.csv and poker-hand-training.csv) in the same directory as the code.

Execute the main script.
## Description

The code consists of the following components:

* Data Preprocessing: The input CSV files are loaded using pandas. The features and target variables are extracted and preprocessed. Suits are one-hot encoded, ranks are scaled, and the data is split into training and validation sets.

* Model Architecture: A Convolutional Neural Network (CNN) model is defined using TensorFlow's Keras API. The model consists of convolutional and pooling layers followed by densely connected layers with dropout regularization.

* Model Training: The defined model is compiled and trained using the training data. Early stopping is implemented to prevent overfitting.

* Model Evaluation: The trained model is evaluated on the test data to compute loss and accuracy.

* Model Saving and Loading: The trained model is saved in Hierarchical Data Format (HDF5) file format. A function is provided to load the saved model for making predictions.

* Prediction: A function is defined to predict the classification of poker hands based on input card data.

## Example Usage

An example script is provided to demonstrate how to use the trained model to predict poker hands based on input cards.
## Files

* poker-hand-testing.csv: Test data file containing poker hand samples.

* poker-hand-training.csv: Training data file containing poker hand samples.

* poker_hand_model.h5: Saved trained model file.

* predict_poker_hand.py: Example script to predict poker hands based on input cards.
## Authors

- [@wynalazca382](https://github.com/wynalazca382) Łukasz Gajewski 20179


## License

 "THE BEERWARE LICENSE" (Revision 42):
 wynalazca382 wrote this code. As long as you retain this 
 notice, you can do whatever you want with this stuff. If we
 meet someday, and you think this stuff is worth it, you can
 buy me a beer in return.



## Acknowledgments

The dataset used in this project is from the UCI Machine Learning Repository.

Special thanks to the contributors of TensorFlow, scikit-learn, and pandas libraries.
