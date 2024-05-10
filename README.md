# EX.NO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

## Aim:
  To Perform Data Visualization using matplot python library for the given datas.

## EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

## Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

## Coding and Output:
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
![image](https://github.com/22008837/EXNO-5-DS/assets/120194155/f0e72d66-9846-4020-8b1c-884e0ab73398)
![image](https://github.com/22008837/EXNO-5-DS/assets/120194155/458331cc-1372-4d47-b157-6ed0f4f49a76)
```
BAR GRAPH

x=[10,20,30,40,50]
names=['A','B','C','D','E']
plt.bar(x,y,color='blue')
plt.show()

x=[14,30,25,6,20]
names=['A','B','C','D','E']
plt.bar(x,y,color='blue')
plt.show()
```
![image](https://github.com/22008837/EXNO-5-DS/assets/120194155/9c25658c-df30-4110-9938-ab266eb7d65d)
![image](https://github.com/22008837/EXNO-5-DS/assets/120194155/76efd34f-33e5-461f-82d5-bc764fc9c2ff)
```
SCATTER PLOT

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
![image](https://github.com/22008837/EXNO-5-DS/assets/120194155/4d32e95a-3ac2-4294-8787-81a9bc696fba)
![image](https://github.com/22008837/EXNO-5-DS/assets/120194155/a729d89b-d178-49fb-86d8-e8b1e0d90e08)
```
HISTOGRAM

ages=[2,5,70,40,30,45,50,45,43,40]
range=(0,80)
bin=10
plt.hist(ages,bin,range,color='green',histtype='bar',rwidht=0.8)
plt.xlabel('ages')
plt.ylabel('No of people')
plt.legend()
plt.title('Histogram')
plt.show()

x=[2,1,6,4,2,4,8,9,4,2,10]
plt.hist(x,bins=10,color='blue',alpha=0.5)
plt.show()
```
![image](https://github.com/22008837/EXNO-5-DS/assets/120194155/6806175c-95e9-4889-8d05-8412ac2dbafa)
![image](https://github.com/22008837/EXNO-5-DS/assets/120194155/8a6d4409-4aa1-41ed-8979-914376d11bbe)
```
PIE CHART

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
![image](https://github.com/22008837/EXNO-5-DS/assets/120194155/d14a3731-63f9-4400-9ab4-41fe112f6514)
![image](https://github.com/22008837/EXNO-5-DS/assets/120194155/41f901a6-3d0e-4025-b4c2-e023b1e46814)


## Result:
Thus, all the data visualization techniques of matplotlib has been implemented.
