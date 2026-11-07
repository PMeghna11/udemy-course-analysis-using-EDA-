
# Udemy Course Market Analysis

## Project Overview

This project focuses on analyzing Udemy course data to understand course characteristics, pricing trends, discount patterns, and relationships between different course attributes.

With a large number of courses available on online learning platforms, learners may find it difficult to select suitable courses based on factors such as price, ratings, duration, lecture count, and course level.

This project uses Python, Exploratory Data Analysis (EDA), data visualization, and statistical hypothesis testing to explore these factors and generate meaningful insights.

## Business Problem

The increasing number of courses available on Udemy makes it challenging for learners to choose suitable courses based on affordability, ratings, duration, lecture count, and course level.

There is a need to analyze course-related data to understand pricing and discount patterns and identify relationships between different course features. This analysis aims to support informed course-selection decisions and help instructors understand course pricing trends.

## Project Objectives

- Understand the structure and characteristics of Udemy course data.
- Perform data cleaning and preprocessing.
- Analyze course distributions based on ratings, duration, lecture count, course level, and pricing.
- Identify pricing trends and discount patterns.
- Explore relationships between different course attributes.
- Identify potential outliers and patterns in numerical variables.
- Apply statistical hypothesis testing using T-test, ANOVA, and Chi-square tests where applicable.
- Generate meaningful insights and conclusions from the analysis.

## Dataset Description

The dataset contains information about Udemy courses, including:

| Column Name | Description |
|---|---|
| Course_Name | Name of the course |
| Instructor | Course instructor |
| Ratings_Out_of_5 | Course rating out of 5 |
| Ratings_Count | Number of ratings received |
| Course_Duration | Total course duration |
| Lectures_count | Number of lectures |
| Course_level | Difficulty level of the course |
| Current_price | Current course price |
| Orginal_price | Original course price |
| Add_to_cart | Add-to-cart availability |

## Technologies and Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook

## Project Workflow

### 1. Data Collection
Collected Udemy course information for analysis.

### 2. Data Understanding
- Checked dataset dimensions.
- Examined column names and data types.
- Generated descriptive statistics.

### 3. Data Cleaning and Preprocessing
- Checked and handled missing values.
- Identified duplicate records.
- Examined inconsistent and invalid values.
- Prepared data for further analysis.

### 4. Exploratory Data Analysis (EDA)

**Univariate Analysis**
- Analyzed individual numerical and categorical variables.
- Studied distributions of course prices, ratings, and duration.

**Bivariate Analysis**
- Explored relationships between two variables.
- Compared course prices with ratings and duration.
- Examined original prices and current prices.

**Multivariate Analysis**
- Analyzed relationships among multiple numerical variables.
- Used correlation analysis and visualizations to identify patterns.

### 5. Feature Engineering
Created additional features such as:

- Discount Percentage
- Price Savings

### 6. Outlier Analysis
Used boxplots and statistical techniques to identify potential outliers in numerical variables.

### 7. Statistical Hypothesis Testing

Applied statistical tests to investigate selected relationships:

- **T-test:** To compare average course prices between courses marked Yes and No in Add-to-Cart.
- **ANOVA:** To examine differences in average course prices across course levels.
- **Chi-square Test:** To investigate the association between course level and Add-to-Cart status.

The null and alternative hypotheses were formulated, and p-values were compared with a significance level (alpha) of 0.05 to make statistical decisions.

### 8. Insights and Conclusions
Summarized the findings from EDA and statistical analysis to understand course pricing patterns and relationships between course attributes.

## Key Areas of Analysis

- Course pricing and discount distribution.
- Course ratings and rating distribution.
- Course duration and lecture count.
- Course-level distribution.
- Relationships between course attributes.
- Add-to-cart availability.
- Statistical significance of selected relationships.

## Project Structure

```text
Udemy-Course-Market-Analysis/
│
├── Udemy_Course_Analysis.ipynb
├── udemy_courses.csv
└── README.md
```

## How to Run the Project

1. Clone this repository:

   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project folder:

   ```bash
   cd Udemy-Course-Market-Analysis
   ```

3. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn scipy jupyter
   ```

4. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open the notebook and execute the cells to explore the analysis.

## Conclusion

This project provides an exploratory analysis of Udemy course data using Python. It examines course characteristics, pricing and discount patterns, and relationships between different attributes. EDA and statistical hypothesis testing help investigate patterns in the available data and derive insights that can support course-selection and pricing decisions.

## Future Scope

- Collect a larger dataset covering more Udemy courses.
- Perform more detailed comparisons across course categories and levels.
- Analyze additional factors influencing course selection.
- Build an interactive dashboard to present the findings.
- Explore machine learning techniques for course price or rating prediction.
