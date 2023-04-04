# Ex-04-Multivariate-Analysis

import pandas as pd

df=pd.read_excel("/content/FlightInformation (1).xlsx")

df.head()

df.dtypes

import seaborn as sns

sns.scatterplot(x=df['Total_Stops'],y=df['Price'],data=df)

sns.barplot(x=df['Source'],y=df['Price'],data=df)

df.corr()

sns.heatmap(df.corr(),annot=True)

![work 1](https://user-images.githubusercontent.com/120440439/229771270-f83b8ace-9b0d-45a9-a4f9-46dfd65d81f7.png)

![work 2](https://user-images.githubusercontent.com/120440439/229771288-c603c341-8bfd-4d52-ba54-3d825e9d8445.png)

![work 3](https://user-images.githubusercontent.com/120440439/229771307-d363e6da-768a-4d22-acff-a17a7132f426.png)

![work 4](https://user-images.githubusercontent.com/120440439/229771325-07b65658-f194-48b4-88d2-fd907ac65ecd.png)

![work 5](https://user-images.githubusercontent.com/120440439/229771348-380a1e43-83a8-4fa5-9c5b-86faf61bce61.png)

