# Internship Day 5 - Data Analysis and Visualization

Welcome to the **Internship Day 5** project repository! This project involves data analysis, visualization, and preprocessing using a dataset `train.csv`. The notebook `untitled1.ipynb` contains the steps for data cleaning, exploration, and various visualizations.

## Project Overview

In this project, we perform the following tasks:

- **Data Cleaning**: Handle missing values, clean up erroneous data, and preprocess the dataset.
- **Data Exploration**: Perform basic analysis and explore the dataset using summary statistics and visualizations.
- **Visualization**: Create attractive, meaningful, and visually appealing charts to understand the relationships between variables.
- **Feature Engineering**: Extract new features (e.g., creating a 'Deck' feature from the 'Cabin' column).
- **Plotting**: Use various plotting techniques like histograms, count plots, box plots, pair plots, and heatmaps.

## Files in the Repository

1. **train.csv**: The dataset used for the analysis. This file contains information about Titanic passengers, including columns like 'Age', 'Fare', 'Pclass', 'Sex', 'Embarked', and more.

2. **untitled1.ipynb**: The Jupyter notebook where all the data analysis and visualizations are performed. It includes code for:
   - Data cleaning and handling missing values.
   - Exploratory data analysis (EDA).
   - Data visualization using Seaborn and Matplotlib.
   - Feature engineering (e.g., creating a 'Deck' column).
   - Analysis of correlations and survival patterns.

## Libraries Used

- **Pandas**: For data manipulation and cleaning.
- **Seaborn**: For beautiful and informative statistical visualizations.
- **Matplotlib**: For custom plotting and visual representation of data.
- **NumPy**: For numerical operations.

## Getting Started

### Prerequisites

Make sure you have the following libraries installed:

```bash
pip install pandas seaborn matplotlib numpy
```
Running the Code
Clone the repository:

```bash
git clone https://github.com/Akhileshwar-2509/Internship-Day5.git
```

Navigate to the project directory:
```bash
cd Internship-Day5
```
Open the Jupyter notebook:
```bash
jupyter notebook untitled1.ipynb
```

Run the code cells step by step in the notebook to see the data analysis and visualizations.
Visualizations
Here are some of the key visualizations included in the project:

Histogram of Age and Fare: Displays the distribution of the Age and Fare columns.

Survival Counts: Shows the count of survivors and non-survivors.

Survival by Class: A count plot of survival based on passenger class.

Survival by Gender: Analyzes survival rates based on gender.

Survival by Embarked Port: Visualizes survival rates across different embarkation ports.

Correlation Heatmap: Analyzes the correlation between numerical variables.
Conclusion
This repository provides a solid foundation for performing data analysis on the Titanic dataset. The visualizations help uncover insights related to survival rates, passenger demographics, and other important patterns.

Feel free to explore the notebook, modify the code, or use the techniques for your own projects.

