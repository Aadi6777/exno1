## NAME : Aadipranav S
# Exno:1
Data Cleaning Process

# AIM
To read the given data and perform data cleaning and save the cleaned data to a file.

# Explanation
Data cleaning is the process of preparing data for analysis by removing or modifying data that is incorrect ,incompleted , irrelevant , duplicated or improperly formatted. Data cleaning is not simply about erasing data ,but rather finding a way to maximize datasets accuracy without necessarily deleting the information.

# Algorithm
STEP 1: Read the given Data

STEP 2: Get the information about the data

STEP 3: Remove the null values from the data

STEP 4: Save the Clean data to the file

STEP 5: Remove outliers using IQR

STEP 6: Use zscore of to remove outliers

# Coding and Output
```
import pandas as pd
lab=pd.read_csv("/content/SAMPLEIDS.csv")
lab.head()
```
![image](https://github.com/user-attachments/assets/8d70d4bb-29f0-444a-a2c0-454764fdbc78)

            <<include your coding and its corressponding output screen shots here>>
# Result
          <<include your Result here>>
