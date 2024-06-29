### Titanic Dataset Analysis
This project analyzes the famous Titanic dataset using Python and various data science libraries including pandas, numpy, matplotlib, and seaborn. The dataset contains information about passengers aboard the Titanic, including demographics and survival outcomes.

### Overview
The project begins by reading and exploring the dataset to understand its structure and contents. It includes basic statistical summaries such as mean, median, and quartiles for numerical features like age and fare.

### Data Visualization
Several visualizations are created to gain insights into the data:

- A stacked bar chart shows the distribution of survival status by sex.
- Line plots, bar plots, and box plots visualize relationships between survival and age.
- A heatmap of correlation coefficients reveals relationships among numerical features.

### Machine Learning Preparation
The dataset is prepared for machine learning tasks:

- Features such as PassengerId, Pclass, SibSp, Parch, and Fare are selected as predictors.
- Age is designated as the target variable for prediction.
- The dataset is split into training (80%), validation (10%), and test (10%) sets for model evaluation.

### Dependencies
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
