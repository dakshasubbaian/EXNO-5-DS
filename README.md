# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:
 ```
import matplotlib.pyplot as plt
x1=[1,2,3]
y1=[2,4,1]
plt.plot(x1,y1,label='line1')
x2=[1,2,3]
y2=[4,1,3]
plt.plot(x2,y2,label='line2')
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Two lines on same graph!')
plt.legend()
plt.show()
```
![image](https://github.com/Aaron-0111/EXNO-5-DS/assets/149347631/69c6383e-99f5-43c5-aa51-86dba3704924)


```
import matplotlib.pyplot as plt
x=[1,2,3,4,5,6]
y=[2,4,1,5,2,6]
plt.plot(x,y,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='blue',markersize=12)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Some cool customizations!')
plt.show()
```
![image](https://github.com/Aaron-0111/EXNO-5-DS/assets/149347631/fb64ac21-a1a7-484e-a4b6-425311ed49ae)

```
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(yield_apples)
```
![image](https://github.com/Aaron-0111/EXNO-5-DS/assets/149347631/30ebd91b-ec0c-47dc-928d-050542017f9c)

```
years=[2010,2011,2012,2013,2014,2015]
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yield_apples)
```
![image](https://github.com/Aaron-0111/EXNO-5-DS/assets/149347631/843c5efe-aeba-4643-8089-f58c99ea6e8c)

```
years=range(2000,2012)
apples=[0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
oranges=[0.926,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896, ]
plt.plot(years, apples)
plt.plot(years, oranges)
plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare)')
plt.title('Crop Yields in Kanto')
plt.legend(['Apples','Oranges']);
```
![image](https://github.com/Aaron-0111/EXNO-5-DS/assets/149347631/0c79a361-26ab-4978-8531-d0a08fab0ca5)

```
plt.figure(figsize=(12,6))
plt.plot(years,oranges,marker='o')
plt.title("Yield of Oranges (tons per hectare)");
```
![image](https://github.com/Aaron-0111/EXNO-5-DS/assets/149347631/589e1264-9426-4e52-a9ae-1c504f4a0f88)

```
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
x=np.arange(0,10)
y=np.arange(11,21)
x
```
![image](https://github.com/Aaron-0111/EXNO-5-DS/assets/149347631/118407ac-0f1d-4d01-bd3a-0be14280edb6)

```
y
```
![image](https://github.com/Aaron-0111/EXNO-5-DS/assets/149347631/e4f603e5-100c-49a0-9ca9-1ff6d7d5d3eb)

```
plt.scatter(x,y,c='r')
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.title('Graph in 2D')
plt.savefig('Test.png')
```
![image](https://github.com/Aaron-0111/EXNO-5-DS/assets/149347631/5b078a15-dc9e-4456-9b71-e3cc29803981)

```
y=x*x
y
```
![image](https://github.com/Aaron-0111/EXNO-5-DS/assets/149347631/b1d93fa1-94c3-4b11-8dcd-e0a16b9e206c)

```
plt.plot(x,y,'g*',linestyle='dashed',linewidth=2,markersize=12)
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('2d Diagram')
```
![image](https://github.com/Aaron-0111/EXNO-5-DS/assets/149347631/a3a8e245-25dd-4162-8c38-892b3877c17c)

```
np.pi
```
![image](https://github.com/Aaron-0111/EXNO-5-DS/assets/149347631/3b8f0d68-94f6-4907-889b-65b2f19a06d1)

```
x=np.arange(0,4*np.pi,0.1)
y=np.sin(x)
plt.title("sine wave form")
plt.plot(x,y)
plt.show()
```
![image](https://github.com/Aaron-0111/EXNO-5-DS/assets/149347631/882ff1ec-06a8-41b8-a973-6a58db0c359f)

```
import matplotlib.pyplot as plt
import numpy as np
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color='blue')
plt.fill_between(x,y2,color='green')
```
![image](https://github.com/Aaron-0111/EXNO-5-DS/assets/149347631/cd93631d-e1ec-4f0d-b393-279953b2bd67)

```
import matplotlib.pyplot as plt
import numpy as np
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color='blue')
plt.fill_between(x,y2,color='green')

plt.plot(x,y1,color='red')
plt.plot(x,y2,color='black')
plt.legend(['y1','y2'])
plt.show()
```
![image](https://github.com/Aaron-0111/EXNO-5-DS/assets/149347631/c2687412-0627-494f-940e-6c27ec58c3d2)

```
import matplotlib.pyplot as plt
height=[10,24,36,40,5]
names=['one','two','three','four','five']
c1=['red','green']
c2=['b','g']
plt.bar(names,height,width=0.8,color=c1)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My bar chart!')
plt.show()
```
![image](https://github.com/Aaron-0111/EXNO-5-DS/assets/149347631/f84d9b93-bb7c-4afd-8472-d796b0ce0498)

```
x=[2,8,10]
y=[11,16,9]
x2=[3,9,11]
y2=[6,15,7]
plt.bar(x,y,color='r')
plt.bar(x2,y2,color='g')
plt.title('Bar graph')
plt.ylabel('Y axis')
plt.xlabel('X axis')
plt.show()
```
![image](https://github.com/Aaron-0111/EXNO-5-DS/assets/149347631/596ac2d7-ceed-4d03-9474-418e6e104367)

```
import matplotlib.pyplot as plt
ages=[2,5,70,40,30,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40]
range=(0,100)
bins=10
plt.hist(ages,bins,range,color='green',histtype='bar',rwidth=0.8)
plt.xlabel('age')
plt.ylabel('No. of people')
plt.title('My histogram')
plt.show()
```
![image](https://github.com/Aaron-0111/EXNO-5-DS/assets/149347631/aeda23bd-1a9e-4022-97b3-b4eb26a020b9)

```
import matplotlib.pyplot as plt
import numpy as np
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data
```
![image](https://github.com/Aaron-0111/EXNO-5-DS/assets/149347631/1e18e3be-98d4-42af-83a0-c91400229db2)

```
fig,ax=plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')
```
![image](https://github.com/Aaron-0111/EXNO-5-DS/assets/149347631/dc5ce2f7-5b16-45c4-b605-a8284cd4793e)

```
labels='Python','C++','Ruby','Java'
sizes=[215,130,245,210]
colors=['gold','yellowgreen','lightcoral','lightskyblue']
explode=(0,0.4,0,0.5)
plt.pie(sizes,explode=explode,labels=labels,colors=colors,autopct='%1.1f%%',shadow=True)
plt.axis('equal')
plt.show()
```
![image](https://github.com/Aaron-0111/EXNO-5-DS/assets/149347631/66e37ab8-a865-4e01-9dbe-5b7c19f0d03f)

```
activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','y','g','b']
plt.pie(slices,labels=activities,colors=colors,startangle=90,shadow=True,explode=(0,0,0.1,0),radius=1.2,autopct='%1.1f%%')
plt.legend()
```

![image](https://github.com/Aaron-0111/EXNO-5-DS/assets/149347631/995b0d9f-2622-483a-98fa-ca48ce6d2d81)

# Result:

Thus, The implementation of data visualization using matplotlib has been successfully verified.

