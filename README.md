# Elevatelab_Task_3
This project performs Exploratory Data Analysis (EDA) on the Netflix Movies and TV Shows dataset using Python in Google Colab.  
The objective is to understand data patterns, distributions, trends, and key insights through statistical analysis and visualizations.

Dataset Information
Dataset Name: Netflix Movies and TV Shows

Source: Kaggle

File Used: netflix_titles.csv

Records: Movies and TV shows available on Netflix

 # Tools & Technologies
  
- Platform: Google Colab
  
- Language:  Python

- Libraries Used:

  - Pandas
  
  - NumPy

  - Matplotlib
  
  - Seaborn

# Exploratory Data Analysis Performed
 
- Dataset shape and structure analysis
  
- Missing value handling
  
- Statistical summary
  
- Histogram for numerical features
  
- Count plots for categorical features
  
- Box plot for outlier detection
  
- Heatmap for correlation analysis


# Categorical Feature Analysis
Count plots for:

Movies vs TV Shows

Content ratings

Identified dominant categories and class imbalance

Duration Analysis
Extracted numerical values from the duration column

Analyzed movie durations (minutes) and TV show seasons separately

Used box plots to identify outliers


#  Key Insights

- Netflix content increased rapidly after 2010
  
- Movies are more frequent than TV Shows
  
- TV-MA is the most common rating
  
- Older titles appear as outliers
  
- Release year is a key feature in trend analysis


Important Features Identified
type

release_year

rating

duration

listed_in

country

These features are useful for future predictive modeling or recommendation systems.

Output
<img width="940" height="653" alt="Image" src="https://github.com/user-attachments/assets/4047a59a-f503-420d-8ce2-09e5457469ea" />
<img width="992" height="668" alt="Image" src="https://github.com/user-attachments/assets/6d5e6d68-52cc-4431-8663-d809f909276a" />
Conclusion
This EDA helped in understanding Netflix’s content distribution, detecting outliers, and identifying important features. The insights gained from this analysis can be used for building machine learning models such as content recommendation or classification systems.
