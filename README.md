# neural-network-challenge-2

This project is part of an AI Bootcamp assignment that demonstrates the use of a branching neural network to predict two outcomes from HR data:
	1.	Employee Attrition (Yes/No)
	2.	Department (multi-class)

The model was built using TensorFlow/Keras and trained on real-world-like employee data with features such as age, salary, job satisfaction, and more.

Objectives
	•	Apply data preprocessing techniques (encoding, scaling, train/test split)
	•	Use OneHotEncoder and StandardScaler to prepare inputs
	•	Build a neural network with shared layers and two separate output branches
	•	Train, evaluate, and interpret model results
	•	Understand when and why metrics like accuracy might be insufficient

⸻

Technologies Used
	•	Python
	•	pandas / numpy
	•	scikit-learn
	•	TensorFlow / Keras
	•	Google Colab

⸻

Model Architecture
	•	Input layer with n features (varies by selected columns)
	•	Shared Layers:
	•	Dense(64) + ReLU
	•	Dense(32) + ReLU
	•	Branch 1 — Department:
	•	Dense(16) + ReLU → Dense(3) + Softmax
	•	Branch 2 — Attrition:
	•	Dense(16) + ReLU → Dense(2) + Softmax

    Files
	•	attrition.ipynb: Main Jupyter Notebook with full code and output
	•	README.md: This file

Next Steps for Improvement
	•	Add dropout or regularization to reduce overfitting
	•	Tune hyperparameters (epochs, batch size, learning rate)
	•	Try more advanced architectures or optimizers
	•	Track additional metrics like precision, recall, or F1-score

Liam Sloan
AI Bootcamp Student
Completed as part of Neural Network Challenge 2