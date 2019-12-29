# Introduction
This is a task from Google Code-In.
Here you learn how to read and write a csv data.

# Requirements
- R
- RStudio
- (Atom)

# Code Description
```
#Task1

#Reading and writing CSV Data

#Create a CSV File called test.csv 
Ex.
ID, Name
1, Mridul
2, Srishti
3, Ruchi
4, Ankur
5, Guruji

#Read a CSV file from your local computer along with its headers and convert it into a data frame.
T1=read.csv(file.choose(), header = TRUE)

#Create a new data frame "student" in R with at least 5 observations and 3 variables, name, age and class.
student=data.frame(name=c("Mridul","Srishti","Ruchi","Ankur","Krishna"), 
              age=c(11,16,40,42,25), 
              class=c("2M1","2M2","2M3","2M4","2M5")) 

#Add a new column height into the data frame and then add a new row into the data frame.
student$height=c(100,150,180,160,165)
T2=data.frame(name=c("Guruji"), 
              age=c(63), class=c("2M6"), height=c(165)) 
students=rbind(student,T3)

#Export the data frame into a CSV file students.csv.
write.csv(T4,"C:\\Users\\srish\\Desktop\\students.csv")

#Read a CSV file from the internet directly into R without downloading the file manually.
X = read.csv("https://archive.ics.uci.edu/ml/machine-learning-databases/iris/iris.data", header = FALSE)
```
# Screen Cast
![Record]()

# Authors
- Mridul
