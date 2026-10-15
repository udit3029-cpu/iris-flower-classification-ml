 Iris Flower Classification

A beginner-friendly machine learning project that predicts the species of an iris flower from four measurements using a Random Forest classifier.

## Flower classes
- Setosa
- Versicolor
- Virginica

## Input features
The model uses these measurements (in centimetres):
1. Sepal length
2. Sepal width
3. Petal length
4. Petal width

## Technology
- Python
- scikit-learn
- Random Forest classification algorithm

## Project files
- `main.py` — loads the Iris dataset, trains and evaluates the model, and prints an example prediction.
- `requirements.txt` — required Python package.
- `.gitignore` — excludes temporary Python and virtual-environment files.

## How to run

1. Install Python 3.10 or later.
2. Open a terminal in this project folder.
3. (Optional but recommended) Create and activate a virtual environment.
4. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

5. Run the program:

   ```bash
   python main.py
   ```

The program prints the test accuracy, classification report, confusion matrix, and an example prediction. Exact results can vary slightly with software versions.

## Dataset
The project uses the classic Iris dataset included with scikit-learn, so you do not need to download a separate CSV file.

## Machine learning workflow
1. Load the Iris dataset.
2. Split the data into training and testing sets.
3. Train a Random Forest classifier on the training data.
4. Predict the species for the test set.
5. Evaluate the model using accuracy, a classification report, and a confusion matrix.
6. Predict the species for one example flower.

## Repository description
**Iris Flower Classification using Machine Learning and Random Forest in Python.**
