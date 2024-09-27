# Student Final Grade Prediction Project

## Project Overview

This project aims to develop a predictive model that estimates students' final grades based on various features, including demographics, study habits, and socio-economic factors. By analyzing these features, the model seeks to provide insights into the factors that significantly influence academic performance, helping educators identify students who may need additional support.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Data Source](#data-source)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Limitations](#limitations)
- [Future Work](#future-work)
- [Acknowledgments](#acknowledgments)

## Features

The model utilizes the following features:

- **Sex**: Gender of the student (F/M)
- **Address**: Type of residence (Urban: U, Rural: R)
- **Age**: Age of the student (in years)
- **Study Time**: Amount of study time (1: <2 hours, 2: 2-5 hours, 3: 5-10 hours, 4: >10 hours)
- **Absences**: Number of absences from classes
- **Mother's Job**: Occupation of the mother (teacher, health, services, at_home, other)
- **Father's Job**: Occupation of the father (teacher, health, services, at_home, other)

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Data Source

The dataset used for this project is available at the UCI Machine Learning Repository:

- [Student Performance Dataset](https://archive.ics.uci.edu/ml/machine-learning-databases/00320/student.zip)

## Installation

To run this project, ensure you have Python and the required libraries installed. You can install the necessary libraries using pip:

```bash
pip install pandas scikit-learn matplotlib seaborn
```

## Usage

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

3. Open the provided Jupyter Notebook file and execute the cells to see the model training process and predictions.

4. Enter your inputs when prompted to predict the final grade.

## Results

- The model produces predictions on a scale of 0 to 20, based on the input features.
- Initial evaluation metrics (e.g., Mean Squared Error, R² Score) indicate that the model requires further refinement for improved accuracy.

## Limitations

- The current model does not yield highly accurate predictions, highlighting the complexity of educational outcomes.
- The features selected may not capture all relevant factors influencing student performance.

## Future Work

- Experiment with more advanced models (e.g., Random Forest, Gradient Boosting) to enhance predictive accuracy.
- Explore additional features that may provide better insights into academic performance, such as peer influence or mental health factors.
- Implement cross-validation techniques for more robust model evaluation.

## Acknowledgments

- Special thanks to the UCI Machine Learning Repository for providing the dataset.
- Appreciation for the mentorship and support during my internship.
