# data-science-project

# Impact of Education on Annual Salary and Weekly Working Hours

## 1. Problem / Research Question
The objective of this data science project is to analyze the relationship between an individual's education level and their annual salary and weekly working hours. Specifically, it investigates how different educational attainments (e.g., No diploma, High school diploma, Bachelor's degree or higher) correlate with earning potential and work commitment among individuals under the age of 65.

## 2. Dataset Source and Usage Permissions
The dataset `age_salary_hours.csv` used in this project is an open-access dataset provided for educational purposes. It contains anonymized records including Age, Annual Salary, Weekly hours, and Education level. 
Usage permission: The data does not contain any Personally Identifiable Information (PII) and is solely used for academic analysis in this portfolio.

## 3. Methods and Tools Used
- **Data Cleaning**: Filtered the dataset to include only individuals under 65 years old to focus on the primary working-age population.
- **Exploratory Data Analysis (EDA)**: Calculated the distribution of education levels and examined salary/hours variances.
- **Visualization**: 
  - Used `squarify` to create a treemap showing the proportion of different education degrees in the dataset.
  - Used `seaborn` violin plots to visualize the distribution of Annual Salary and Weekly Hours across different education levels.
- **Tools**: Python, Pandas, Matplotlib, Seaborn, Squarify.

## 4. Key Findings and One Limitation
**Key Findings:**
- Individuals with a **"Bachelor's degree or higher"** make up the largest proportion of the dataset (47.4%) and demonstrate the widest range of annual salaries, with a noticeably higher upper bound compared to other groups.
- While weekly working hours are relatively concentrated around 40 hours for all education levels, the distribution of annual salary shows significant variance, indicating that factors other than just working hours (and education) heavily influence income.

**Limitation:**
- The dataset has a relatively small sample size and contains extreme outliers (e.g., a very high annual salary of over $600,000). This may skew the average salary representations for certain education groups and might not fully represent the broader population.

## 5. Instructions for Running the Analysis
To reproduce this analysis, please follow these steps:
1. Clone this repository to your local machine.
2. Ensure you have Python installed (version 3.8 or higher is recommended).
3. Install the required dependencies by running:
   ```bash
   pip install -r requirements.txt
