
# Income Classification with the Adult Census Dataset

This project analyzes the Adult Income dataset to predict whether an individual earns more than $50K annually based on demographic and employment attributes. It showcases a full data science workflow from raw data ingestion to feature engineering and exploratory analysis.

# Project Highlights:

 Data Cleaning:
  ⁠ Replaced ambiguous entries (?) with NaN and dropped missing values.
  
  ⁠ Removed duplicates to ensure data integrity.
  
  ⁠ Dropped irrelevant columns (educational-num, capital-gain, capital-loss) to reduce noise.
  
•  Exploratory Data Analysis (EDA):

  ⁠  Visualized distributions of age, workclass, education, and income.
  
  ⁠  Identified demographic patterns and salary disparities across gender, education, and workclass.
  
  ⁠ Found that males and those in self-employment or government roles had higher income probabilities.
  
•  Feature Engineering:

  ⁠   Encoded categorical variables using LabelEncoder.
  
  ⁠   Converted salary labels (<=50K, >50K) into binary format for classification.
  
•  Insights:

  ⁠     Self-employed individuals and federal employees had the highest likelihood of earning >$50K.
  
  ⁠     Males were significantly more likely than females to earn above the threshold.
  
  ⁠      Bachelors and Masters degree holders formed a strong segment of high earners.

# Tools & Technologies:

•  Python (Pandas, NumPy, Seaborn, Matplotlib)

•  Jupyter Notebook

•  Scikit-learn for preprocessing and encoding
