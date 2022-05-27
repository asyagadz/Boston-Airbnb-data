# Boston-Airbnb-data
This is the dataset I choose for the first project in the Data Science Nanodegree. Data is available here: https://www.kaggle.com/datasets/airbnb/boston
The purpose of the project is to choose a dataset and choose 3 questions to answer from the data chosen.

## Installations
cycler==0.10.0
feature_engine==1.2.0
joblib==1.1.0
matplotlib==3.4.3
nltk==3.6.5
numpy==1.20.3
pandas==1.3.4
regex==2021.8.3
scikit_learn==1.1.1
scipy==1.7.1
seaborn==0.11.2
spacy==3.2.1
textacy==0.11.0
wordcloud==1.8.1
For reference - there is a requirements.txt file in the main project.


## Project Motivation
This project is the first project from Udacity's Data Science Nanodegree  - the Introduction to Data Science. 
I have defined the following three questions to answer:
1. When are the busiest times in Boston? 
2. Which are the most crowded neighbourhoods in Boston in terms of AirBNB listings?
3. What drives/defines the prices of the AirBNB in Boston? Which are the top variables that affect the price? 


## File Descriptions
The project contains:
- A Readme.md file
- Notebook folder
  - 01.01.-ag-initial-analysis.ipynb - I explore the raw data files as downloaded from Kaggle
  - 02.01.-ag-data-cleaning.ipynb - drop irrelevant features and add new features
  - 02.02.-ag-data-cleaning-feature-engineering-description.ipynb - explore the Description field from listings dataset - transform and vectorize data in order to find meaningful insights; it is a complementary notebook
  - 02.03.-ag-data-cleaning-feature-engineering-other-text-columns.ipynb - explore other text columns from listings data; it is a complementary notebook
  - 03.01.-ag-feature-engineering.ipynb - this notebook contains all imputings of missing values, additional transformations of features, binning, discretization, outliers handling
  - 04.01.-ag-feature-selection-modelling-price-prediction.ipynb - this notebook contains the modelling part performed and chosen for question 3.
  - 05.01.-ag-exploratory-data-analysis.ipynb - this notebook contains the descriptive and visualisation analysis that provides answers to the three questions to the dataset.
- src folder:
  - data:
    - raw data - the raw files as downloaded from Kaggle
    - processed data - the files processed throughtout the different steps of the project.


## How to Interact with your project/Results
TBased on the analysis performed, we have seen some interesting information about the AirBNBs in Boston:

- beginning of Autumn is the busiest period for the airBNBs occupancy rates
- there are neighbourhoods that reveal a capacity for new AirBNBs.
- a more precise modelling and data mining is necessary to build more robust model, that explains better what affect the prices and its values.

The blog post for the analysis can be found here: https://medium.com/@asya.gadz/a-study-on-airbnb-boston-data-410940343dd8

## Licensing, Authors, Acknowledgements, etc.
I have used some functions or code that is from Feature Engineering course & Feature Selection course from Udemy, lead by Soledad Galli.
