# Ex03-Univariate-Analysis

# Aim:
To read the given data and perform the univariate analysis with different types of plots.

# Explanation:
Univariate analysis is basically the simplest form to analyze data. Uni means one and this means that the data has only one kind of variable. The major reason for univariate analysis is to use the data to describe. The analysis will take data, summarise it, and then find some pattern in the data.

# Algorithm:
# Step1:
Read the given data.

# Step2:
Get the information about the data.

# Step3:
Remove the null values from the data.

# Step4:
Mention the datatypes from the data.

# Step5:
Count the values from the data.

# Step6:
Do plots like boxplots,countplot,distribution plot,histogram plot.

# Program:
DEVELOPED BY : NIROSHA.S

REGISTER NO : 212222230097
~~~py

import pandas as pd
import numpy as np
import seaborn as sns

df=pd.read_csv('superstore.csv')
df

df.head()
df.info()
df.describe()
df.isnull().sum()

df.dtypes

df['Postal Code'].value_counts()

sns.boxplot(x='Postal Code', data=df)
sns.countplot(x='Postal Code',data=df)
sns.distplot(df["Postal Code"])
sns.histplot(x='Postal Code',data=df)
~~~

# Output:

# SuperStore.csv:


Dataset:

![DS3 1](https://user-images.githubusercontent.com/121418437/229268586-385e9370-9507-43f0-8f90-9efaf66360cd.PNG)

Head:

![DS3 2](https://user-images.githubusercontent.com/121418437/229268866-b6d05025-fba8-42e5-bd70-b86877762a51.PNG)

Info:

![DS3 3](https://user-images.githubusercontent.com/121418437/229268886-1f2b814c-e8f4-4659-a86f-b4acbd401409.PNG)

Describe:

![DS3 4](https://user-images.githubusercontent.com/121418437/229268902-91859536-29ce-4a86-8176-24f7496cd29a.PNG)

Isnull:

![DS3 5](https://user-images.githubusercontent.com/121418437/229268918-c0f53c7e-a55e-4a43-9974-b06cabb99a29.PNG)

dtypes:

![DS3 6](https://user-images.githubusercontent.com/121418437/229268929-c704e3c7-06ab-45cd-8ae7-fe82ab585c0c.PNG)

Valuecount:

![DS3 7](https://user-images.githubusercontent.com/121418437/229268942-a2a093ff-1b0d-4479-8bfd-043ffb968d38.PNG)

Boxplot:

![DS3 8](https://user-images.githubusercontent.com/121418437/229268953-bb240f96-4aae-4d0e-976a-88960df72ac8.PNG)

Countplot:

![DS3 9](https://user-images.githubusercontent.com/121418437/229268963-3a0341af-3cee-4bbb-b1b6-566e3099c449.PNG)

Distribution plot:

![DS3 10](https://user-images.githubusercontent.com/121418437/229268986-b8a2aaed-2069-4b07-8f71-bcc13b3df1fd.PNG)

Histogram plot:

![DS3 11](https://user-images.githubusercontent.com/121418437/229269004-91cac9b9-11b6-4fce-927d-2ebe4b6e9f7a.PNG)


# diabetes.csv:

Dataset:

![DS3 12](https://user-images.githubusercontent.com/121418437/229269017-95cdd05a-39a0-4eec-a6ab-f61268275439.PNG)

Head:

![DS3 13](https://user-images.githubusercontent.com/121418437/229269037-f55b2340-130a-41f5-b42d-3fe939789777.PNG)

Info:

![DS3 14](https://user-images.githubusercontent.com/121418437/229269056-b1a743d9-ca64-41ee-882f-9024c0fbd01d.PNG)

Describe:

![DS3 15](https://user-images.githubusercontent.com/121418437/229269072-a132d6f1-42eb-42c4-a6a3-f70ce3129eb6.PNG)

Isnull:

![DS3 16](https://user-images.githubusercontent.com/121418437/229269081-ae7054af-3090-493b-a590-142c22a1d87b.PNG)

dtypes:

![DS3 17](https://user-images.githubusercontent.com/121418437/229269094-4e318ecc-b198-4408-b95c-9e95dd407fe9.PNG)

Valuecount:

![DS3 19](https://user-images.githubusercontent.com/121418437/229269108-615e2e1e-cdff-4c59-988f-2b821575954e.PNG)

Boxplot:

![DS3 18](https://user-images.githubusercontent.com/121418437/229269147-3ab428f6-a794-4bae-a1ac-25700fa4d5af.PNG)

Countplot:

![DS3 20](https://user-images.githubusercontent.com/121418437/229269155-6c1770a4-66af-45ef-8a2b-80267b282af2.PNG)

Distribution plot:

![DS3 21](https://user-images.githubusercontent.com/121418437/229269170-82e1f2a2-5d57-477d-bf1a-5a50f2e4965b.PNG)

Histogram plot:

![DS3 22](https://user-images.githubusercontent.com/121418437/229269194-04bcb56d-cc88-4dcc-bf72-9fdd2eab7496.PNG)

# Result:

    Thus we have read the given data and performed the univariate analysis with different types of plots.

