1.	Histogram: Distribution of Wine Quality Ratings

import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt

# Simulating the loading of a dataset similar to "Wine Quality"
# For the purpose of this example, we'll create a small sample DataFrame that represents the structure and type of data

data = {


    'fixed_acidity': np.random.normal(8.0, 2.0, 100),
    'volatile_acidity': np.random.normal(0.5, 0.1, 100),
    'citric_acid': np.random.uniform(0, 1, 100),
    'residual_sugar': np.random.normal(5.0, 4.5, 100),
    'chlorides': np.random.normal(0.08, 0.02, 100),
    'free_sulfur_dioxide': np.random.normal(15, 10, 100),
    'total_sulfur_dioxide': np.random.normal(46, 32, 100),
    'density': np.random.normal(0.996, 0.002, 100),
    'pH': np.random.normal(3.3, 0.15, 100),
    'sulphates': np.random.normal(0.65, 0.15, 100),
    'alcohol': np.random.normal(10.5, 1.2, 100),
    'quality': np.random.randint(3, 9, 100)
}

df = pd.DataFrame(data)

df.describe()

2.	Scatter Plot: Relationship between Alcohol Content and Wine Quality

import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt


plt.figure(figsize=(10, 6))
sns.scatterplot(x='alcohol', y='quality', data=df)
plt.title('Relationship between Alcohol Content and Wine Quality')
plt.xlabel('Alcohol Content (%)')
plt.ylabel('Quality Rating')
plt.grid(True)
plt.show()

3.	 Box Plot: Distribution of Alcohol Content by Wine Quality
plt.figure(figsize=(10, 6))
sns.boxplot(x='quality', y='alcohol', data=df)
plt.title('Distribution of Alcohol Content by Wine Quality')
plt.xlabel('Quality Rating')
plt.ylabel('Alcohol Content (%)')
plt.grid(True)
plt.show()

4.	Heatmap: Correlation Matrix of Wine Properties
plt.figure(figsize=(12, 8))
sns.heatmap(df.corr(), annot=True, cmap='coolwarm', fmt=".2f")
plt.title('Correlation Matrix of Wine Properties')
plt.show()


