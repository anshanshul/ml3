# ml3
import numpy as n
import pandas as p
import matplotlib.pyplot as plt
data=p.read_csv(r'C:\Users\hmr\Desktop\wine_dataset.csv')
print(data)
a=data.values
x=a[:,0:12]
print(x)
plt.hist(x)
plt.show()
print(data.columns)
print(data['Alcohol'])
plt.hist(data['Alcohol'])
print(data['Malic acid'])
plt.hist(data['Malic acid'])
print(data['Ash'])
plt.hist(data['Ash'])
print(data['Alcalinity of ash'])
plt.hist(data['Alcalinity of ash'])
print(data['Magnesium'])
plt.hist(data['Magnesium'])
print(data['Total phenols'])
plt.hist(data['Total phenols'])
print(data['Flavanoids'])
plt.hist(data['Flavanoids'])
print(data['Nonflavanoid phenols'])
plt.hist(data['Nonflavanoid phenols'])
print(data['Proanthocyanins'])
plt.hist(data['Proanthocyanins'])
print(data['Color intensity'])
plt.hist(data['Color intensity'])
print(data['Hue'])
plt.hist(data['Hue'])
print(data['OD280/OD315 of diluted wines'])
plt.hist(data['OD280/OD315 of diluted wines'])

print(data['Proline'])
plt.hist(data['Proline'])

print(data['Wine Type'])
plt.hist(data['Wine Type'])

new_data=n.array(data)

print(new_data[0])
plt.show()
