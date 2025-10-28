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
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
```

```
marks = [13,45,63,78]
student = ['ABC','QDR','EFB','TOB']
plt.plot(marks,student)
plt.xlabel('Marks')
plt.ylabel('STudent Name')
plt.show()
```

<img width="714" height="486" alt="image" src="https://github.com/user-attachments/assets/01eb3d21-17db-4d25-9f64-2ffc1547381a" />

```
student=['A','B','C','D']
attendance = [76,90,98,87]
plt.plot(attendance, student)
plt.xlabel('Attendance')
plt.ylabel('Student Name')
plt.show()
```

<img width="642" height="485" alt="image" src="https://github.com/user-attachments/assets/9a8c7c42-352e-4797-b114-346816f10e01" />


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
plt.xlabel('X-Axis')
plt.ylabel('Y-Axis')
plt.title('Scatter Plot')
plt.show()
```

<img width="631" height="465" alt="image" src="https://github.com/user-attachments/assets/c37df82f-d911-4256-a5af-df9656325142" />


<img width="636" height="500" alt="image" src="https://github.com/user-attachments/assets/c42ae02f-1eba-47d6-82af-28ce5b0e72fa" />

```
act=['eat','sleep','work','play']
slices=[3,7,8,6]
color=['r','y','g','b']
plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%.1f%%')
plt.legend()
plt.show()
```

<img width="585" height="472" alt="image" src="https://github.com/user-attachments/assets/94365aa3-ada4-4cb6-903a-daa8d0b7c6f8" />

```
feedback=['Good','Excellent','Perfect','Ok']
slices=[4,10,3,8]
color=['y','r','b','g']
plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%.1f%%')
plt.legend()
plt.show()
```

<img width="506" height="443" alt="image" src="https://github.com/user-attachments/assets/fe61733a-c177-416a-a46c-860f1a739a2b" />

```
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

<img width="640" height="467" alt="image" src="https://github.com/user-attachments/assets/96942ea0-f003-4899-99d8-24384266a58d" />

```
 height = [10, 24, 36, 40, 5]
 names = ['one', 'two', 'three', 'four', 'five']
 c1=['yellow', 'blue']
c2=['b', 'g']
 plt.bar (names, height, width=0.8, color=c1)
 plt.xlabel('x - axis')
 plt.ylabel('y - axis')
 plt.title('My bar chart.')
 plt.show()
```

<img width="627" height="506" alt="Screenshot 2025-10-27 112226" src="https://github.com/user-attachments/assets/5c2063c0-f729-4805-b77c-e280aa07e03d" />

```
 x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
 plt.hist(x, bins = 10, color='orange', alpha=0.5)
 plt.show()
```

<img width="608" height="460" alt="image" src="https://github.com/user-attachments/assets/72e921be-fb30-45ff-8099-41e774306463" />

```
np.random.seed(0)
data=np.random.normal(loc=0, scale=1, size=100)
data
```

<img width="641" height="397" alt="image" src="https://github.com/user-attachments/assets/c1d8e36b-19bd-4146-b4fa-21ffb3945d8b" />

```
fig, ax= plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')
```

<img width="650" height="536" alt="image" src="https://github.com/user-attachments/assets/c6db867f-6061-4d99-a1ca-a755f2b3891c" />


# Result:
Thus , to perform data visualization using matplot python library for the given datas is successfully completed.
