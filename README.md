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
Developed by: KISHORE N
REG NO. 212222240049
```
### 1. Read and display DataFrame
```
import pandas as pd
df = pd.read_csv("SAMPLEIDS.csv")
print(df)
```
![image](https://github.com/nkishore2210/exno1/assets/118707090/9252b42f-c9e4-4d1a-8ef4-700dd32597e0)

### 2. Display head
```
df.head(5)
```
![image](https://github.com/nkishore2210/exno1/assets/118707090/6fdfef9d-377a-4761-8f41-a96548c024e6)

### 3. Describe about the dataframe
```
df.describe()
```
![image](https://github.com/nkishore2210/exno1/assets/118707090/4a635a35-f428-4aa0-ac4d-fcef1aca1cd2)

### 4. Info of dataframe
```
df.info()
```
![image](https://github.com/nkishore2210/exno1/assets/118707090/b09bb04a-ee30-433c-ae69-b99ce4a22b96)

### 5. Display tail
```
df.tail()
```
![image](https://github.com/nkishore2210/exno1/assets/118707090/916aaa5b-a69e-4ae6-b964-f735176e4511)

### 6. Shape of the dataframe
```
df.shape
```
![image](https://github.com/nkishore2210/exno1/assets/118707090/b9f9d9c8-4e83-4021-8c46-7cbda12fbd94)

### 7. Checking tha Null values
```
df.isnull().sum()
```
![image](https://github.com/nkishore2210/exno1/assets/118707090/ac0fce99-0de8-4746-8796-d424d8250b26)

### 8. FIll the Null values
```
df.fillna(value=10)  
```
![image](https://github.com/nkishore2210/exno1/assets/118707090/a76ed1b8-b802-4ed5-bb98-a11f94df2bc6)

### 9. Fill value to null values
```
df.fillna(method='ffill')
```
![image](https://github.com/nkishore2210/exno1/assets/118707090/033a136d-933f-48aa-9804-a66db678b1c0)

## IQR METHOD:

![image](https://github.com/Ashwinkumar-03/exno1/assets/118663725/8ddf662f-4841-4d79-bfd6-a8a6cfc845ea)

![image](https://github.com/Ashwinkumar-03/exno1/assets/118663725/417d4ef4-fb53-4c46-9486-b152c898490c)

![image](https://github.com/Ashwinkumar-03/exno1/assets/118663725/123d5d45-acf7-40ca-a976-e7425539de05)

![image](https://github.com/Ashwinkumar-03/exno1/assets/118663725/10893ace-891f-4f41-b6e8-54df22531525)

![image](https://github.com/Ashwinkumar-03/exno1/assets/118663725/5aadd65e-5a98-4f34-abe9-54a7fdf2353d)

![image](https://github.com/Ashwinkumar-03/exno1/assets/118663725/43427525-4ffc-4886-a27f-b3c89c2ea0f3)

![image](https://github.com/Ashwinkumar-03/exno1/assets/118663725/e5476b21-c662-4f1c-ad79-9f0a08d768c5)

## Z-SCORE METHOD:

![image](https://github.com/Ashwinkumar-03/exno1/assets/118663725/e4cf2d42-f7b4-49dd-a80e-366a48786e5d)

![image](https://github.com/Ashwinkumar-03/exno1/assets/118663725/02b4980e-29fc-4939-9362-c68531cacbd3)

![image](https://github.com/Ashwinkumar-03/exno1/assets/118663725/3b6744c4-3f4a-488f-baa3-d57fe76b4683)

![image](https://github.com/Ashwinkumar-03/exno1/assets/118663725/dd967c3b-d963-49da-83f5-177a8ff999d5)

![image](https://github.com/Ashwinkumar-03/exno1/assets/118663725/050e8baa-2b68-4c5e-9270-80b098b8ecb7)

![image](https://github.com/Ashwinkumar-03/exno1/assets/118663725/2f869bfb-1cf8-41f4-ba05-6a8be2315538)

![image](https://github.com/Ashwinkumar-03/exno1/assets/118663725/573946b5-f540-4d27-8497-2666fefb8917)

# Result
The data cleaning has beeen done successfully.
