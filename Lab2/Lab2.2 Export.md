# LAB 3.2 -> Exporting HDFS Data to an RDBMS

***Objective -> Export data from HDFS into a MySQL table using Sqoop.***

***Pre-requisites -> Hadoop cluster on EMR should be up and running***

Following are the steps to be performed in this lab:-

1. Create a new hdfs directory using mkdir command with name salarydata

![dfs-mkdir](https://github.com/nileshsingal/BigData/blob/master/images/3.2/1.png)

2. Put salarydata.txt into the salarydata directory in HDFS
3. Check whether the file is created on hdfs

![ls](https://github.com/nileshsingal/BigData/blob/master/images/3.2/2.png)


4. Create a new Table in the Database as salaries2 using following sql command


![table](https://github.com/nileshsingal/BigData/blob/master/images/3.2/3.png)

5. Now export data from hdfs to database

![sqoop](https://github.com/nileshsingal/BigData/blob/master/images/3.2/4.png)

6. Verify whether all records are been exported successfully

![verify-export](https://github.com/nileshsingal/BigData/blob/master/images/3.2/5.png)



***Result -> You have now used Sqoop to export data from HDFS into a database table in MySQL.***
