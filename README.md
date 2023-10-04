# ODD2023-DataScience-Ex-03
## Aim:
To read the given data and perform the univariate analysis with different types of plots.

## Eplanation:
Univariate analysis is basically the simplest form to analyze data. Uni means one and this means that the data has only one kind of variable. The major reason for univariate analysis is to use the data to describe. The analysis will take data, summarise it, and then find some pattern in the data.

## Algorithm:
Step 1: Read the given data.
Step 2: Get the information about the data.
Step 3: Remove the null values from the data.
Step 4: Mention the datatypes from the data.
Step 5: Count the values from the data.
## Program:

Developed By : Naveenaa A.K
Register number: 212222230094
## Superstore.csv
```
import pandas as pd
import numpy as np
import seaborn as sns
df=pd.read_csv('SuperStore.csv')
print(df)
df.head()
df.info()
df.dtypes
df['Postal Code'].value_counts()
sns.boxplot(x='Postal Code', data=df)
sns.countplot(x='Postal Code',data=df)
sns.distplot(df["Postal Code"])
df.describe()
```
## Diabetes.csv
```
import pandas as pd
import numpy as np
import seaborn as sns
df = pd.read_csv("/diabetes.csv")
df
df.info()
df.isnull().sum()
df.dtypes
df.describe()
df['Glucose'].value_counts()
sns.boxplot(x="Glucose",data=df)
sns.countplot(x="Glucose",data=df)
sns.distplot(df['Glucose'])
sns.histplot(x="Glucose",data=df)
df.skew()
df.kurtosis()
```
## Output:
## Superstore.csv
![1](https://github.com/naveenaakumarasamy/ODD2023-DataScience-Ex-03/assets/113497406/7b7a5909-233a-4e0e-bb5e-b2b987864456)
![2](https://github.com/naveenaakumarasamy/ODD2023-DataScience-Ex-03/assets/113497406/e8e19269-1efb-4a35-89ec-bfa824ef58b1)
![3](https://github.com/naveenaakumarasamy/ODD2023-DataScience-Ex-03/assets/113497406/43173baf-b540-4b87-9be8-2b5f8e3aa986)
![4](https://github.com/naveenaakumarasamy/ODD2023-DataScience-Ex-03/assets/113497406/52bbff9f-a2e6-4c13-9107-0d10c23cc3c0)
![5](https://github.com/naveenaakumarasamy/ODD2023-DataScience-Ex-03/assets/113497406/358e0028-e0f9-4084-ae75-aae7a609a0ae)
![6](https://github.com/naveenaakumarasamy/ODD2023-DataScience-Ex-03/assets/113497406/9645c1f9-0538-4f57-ab61-183ae18e0d4f)
![7](https://github.com/naveenaakumarasamy/ODD2023-DataScience-Ex-03/assets/113497406/c31bdb26-4b8a-4cd6-b029-773e2880d5f1)
![8](https://github.com/naveenaakumarasamy/ODD2023-DataScience-Ex-03/assets/113497406/0cab88ff-299a-408b-8bd0-970d5ab61b0f)
![9](https://github.com/naveenaakumarasamy/ODD2023-DataScience-Ex-03/assets/113497406/7261e894-5f62-40fc-957a-5a5155bf5a25)
![10](https://github.com/naveenaakumarasamy/ODD2023-DataScience-Ex-03/assets/113497406/29edc1ca-f249-4182-8d79-efdc580b8615)
![11](https://github.com/naveenaakumarasamy/ODD2023-DataScience-Ex-03/assets/113497406/01b5ebc7-1aa6-41ef-9466-edaabd42fb61)
![12](https://github.com/naveenaakumarasamy/ODD2023-DataScience-Ex-03/assets/113497406/b4378997-05d0-4464-98e2-59e8876d6955)
![13](https://github.com/naveenaakumarasamy/ODD2023-DataScience-Ex-03/assets/113497406/1b83f734-9533-40ec-b615-c762ff148c2c)
![14](https://github.com/naveenaakumarasamy/ODD2023-DataScience-Ex-03/assets/113497406/940f851c-5e6d-4872-aa17-672159ff5f36)
![15](https://github.com/naveenaakumarasamy/ODD2023-DataScience-Ex-03/assets/113497406/776fc33a-5598-4bc6-ae00-fbb0e6440080)
![16](https://github.com/naveenaakumarasamy/ODD2023-DataScience-Ex-03/assets/113497406/31d2ac3b-1282-4601-b97f-3d8f01c1cd97)
![17](https://github.com/naveenaakumarasamy/ODD2023-DataScience-Ex-03/assets/113497406/b4a70e44-b1df-40f0-8528-cf72bb870dbd)
![18](https://github.com/naveenaakumarasamy/ODD2023-DataScience-Ex-03/assets/113497406/c8d14912-de21-4d34-9942-0e6048d2c7d3)
![19](https://github.com/naveenaakumarasamy/ODD2023-DataScience-Ex-03/assets/113497406/12123452-146c-4bdd-956a-8d94901e0c3d)
![20](https://github.com/naveenaakumarasamy/ODD2023-DataScience-Ex-03/assets/113497406/e3d33c98-db31-4b89-b8f6-0fa1b77770c1)
![21](https://github.com/naveenaakumarasamy/ODD2023-DataScience-Ex-03/assets/113497406/40ba7e3c-21de-497e-84be-2b2fbdfce39c)
## RESULT:
Hence the univariate analysis is verified.
