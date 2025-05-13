# Student Performance Analysis

This project analyzes the **StudentsPerformance.csv** dataset using Python's data analysis and visualization libraries. The goal is to uncover patterns in student scores based on demographic and contextual factors, and present key findings using various visualizations.

## 📊 Dataset Overview

The dataset contains test scores and demographic information for students in areas such as:

- Gender
- Parental level of education
- Lunch type
- Test preparation course
- Scores in Math, Reading, and Writing

## 📁 Dataset Source

If not already present in your environment, you can find similar datasets on [Kaggle](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams).

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## ✅ Project Tasks

### Task 1: Load and Explore the Dataset

- Loaded the dataset using Pandas with error handling for file issues.
- Displayed the first few rows and examined the structure using `.info()`.
- Checked and cleaned missing values (filled using mean/mode based on column type).

### Task 2: Basic Data Analysis

- Computed descriptive statistics (`mean`, `std`, `min`, `max`, etc.).
- Created a `total score` column.
- Grouped and analyzed scores by:
  - Gender
  - Parental level of education
  - Lunch type
  - Test preparation course

#### 🔍 Key Findings

1. Students with **standard lunch** perform better than those with free/reduced lunch.
2. Completing the **test preparation course** correlates with higher scores.
3. Higher **parental education level** is associated with better student performance.
4. Gender-based differences observed in performance across subjects.

### Task 3: Data Visualization

#### 📈 Line Chart
- Shows average test scores across months (synthetically generated for demonstration).

#### 📊 Bar Chart
- Compares average scores by **parental level of education**.

#### 📉 Histograms
- Displays the distribution of scores for:
  - Math
  - Reading
  - Writing

#### ⚫ Scatter Plots
- Visualizes relationships:
  - Math vs Reading (by gender)
  - Math vs Writing, etc.

## 🧪 How to Run

1. Make sure you have Jupyter Notebook and Python installed.
2. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
