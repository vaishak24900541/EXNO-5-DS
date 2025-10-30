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
### Name: Vaishak M
### Reg.No: 212224040355
```
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
```
# Line Plot:
```
marks=[13,45,63,78]
student=['ABC','QOR','EFB','TOB']
plt.plot(marks,student)
plt.xlabel('Marks')
plt.ylabel('Student name')
plt.show()
student=['A','B','C','D']
attendence=[90,85,73,88]
plt.plot(attendence,student)
plt.xlabel('Attendence')
plt.ylabel('Student name')
plt.show()
```

<img width="784" height="559" alt="image" src="https://github.com/user-attachments/assets/ed56fb86-5304-4c04-855e-defff2bf67c9" />
<img width="774" height="551" alt="image" src="https://github.com/user-attachments/assets/da0cda73-6c9e-4b7d-8b53-f023c49db9a8" />

# Scatter Plot:
```
x=[10,20,30,40,50]
y=[100,200,300,400,500]
plt.scatter(x,y,label='stars',color='green',marker='*',s=30)
plt.show()
x=np.arange(0,15)
y=np.arange(0,15)
x
y
plt.scatter(x,y,c='r')
plt.xlabel('X axis')
plt.ylabel('y axis')
plt.title('Scatter plot')
plt.show()
```

<img width="757" height="544" alt="image" src="https://github.com/user-attachments/assets/dcfdb70a-22e0-483e-8564-270fc17a28d5" />
<img width="732" height="590" alt="image" src="https://github.com/user-attachments/assets/021119ca-de52-4028-ac28-9a29a088857b" />

# Pie Chart:
```
act=['eat','sleep','work','play']
slices=[3,7,8,6]
color=['r','y','g','b']
plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
feedback=['Good','excellent','Perfect','Ok']
slices=[4,10,3,8]
color=['y','r','b','g']
plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
```

<img width="679" height="531" alt="image" src="https://github.com/user-attachments/assets/f5591c10-edc9-4101-b155-b66656512a62" />
<img width="650" height="512" alt="image" src="https://github.com/user-attachments/assets/772baad8-aa45-4bf1-99bf-0b5bf12874bc" />

# Area Chart:
```
x = [1, 2, 3, 4, 5]
y1 = [10, 12, 14, 16, 18]
y2 = [5, 7, 9, 11, 13]
y3 = [2, 4, 6, 8, 10]
plt.fill_between(x, y1, color='blue')
plt.fill_between(x, y2, color='green')
plt.plot(x, y1, color='red')
plt.plot(x, y2, color='black')
plt.legend(['y1','y2'])
plt.show()
```

<img width="809" height="536" alt="image" src="https://github.com/user-attachments/assets/55cf8a2b-382c-4e19-8040-53fd3cb7dc9e" />

# Bar Chart:
```
height = [10, 24, 36, 40, 5]
names = ['one', 'two', 'three', 'four', 'five']
c1=['red', 'green'] 
c2=['b', 'g']
plt.bar (names, height, width=0.8, color=c1)
plt.xlabel('x - axis')
plt.ylabel('y - axis')
plt.title('My bar chart!')
plt.show()
```

<img width="763" height="577" alt="image" src="https://github.com/user-attachments/assets/298030e1-65e2-4153-a618-4ca398a47f10" />

# Histogram:
```
x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x, bins = 10, color='blue', alpha=0.5)
plt.show()
```

<img width="769" height="520" alt="image" src="https://github.com/user-attachments/assets/fcd8180c-a05c-4fa5-ab02-0b30243ca5f5" />

# Box Plot:
```
np.random.seed(0)
data=np.random.normal(loc=0, scale=1, size=100)
data
fig, ax= plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')
```

<img width="820" height="597" alt="image" src="https://github.com/user-attachments/assets/7c35bf7c-7797-4979-8ec5-2f30d8e900e4" />

# Result:

Thus, all the data visualization techniques of matplotlib has been implemented.
