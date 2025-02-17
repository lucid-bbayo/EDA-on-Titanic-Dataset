# Exploratory Data Analysis (EDA) Report

## **1\. Title and Introduction**

This report presents a comprehensive Exploratory Data Analysis (EDA) of the Titanic dataset. The objective is to analyze trends, patterns, and correlations to uncover key insights into passenger demographics and survival outcomes.

## **2\. Data Overview**

The Titanic dataset contains 891 rows and 12 columns. Features such as 'Name', 'Age', and 'Fare' provide insights into passenger characteristics. Missing values and duplicates were handled as follows:  
\- 'Age' missing values were filled with the mean age.  
\- 'Cabin' missing values were replaced with 'Unknown'.  
\- Rows with any other missing values were removed.
The dataframe ended up with 891 rows and 12 columns.

## **3\. Data Cleaning**

Several steps were taken to clean the data:  
\- Missing values in 'Age' were filled with the mean.  
\- 'Cabin' missing values were replaced with 'Unknown'.  
\- Outliers in 'Age' and 'Fare' were capped using the IQR method.

## **4\. Univariate Analysis**

Univariate analysis was conducted to explore individual features using visualizations such as histograms and boxplots. They include:  
\- Age Distribution: Most passengers were between 22 and 35 years old.  
\- Fare Distribution: Fares ranged from 0 to around 512.33 units, with some outliers, but the most common fares fall between 7.90 and 31 units (based on the capped fares).
\- Passenger Class: The passenger class with the highest number of passengers is the third class (3), while second class (2) has the lowest number of passengers.

## **5\. Multivariate Analysis**

Multivariate analysis was conducted to explore relationships between variables. Key visualizations include:  
\- Scatter plots to analyze the relationship between Age and Fare.  
\- Correlation heatmaps for numerical variables.  
\- Boxplots to analyze the distribution of Age and Fare by survival status.

## **6\. Key Insights**

Some of the key findings from the analysis include:  
\- The overall survival rate was 38%.  
\- Females had a significantly higher survival rate than males (74% vs. 19%).  
\- First-class passengers were more likely to survive compared to other classes.

## **7\. Conclusion**

This analysis revealed several factors that contributed to survival on the Titanic, including gender, class, and age. 
