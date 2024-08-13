# Wine Quality Predictor

## Overview

The **Wine Quality Predictor** project is a machine learning application designed to predict the quality of wine based on its chemical properties. The project uses a Random Forest Classifier to analyze features like acidity, residual sugar, chlorides, and more to predict the quality of the wine on a scale.

This project includes both a Jupyter Notebook (`WineQualityPredictor.ipynb`) for data analysis and model training, as well as a Python script (`wine_quality_with_gui.py`) that provides a graphical user interface (GUI) for users to input wine features and get a quality prediction.

## Project Structure

- **`WineQualityPredictor.ipynb`**: This Jupyter Notebook contains the data exploration, feature analysis, model training, and evaluation.
- **`wine_quality_with_gui.py`**: A Python script that implements the GUI using Tkinter. Users can input wine characteristics, and the trained model predicts the quality.
- **`winequality-red.csv`**: The dataset used for training the model. It contains the chemical properties of different wines and their quality ratings.

## Dependencies

To run the project, you need to install the following Python libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
