Penguin Classifier: Machine Learning from Scratch
Description
This project is a hands-on implementation of the Perceptron algorithm for binary classification. It is inspired by the educational content from Chapter 2 of the book "Machine Learning with PyTorch and Scikit-Learn" by Sebastian Raschka.

While the original examples in the book utilize the Iris dataset, I have adapted and applied these concepts to the Palmer Penguins dataset. This project serves as a foundational exercise to understand how artificial neurons learn through weight updates and how to visualize linear decision boundaries.

Key Features
Perceptron from Scratch: A Python implementation of the Perceptron algorithm using NumPy, following Object-Oriented Programming (OOP) principles.

Data Adaptation: Successfully transitioned the book's logic from the Iris dataset to the Palmer Penguins dataset, including data cleaning and feature selection.

Binary Classification: Focused on classifying two species: Adelie and Gentoo.

Visual Analytics:

Scatter plots for feature exploration (e.g., Flipper Length vs. Body Mass).

Plotting the misclassification error per epoch to monitor convergence.

Decision Boundary Visualization: A custom visualization to show how the model separates the two species in a 2D feature space.

Dataset
The project uses the Palmer Penguins dataset, a popular alternative to the Iris dataset. It includes measurements for penguin species found in the Palmer Archipelago, Antarctica.

Note: The dataset was preprocessed to remove missing values and filtered for binary classification.

Requirements
To run the notebook, you will need the following Python libraries:

numpy

pandas

matplotlib

How to Run
Clone this repository:

Bash
git clone https://github.com/your-username/penguin-classifier.git
Ensure palmer-penguins.csv is in the same directory as the notebook.

Launch Jupyter Notebook or open the file in Google Colab:

Bash
jupyter notebook penguin_classifier.ipynb
References
Raschka, S., Liu, Y., & Mirjalili, V. (2022). Machine Learning with PyTorch and Scikit-Learn. Packt Publishing.
