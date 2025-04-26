![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Lab | Data Cleaning

## Introduction

Data cleaning is a critical step in the data analysis process. As a data scientist, you will often encounter messy and complex datasets that require significant effort to refine and restructure before analysis. This lab focuses on practicing data cleaning techniques using a weather dataset. You will work through various steps to clean and prepare the data for further analysis.

## Getting Started

In this lab, you will be working with a weather dataset (`weather.csv`) that contains daily weather records for a weather station (MX17004) in Mexico during five months in 2010. Your goal is to clean and tidy this dataset to make it ready for analysis.

To get started:

1. Open the file `main.ipynb` located in the `your-code` folder.
2. Follow the instructions provided in each cell of the notebook and complete the tasks.

## Goals

The primary objective of this lab is to clean and tidy the weather dataset. You will apply various data cleaning techniques, such as handling missing values, correcting data types, and restructuring the dataset for analysis.

### Challenge Tasks

1. Load and Explore the Dataset
   - Import the dataset into a pandas DataFrame.
   - Explore its structure, columns, and summary statistics.
   - **Hint:Variables are stored in both rows and columns.**

2. Handle Missing Values
   - Identify missing values in the dataset.
   - Apply appropriate methods to handle these missing values (e.g., imputation or removal).

3. Correct Data Types
   - Inspect the data types of each column.
   - Convert columns to their appropriate data types (e.g., dates, numeric values).

4. Tidy the Dataset
   - Reshape the dataset as needed to ensure it adheres to tidy data principles.
   - Use techniques such as melting or pivoting to organize variables into columns.

5. Validate and Save
   - Ensure that your cleaned dataset is free of inconsistencies.
   - Save the cleaned dataset as `cleaned_weather.csv` in the `your-code` folder.

6. Bonus Task: Outlier Detection
   - Identify any outliers in the cleaned dataset.
   - Create a separate DataFrame containing these outliers and save it as `outliers.csv`.

**:exclamation: Feel free to create your own solution file instead of following the guided steps in `main.ipynb`.**

To accomplish this challenge, you will need to do some research on tidying and melt&pivot. Feel free to reference any resources you consider appropiate.

## Deliverables

- A completed `main.ipynb` file with your responses and code for all tasks.
- A cleaned version of the dataset saved as `cleaned_weather.csv`.
- A file containing identified outliers saved as `outliers.csv`.

## Submission

Upon completion, add your deliverables to git. Then commit git and push your branch to the remote.

## Additional Challenges for Advanced Learners

If you complete all tasks without difficulty, consider diving deeper into advanced data cleaning techniques:
- Experiment with advanced outlier detection methods (e.g., Z-scores or IQR).
- Explore ways to visualize missing data patterns using libraries like `plotly` or `seaborn`.

<br>

**Good luck!**