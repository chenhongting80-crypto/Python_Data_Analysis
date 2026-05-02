# Python Data Analysis

This repository contains practice projects for Python data analysis. The projects cover common steps in a data analysis workflow, including data loading, data assessment, data cleaning, exploratory data analysis, visualization, and basic statistical analysis.

## Projects

### 1. E-commerce Data Cleaning and Assessment

This project focuses on cleaning and assessing an e-commerce transaction dataset using Python and pandas.

Main steps include:

- Loading the raw dataset
- Assessing data structure and data quality
- Handling missing values
- Removing duplicated rows
- Standardizing inconsistent country names
- Removing invalid transaction records
- Converting data types
- Exporting the cleaned dataset

---

### 2. Netflix Movie Actor Rating Data Analysis

This project focuses on organizing Netflix movie and TV actor rating data using Python and pandas. The goal is to calculate actors' average IMDb scores across different genres and identify actors associated with the highest-rated works in each genre.

Main steps include:

- Loading the `titles.csv` and `credits.csv` datasets
- Assessing data tidiness and data quality
- Handling missing values in key columns
- Converting the `genres` column into list format
- Splitting genre lists into separate rows using `explode()`
- Removing duplicated records based on key identifiers
- Filtering actor records from the credits dataset
- Merging title information with actor information
- Calculating average IMDb scores by genre and actor
- Identifying the highest-scoring actors in each genre
- Exporting the cleaned datasets and final analysis result

---

### 3. Palmer Penguins Data Visualization

This project focuses on visualizing the Palmer Penguins dataset using Python, pandas, matplotlib, and seaborn. The goal is to explore the relationships between penguin species, island, sex, and body measurements, including culmen length, culmen depth, flipper length, and body mass.

Main steps include:

- Loading the `Penguins.csv` dataset
- Assessing data structure and data quality
- Handling missing values
- Converting categorical variables to the `category` data type
- Removing invalid category values in the `sex` column
- Checking summary statistics for numerical variables
- Visualizing sample distributions by species, island, and sex
- Comparing species and island distributions using count plots
- Comparing body measurements across species using box plots
- Comparing body measurements by sex within each species
- Exploring relationships among numerical body measurements using pair plots
- Using species and sex as grouping variables to examine visible clusters
- Summarizing major visual patterns in penguin body measurements

---

### 4. Iris Species Data Analysis

This project analyzes the Iris dataset using Python, pandas, seaborn, matplotlib, and statistical testing. The goal is to compare numerical features between Iris-setosa and Iris-versicolor and examine which variables are useful for distinguishing the two species.

Main steps include:

- Loading the `Iris.csv` dataset
- Assessing data structure and data quality
- Cleaning and preparing the dataset
- Comparing numerical variables between species
- Visualizing feature distributions using histograms
- Comparing feature values using box plots
- Exploring relationships among variables using pair plots
- Performing independent two-sample t-tests
- Interpreting statistical results based on p-values and significance levels

## Tools Used

- Python
- pandas
- NumPy
- matplotlib
- seaborn
- scipy
- Jupyter Notebook

## Skills Practiced

- Data loading and inspection
- Data cleaning
- Handling missing and invalid values
- Data type conversion
- Grouped analysis
- Data visualization
- Exploratory data analysis
- Basic statistical testing
- Result interpretation
- Jupyter Notebook documentation
