# Data-Cleaning-techniques-with-different-ML-Models-DA
 
- In this Task, we will apply data cleaning on a given Airbnb data set.

- This dataset (raw.csv) contains 30k+ records on hotels in the top-10 tourist destinations and major US metropolitan areas sraped from Airbnb.com. Each data record has 40 attributes including the number of bedrooms, price, location, etc. The attribute "pop2016" means population of the zipcode location (area) in year 2016. Demographic and economic attributes were scraped from city-data.com.

### House specific features, collected from Airbnb.com:
 - Bathrooms: The number of bathrooms in the listing Bedrooms: The number of bedrooms Beds: The number of bed(s) LocationName: Location of the house NumGuests: Maximum number of guests can hold NumReviews: number of reviews received Price: daily price in local currency
 
#### Task 1: Read dataset and perform basic data exploration. Specially, you should write code to explore the types of data provided

#### Task 2: Data quality check, does duplicate entries exit in this table? Do they have consistent values? Briefely explain your methodology and your findings within this markdown cell, and write corresponding code in the next code cell.

#### Task 3: Data quality check
  3.1 does missing value exit in the table?
  3.2 Where are the missing data?
  3.3 How much data is missing?
  3.4 Are there any variables often missing together？
 
#### Task 4: What are the potential mechnisms of the missing values? Briefely explain your methodology and your findings (within this markdown cell), and write corresponding code in the next code cell.

#### Task 5: Handling missing values, Briefely explain your methodology below (within this markdown cell), and write corresponding code in the next code cell.

#### Task 6: Impact on classification performance. Consider one of the above handling method you proposed for this dataset and perform classification tast to investigate if your handling method can improve classificaiton performance. Train-test split: you can do one split of train and test where 70% of the data for training and the remaining 30% for testing. Classifier: you can pick any two tranditional binary classifier (e.g., from sklearn)

#### Task 7: Report your findings through the above experiments (in this markdown cell)


### Training Models:
 - Logistic Regression
 - SVM
 - Decision Tree
 - XGBClassifier
 - AdaBoostClassifier
