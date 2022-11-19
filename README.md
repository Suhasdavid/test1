import numpy as np 
import pandas as pd 
import matplotlib 
import matplotlib.pyplot as plt
import seaborn as sns


df =pd.read_csv('mtcars.csv')
df



a=df.mpg
b=df.drat
sns.boxplot(df['mpg'])
x=df.wt
y=df.mpg
plt.xlabel('Weight')
plt.ylabel('Mpg')
plt.title('scater plot')
plt.scatter(x,y)
a=df.mpg
b=df.model
plt.xlabel('TRANSMISSION TYPE')
plt.ylabel('MODEL')
plt.title('bar graph')
plt.bar(a,b,color ='red',edgecolor='black', )
