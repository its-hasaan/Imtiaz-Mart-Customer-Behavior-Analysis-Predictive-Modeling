## Customer Behavior Analysis & Predictive Modeling Project

This project analyzes customer behavior patterns in an electronics retail dataset, using various data science techniques to extract insights and develop predictive models for future purchasing behavior.

### Project Overview

This comprehensive data science project explores customer purchasing patterns, preferences, and behaviors using a dataset of electronic retail transactions. The analysis employs multiple techniques including exploratory data analysis, regression modeling, decision tree classification, and customer segmentation to develop actionable business intelligence.

### Key Components

#### 1. Data Acquisition & Preprocessing

- **Data Loading**: Imported data from JSON files containing customer purchase records.
- **Data Cleaning**:
  - Identified and addressed missing values across 19 columns.
  - Applied appropriate filling strategies (mode for categorical variables, mean for numerical).
  - Handled inconsistencies in format, spelling, and data types.
- **Data Transformation**:
  - Created derived features like recency, age groups, and day of purchase.
  - Converted dates to datetime format.
  - Standardized text fields for consistency.

#### 2. Exploratory Data Analysis

- **Univariate Analysis**: Examined distributions of key variables including age, purchase amount, and purchase frequency.
- **Bivariate Analysis**:
  - Analyzed relationships between purchase amount and income level.
  - Explored brand preferences across product categories.
  - Identified correlations between age groups and purchase behaviors.
- **Temporal Analysis**:
  - Tracked purchase trends over time (months, years).
  - Identified seasonal variations in spending and product preferences.

#### 3. Predictive Modeling

- **Linear Regression**:
  - Predicted average customer spending based on demographic and behavioral features.
  - Performed preprocessing with one-hot encoding for categorical variables.
  - Evaluated model performance with MAE, MSE, and R-squared metrics.
- **Decision Tree Classification**:
  - Built a predictive model for future purchases.
  - Identified key features influencing purchase decisions.
  - Achieved high accuracy (90.5%) with balanced precision (97.0%) and recall (92.0%).

#### 4. Customer Segmentation

- **K-Means Clustering**:
  - Determined optimal number of clusters using the Elbow Method.
  - Identified 3 distinct customer segments based on purchase amount, frequency, and brand affinity.
  - Visualized clusters using Principal Component Analysis.
- **Cluster Analysis**:
  - Characterized each segment based on purchasing behavior and preferences.
  - Developed targeted marketing recommendations for each cluster.

#### 5. Model Evaluation & Recommendations

- **Comparative Analysis**: Evaluated strengths and limitations of each modeling approach.
- **Actionable Insights**:
  - Identified brand preferences across product categories.
  - Determined peak purchasing seasons.
  - Developed targeted age-based marketing strategies.

### Tools & Technologies Used

- Python with pandas, numpy, matplotlib, seaborn
- Scikit-learn for machine learning models
- Jupyter Notebook for interactive development and visualization

### Conclusion

The project successfully identified key patterns in customer behavior, developed predictive models for future purchases, and uncovered distinct customer segments. The findings provide actionable insights that can guide marketing strategies, inventory planning, and customer retention efforts.

The analysis revealed that purchase frequency and brand affinity are key differentiators among customer segments, while there are significant opportunities to target specific age groups and capitalize on seasonal purchasing patterns.

---
