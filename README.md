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
x_val = [0,1,2,3,4,5]
y_val = [0,1,4,9,16,25]
plt.plot(x_val,y_val)
plt.show()
```

![325700663-7ea276da-329c-4e1b-af27-3ccbc2e158e8](https://github.com/user-attachments/assets/014d4218-80c9-4d25-9c77-a5e503519eff)
```
import matplotlib.pyplot as plt
x = [1,2,3]
y = [2,4,1]
plt.plot(x,y)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My first graph')
plt.show()
```
![325700892-53f92332-e90c-481d-b3db-b3a8b253211b](https://github.com/user-attachments/assets/e2b0d4e5-eea8-45f3-a2f4-30831a2c2733)
```
import matplotlib.pyplot as plt
x1 = [1,2,3]
y1 = [2,5,3]
plt.plot(x1,y1,label = 'line 1')
x2 = [1,2,3]
y2 = [3,1,6]
plt.plot(x2,y2,label = 'line 2')
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title("Two lines on the same graph")
plt.legend()
plt.show()
```
![325701123-2cc396f0-67ac-4526-9301-1126cb6eb146](https://github.com/user-attachments/assets/992ac100-fe98-42b4-bb2b-5ec5bc0459cf)

```
import matplotlib.pyplot as plt
import numpy as np
x = [1,2,3,4,5]
y1 = [10,12,14,16,18]
y2 = [5,7,9,11,13]
y3 = [2,4,6,8,10]
plt.fill_between(x,y1,color = 'blue')
plt.fill_between(x,y2,color = 'orange')
```
![325701443-12d2d32e-2a72-4864-aeec-89af7b2f681d](https://github.com/user-attachments/assets/cb071843-0c56-4e1b-803b-abb2dad69c8a)
```
plt.stackplot(x,y1,y2,y3,labels = ['line1','line2','line3'])
plt.legend(loc = 'upper left')
plt.title('Stacked line charts')
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.show()
```
![325701633-676db96f-5e9c-4ee4-a139-d42346831da8](https://github.com/user-attachments/assets/1ca99150-7829-4de6-b6e3-b6b6875ace31)
```
import numpy as np
import matplotlib.pyplot as plt
val = [2,4,7,3]
names = ['A','B','C','D']
plt.bar(names, val,color = 'purple')
plt.show()
```
![325701778-7d71481a-1aa6-4b57-a5af-95af9b12a4be](https://github.com/user-attachments/assets/598c927c-e7a2-4032-9b54-3573506bb102)
```
import matplotlib.pyplot as plt
import numpy as np
ages = [2,6,4,12,13,12,16,18,18,19,26,24,39,34,45,42,54,56,90,56,86,79]
range = (0,100)
bins = 10
plt.hist(ages,bins,range,color='green',histtype='bar',rwidth=0.8)
plt.xlabel('age')
plt.ylabel('no of people')
plt.title('histogram')
plt.show()
```
![325701999-5b088d34-b1ee-4b3e-a229-39360d583bf6](https://github.com/user-attachments/assets/2a5b0f29-3c92-48af-8599-150ac6ebe6d6)
```
import matplotlib.pyplot as plt
import numpy as np
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data
```
![325702341-d66d7f36-ff0d-41de-9fdd-1ebd34f79828](https://github.com/user-attachments/assets/70cba769-de61-4e41-b8e1-b815712f98e9)
```
fig,ax=plt.subplots()
ax.boxplot(data)
ax.set_xlabel("data")
ax.set_ylabel("values")
ax.set_title("box plot")
```
![325702521-4cdf0d14-c240-4e56-9ef1-ed0ac3eef7d2](https://github.com/user-attachments/assets/5029184f-4ec3-45d0-8730-90dd65d3f718)
```
import matplotlib.pyplot as plt
activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','y','g','b']
plt.pie(slices,labels = slices,colors=colors,startangle=90,shadow = True,explode = (0,0,0.1,0),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
```
![325702693-ddb35914-91b3-478a-81cf-f76e9cc9c071](https://github.com/user-attachments/assets/7137a01b-204d-4446-b56e-0c712adb28f7)








# Result:
 Thus, We have successfullu performed Data Visualization using matplot python library for the given datas.
