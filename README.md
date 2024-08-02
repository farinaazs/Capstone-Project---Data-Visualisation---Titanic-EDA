# Titanic Data Visualisation and Exploratory Data Analysis (EDA)

### Overview

This project performs an exploratory data analysis (EDA) on the Titanic dataset to uncover patterns, correlations, and insights related to the survival rates of passengers. The dataset contains information about the passengers who were aboard the Titanic, including demographics, ticket class, and fare information.

### Contents
* titanic_eda.ipynb: The Jupyter Notebook file containing all the analysis and visualisations.
* Titanic.csv: The dataset used for this analysis.

### Installation
To run the notebook, you'll need to have Python installed along with the following libraries:

* python
  * pandas
  * seaborn
  * matplotlib

You can install these packages using pip:
* bash (Copy code)
  * pip install pandas seaborn matplotlib

### Usage
1. Clone this repository:

* bash (Copy code)
  * git clone https://github.com/farinaazs/Capstone-Project---Data-Visualisation---Titanic-EDA
  * cd titanic-eda

2. Ensure that the Titanic.csv file is in the same directory as the notebook.

3. Open the Jupyter Notebook:

* bash (Copy code)
  * jupyter notebook titanic_eda.ipynb

4. Run the cells to execute the EDA and visualise the data.

### Analysis Outline

1. Data Loading and Initial Exploration:

* Load the Titanic dataset.
* Check the dataset's shape, data types, and missing values.
* Drop unnecessary columns and handle missing data.

2. Exploratory Data Analysis (EDA):

* Calculate and visualise survival rates by different variables:
  * Sex
  * Age
  * Pclass
  * Embarked
  * Fare

* Cross-reference survival rates by combining different variables:
  * Sex and Pclass
  * Pclass and Age
  * Sex and Age
  * Fare and Pclass

* Explore multivariate relationships:
  * Survival by Sex vs. Pclass vs. Embarked
  * Correlation between Survived, Age, Pclass, and Fare
  * Survival by Sex vs. Pclass vs. Age vs. Fare

### Conclusion

The EDA provided insights into the survival patterns of Titanic passengers. Key findings include:

* Female passengers had a significantly higher survival rate than males.
* Higher ticket class was strongly associated with higher survival rates.
* Younger passengers, especially children, had higher survival rates.
* Passengers who paid higher fares generally had better survival chances.

### Tools Used
* Pandas: Excellent for data manipulation, handling missing values, and general data preprocessing. The library's robust functionality made it easy to clean and explore the dataset.

* Seaborn: A powerful library for data visualisation. Its high-level interface allows for easy creation of informative and aesthetically pleasing statistical graphics. The ability to combine plots and customise them was very useful in this analysis.

* Matplotlib: Used in conjunction with Seaborn, Matplotlib provided the underlying structure for visualisations. While Seaborn is more user-friendly, Matplotlib is necessary for fine-tuning and customising plots beyond Seaborn's default capabilities.

---------------------------------------------------------------------------------------------------------

#### My citings:

https://www.kaggle.com/code/demidova/titanic-eda-tutorial

https://www.kaggle.com/code/mjamilmoughal/eda-of-titanic-dataset-with-python-analysis

https://www.kaggle.com/code/kanncaa1/dataiteam-titanic-eda

https://www.kaggle.com/code/allohvk/titanic-advanced-eda

https://www.kaggle.com/code/mjamilmoughal/eda-of-titanic-dataset-with-python-analysis

https://www.w3schools.com/python/pandas/default.asp

##### Thank you, Farinaaz :)
