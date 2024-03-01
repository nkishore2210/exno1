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

Developed by: KISHORE N
REG NO. 212222240049

import pandas as pd
df=pd.read_csv('/content/SAMPLEIDS.csv')
df
![image](https://github.com/nkishore2210/exno1/assets/118707090/f21d42e5-6b29-4385-972d-59c63ba2565f)

df.head()
![image](https://github.com/nkishore2210/exno1/assets/118707090/0d7f3e26-b0b3-4e6b-b6af-4fb5559881b9)

df.tail()
![image](https://github.com/nkishore2210/exno1/assets/118707090/41063fc7-628b-4163-9bb7-ad03413d2817)

df.info()
![image](https://github.com/nkishore2210/exno1/assets/118707090/1a93abfb-c55e-4d22-9b34-f2a72ec88a7d)

df.describe()
![image](https://github.com/nkishore2210/exno1/assets/118707090/91a5d2c1-7119-4fb7-b5db-f599711c4cd5)

df.shape
![image](https://github.com/nkishore2210/exno1/assets/118707090/4c320c76-2428-4dac-bb9d-fe1c8bf0b9c9)

df.isnull()
![image](https://github.com/nkishore2210/exno1/assets/118707090/4e504c22-d322-4aad-a131-0b849b657927)

df.dropna(axis=0)
![image](https://github.com/nkishore2210/exno1/assets/118707090/224b5722-0bb1-4b5f-be35-d0c29a37d1a6)

df.fillna(0)
![image](https://github.com/nkishore2210/exno1/assets/118707090/60d87784-efe3-4da3-82f8-6c8004aa693a)

# Result
The data cleaning has beeen done successfully.
