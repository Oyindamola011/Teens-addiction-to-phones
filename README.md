# Teens phone addiction and behavioural patterns analysis

### Project overview

This data analysis explores more about the usage of phone by teens and how it has affect different areas of their lives including the academic performance,sleep habits,family communication and also the mental health like anxiety level,depression level and self esteem.
 The goal is to identify the relationship and patterns in how addiction of phone has influenced the behaviour and well being of the teens.

 ### Data sources
Teens phone addiction and behavioural patterns analysis : The primary dataset used for this analysis is the "Teens_addiction_to_phones.csv" containing detailed infromation about how phone addiction has influenced the life of teens.

### Tools and Libraries
- Python - Analyze the data
- Pandas - Data cleaning and revealing insights.
- Matplotlib & Seaborn - Data visualization
- Numpy - To perform and show the correlations between variables

 ### Objectives
 - Analyze the relationship between phone addiction and key behavioral factors such as:
 -  Academic performance
 -  Sleep hours
 -  Use of educational, social media and gaming apps
 -  Family communication 
 -  Self-esteem, anxiety and depression levels
 -  Investigate phone usage trends (weekdays vs weekends, hours spent, number of phone checks per day).
 -   Understand how parental control affects addiction levels.
   
 ### Data cleaning 
 - Loading and inspection of dataset into the IDE
 - Handling missing values
 - Dropping of duplicates
 - Convert & correct data types,ensure columns that should be numbers are numeric and categorical columns are text/category.
 - Standardize text in order for grouping and counts to be more accurate.
 - Create helpful new columns to make comparisons and grouping easier and more meaningful.

### Exploratory data analysis
EDA is exploring the dataset to answer key questions :
- What is the average daily phone usage across teens
- What is the relationship between screen time before bed and sleep hours
- what is the relationship between addiction level and family communication
- What is the daily phone usage on weekdays and weekends
- How it affects based on school grades and academic performance
- the most used purpose of phone by teens (social media,education , gaming ,browsing and others)

  ### Data analysis
  ```Python
     print(df.head())
  df.drop_duplicates(inplace=True)
  for col in ['gender','location','school_grade']:
 df[col] = df[col].fillna('Unknown')
  
