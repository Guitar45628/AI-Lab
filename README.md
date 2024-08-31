# **AI-Lab Documentation**

## Table of Contents
1. [Introduction](#introduction)
2. [Lab 1: Getting Started with NumPy and Pandas](#lab-1-getting-started-with-numpy-and-pandas)
3. [Lab 2: Data Preprocessing](#lab-2-data-preprocessing)
4. [Lab 3: Data Analysis and Statistical Testing](#lab-3-data-analysis-and-statistical-testing)
5. [Lab 4: Model Testing for Artificial Intelligence](#lab-4-model-testing-for-artificial-intelligence)
---


## Introduction
Welcome to the AI-Lab series! This README file serves as a comprehensive guide to the labs in this series. Each lab is designed to build your skills in AI, starting from the basics and moving to more advanced topics.

## Lab 1: Getting Started with NumPy and Pandas

In this lab, you will get familiar with **NumPy** and **Pandas**, two essential libraries for data manipulation and analysis in Python. The lab will introduce you to basic functionalities and how to use these libraries for handling data.

- **Objective**: Understand the fundamentals of NumPy and Pandas and how to apply them to data handling and analysis.
- **Prerequisites**: Basic knowledge of Python programming. ✨

### Instructions
1. Open the Colab notebook linked below.
2. Follow the instructions in the notebook to complete the exercises.
3. Execute the provided code examples to explore how NumPy and Pandas work.
4. Experiment with the code to better understand the libraries' functionalities.

### Key Concepts
- **NumPy**: A library for numerical computations, providing support for multi-dimensional arrays and mathematical functions.
- **Pandas**: A library for data manipulation, offering data structures like DataFrames for efficiently handling tabular data.

### Expected Outcome
By the end of this lab, you should be comfortable with the basics of NumPy and Pandas and able to perform basic data manipulation and analysis tasks.

- **[Open Lab 1 Notebook](https://colab.research.google.com/drive/1Jjr1HsOYW2Q4vXux60kdMUQ8osBZk2Q4?usp=sharing)**

Feel free to explore the Colab notebook for interactive exercises and examples. Happy learning!

## Lab 2: Data Preprocessing

In this combined lab, you will cover essential data preprocessing techniques using Pandas, as well as advanced preprocessing methods such as normalization and feature engineering.

### Part I: Basic Data Preprocessing

In this part, you will learn the basics of data preprocessing using Pandas. This includes creating DataFrames, splitting and merging data, handling missing values, and dealing with outliers and categorical data.

- **Objective**: Understand and apply basic data preprocessing techniques using Pandas to prepare data for analysis and modeling.
- **Prerequisites**: Completion of Lab 1 or basic knowledge of Pandas.

#### Instructions
1. Open the Colab notebook linked below.
2. Download and upload the required files (`IMI_Dataset.csv` and `dataset_missing_value.csv`) to the Colab environment.
3. Follow the instructions in the notebook to complete the exercises, including data manipulation tasks such as filtering, merging, handling missing values, detecting outliers, and encoding categorical data.

#### Key Concepts
- **DataFrame Creation**: Learn to create and manipulate DataFrames from various data sources.
- **Data Splitting and Merging**: Techniques for dividing and combining datasets.
- **Missing Value Handling**: Strategies to address and impute missing data.
- **Outlier Detection**: Methods to identify and handle outliers in your data.
- **Categorical Data Encoding**: Converting categorical data into numerical formats for analysis.

#### Files to Download
- [IMI_Dataset.csv](link-to-IMI_Dataset.csv)
- [dataset_missing_value.csv](link-to-dataset_missing_value.csv)

#### Expected Outcome
By the end of this part, you should be proficient in basic data preprocessing techniques and ready to apply these skills to prepare data for further analysis and modeling.

- **[Open Lab 2 Part I Notebook](https://colab.research.google.com/drive/1c5O6tKlRVbqTEzT95z5JzNyDaLZEDPym?usp=sharing)**

### Part II: Advanced Data Preprocessing

In this part, you will explore advanced preprocessing techniques, including normalization and feature engineering. This involves handling various types of features: numeric, datetime, text, and image.

- **Objective**: Learn advanced data preprocessing techniques including normalization and feature engineering for various types of data.
- **Prerequisites**: Completion of Lab 1 and Lab 2 Part I or equivalent knowledge.

#### Instructions
1. Open the Colab notebook linked below.
2. Download and upload any additional required files to the Colab environment.
3. Follow the instructions in the notebook to complete the exercises related to normalization and feature engineering.

#### Key Concepts
- **Normalization**: Scaling numeric data to a standard range to improve the performance of machine learning models.
- **Feature Engineering**:
  - **Numeric Features**: Techniques for binning and scaling numeric data.
  - **Datetime Features**: Extracting and creating new features from datetime data.
  - **Text Features**: Utilizing methods like word counts and TF-IDF for text data analysis.
  - **Image Features**: Extracting and processing features from image data.

#### Files to Download
- [IMI_Dataset.csv](https://colab.research.google.com/drive/179uz7UA5vlZ47P7SHnZUeYHm-1yEHAy5?usp=sharing)

#### Expected Outcome
By the end of this part, you should be proficient in normalizing datasets and engineering features for various data types, preparing you for more advanced data analysis and machine learning tasks.

- **[Open Lab 2 Part II Notebook](https://colab.research.google.com/drive/179uz7UA5vlZ47P7SHnZUeYHm-1yEHAy5?usp=sharing)**

Dive into the Colab notebook for practical exercises and enhance your feature engineering skills. Enjoy exploring advanced data preprocessing techniques!

## Lab 3: Data Analysis and Statistical Testing

In this lab, you will focus on various data analysis techniques and statistical tests to understand your dataset better. This includes analyzing central tendency, variability, data shape, and performing statistical tests such as Pearson correlation, T-Test, and ANOVA.

- **Objective**: Gain insights into data analysis techniques and apply statistical tests to evaluate relationships and differences in your dataset.
- **Prerequisites**: Completion of Lab 1 and Lab 2 or equivalent knowledge.

### Instructions
1. Open the Colab notebook linked below.
2. Download and upload the required file (`IMI_Dataset.csv`) to the Colab environment.
3. Follow the instructions in the notebook to complete the exercises, including:
   - Calculating measures of central tendency (mean, median, mode).
   - Assessing measures of variability (variance, standard deviation).
   - Understanding the shape of data (skewness, kurtosis).
   - Performing Pearson correlation to analyze relationships between variables.
   - Conducting T-Test and ANOVA to test for significant differences between groups.
   - Using built-in feature selection techniques to identify significant features.

### Key Concepts
- **Central Tendency**: Measures of mean, median, and mode to understand the central value of the data.
- **Measure of Variability**: Variance and standard deviation to assess the spread of the data.
- **Shape of Data**: Analyzing skewness and kurtosis to understand data distribution.
- **Pearson Correlation**: Evaluating the linear relationship between variables.
- **T-Test**: Comparing the means of two groups to determine if they are significantly different.
- **ANOVA**: Analyzing the differences between means of multiple groups to determine if there are significant differences.
- **Built-in Feature Selection**: Identifying the most important features using Scikit-learn's `SelectKBest`.

#### Files to Download
- [IMI_Dataset.csv](https://colab.research.google.com/drive/1ycI7f-URPtf1uzEfevqG0FHlgKIC4ebx?usp=sharing)

#### Expected Outcome
By the end of this lab, you should be proficient in data analysis techniques and statistical testing, allowing you to derive meaningful insights and validate hypotheses about your dataset.

- **[Open Lab 3 Notebook](https://colab.research.google.com/drive/1ycI7f-URPtf1uzEfevqG0FHlgKIC4ebx?usp=sharing)**
- 
## Lab 4: Model Testing for Artificial Intelligence

In this lab, you will test different machine learning models using performance metrics to evaluate their effectiveness. The focus will be on testing a regression model using the R-squared metric and a classification model using accuracy.

- **Objective**: Learn how to evaluate machine learning models using appropriate metrics for regression and classification tasks.
- **Prerequisites**: Completion of Lab 1, Lab 2, and Lab 3 or equivalent knowledge.

### Instructions
1. Open the Colab notebook linked below.
2. Download and upload the required file (`IMI_Dataset.csv`) to the Colab environment.
3. Follow the instructions in the notebook to complete the exercises:
   - **Testing Regression Models**: Evaluate a regression model using the R-squared value.
   - **Testing Classification Models**: Assess a classification model using accuracy.

### Key Concepts
- **R-squared Metric**: Measures the proportion of variance in the dependent variable that is predictable from the independent variables. Useful for evaluating regression models.
- **Accuracy Metric**: Indicates the proportion of correct predictions made by the classification model. Useful for evaluating classification models.

#### Files to Download
- [IMI_Dataset.csv](https://colab.research.google.com/drive/1ycI7f-URPtf1uzEfevqG0FHlgKIC4ebx?usp=sharing)

#### Expected Outcome
By the end of this lab, you should be able to evaluate machine learning models using appropriate metrics and understand their effectiveness in making predictions.

- **[Open Lab 4 Notebook](https://colab.research.google.com/drive/1ycI7f-URPtf1uzEfevqG0FHlgKIC4ebx?usp=sharing)**


