Drug Classification Model
This project is a simple machine-learning model to predict drug types based on patient characteristics. The model uses a feed-forward neural network implemented with TensorFlow and Keras and achieves high accuracy on the dataset, making it a practical example for beginners in neural networks.

Dataset
The dataset, drug200.csv, contains information about various drugs prescribed to patients based on certain characteristics:

Age: The age of the patient.
Sex: Gender of the patient (M for male, F for female).
BP: Blood pressure levels (categorized as LOW, NORMAL, or HIGH).
Cholesterol: Cholesterol levels (NORMAL or HIGH).
Na_to_K: Sodium-to-potassium ratio in the blood.
Drug: Target variable, indicating the type of drug prescribed. This is a categorical variable with 5 possible classes, which are encoded as integers for model training.
Model
The model is a feed-forward neural network with three layers:

Input Layer: A dense layer with 32 neurons and ReLU activation.
Hidden Layer: A dense layer with 16 neurons and ReLU activation.
Output Layer: A dense layer with 5 neurons and softmax activation, which outputs a probability distribution for the 5 drug types.
