# sales-data-anyaysis-
here   we have calculate the revenue of the sales ,mean stander deviation,of the best saleing product and the least selling product  using numpy libarys 


import numpy as np
import pandas as pd
import matplotlib.pyplot as plt

df=pd.read_csv('/content/100 Sales Records.csv')
df


df.head()

df.columns

df['Item Type']

df.dropna()

df.fillna(0)

df['Total Revenue'].sum()

df['Item Type'].max()#top-sales
