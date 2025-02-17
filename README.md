
# Exploratory Data Analysis (EDA) on Titanic Dataset

## Project Overview
This project is an Exploratory Data Analysis (EDA) of the Titanic dataset. The goal is to uncover key trends and patterns in the data, focusing on passenger demographics and survival outcomes.  

## Dataset
- **Source:** [Kaggle Titanic Dataset](https://www.kaggle.com/datasets/c0dev07/titanic-dataset)  
- **Number of Rows:** 889  
- **Number of Columns:** 12  

## Objectives
- Perform data cleaning and preparation.  
- Conduct univariate and multivariate analysis.  
- Visualize key insights using Python libraries.  

## Tools & Libraries
- **Pandas** – for data manipulation  
- **NumPy** – for numerical operations  
- **Matplotlib & Seaborn** – for visualizations  
- **Plotly** – for interactive plots  

## Key Steps
1. **Data Cleaning:**  
   - Filled missing values in `Age` with the mean.  
   - Replaced null values in `Cabin` with "Unknown".  
   - Capped outliers in `Age` and `Fare` using the IQR method.  

2. **Univariate Analysis:**  
   - Distribution of Age, Fare, Passenger Class, and Survival.  

3. **Multivariate Analysis:**  
   - Correlation between `Age`, `Fare`, `SibSp`, and `Parch`.  
   - Survival rates based on gender, class, and embarkation point.  

## Visualizations
Key visualizations include:  
- Boxplots for outlier detection and analysis.  
- Histograms for distributions.  
- Count plots for categorical variables.  
- Heatmaps for correlation analysis.

![survivor_counts](https://github.com/user-attachments/assets/175660e0-21d0-4f0d-b01e-c1a50fb439a4)
![pclass_count](https://github.com/user-attachments/assets/35798ad7-6b38-4dd1-a512-fd7e4571cdf1)
![survival_by_pclass](https://github.com/user-attachments/assets/acbe3067-541c-4e57-9196-257d7803111e)
![survival_by_sex](https://github.com/user-attachments/assets/836c7f7b-5bf7-411a-9323-0b9964ed0962)

## Key Findings
- **Survival Rate:** 38% of passengers survived.  
- **Gender:** Female passengers had a significantly higher survival rate.  
- **Class:** First-class passengers were more likely to survive.  

## How to Run the Notebook
1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/titanic-eda.git
   ```  
2. Install the required libraries:  
   ```bash
   pip install pandas numpy matplotlib seaborn plotly
   ```  
3. Open the Jupyter Notebook and run the cells sequentially.  

## Conclusion
This analysis provides valuable insights into factors affecting survival on the Titanic.

## Author
[Basit Adebayo Tiamiyu](https://github.com/lucid-bbayo)
