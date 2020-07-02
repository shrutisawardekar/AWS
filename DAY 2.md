**Importing RDBMS data into HDFS using sqoop**

*Connect the RDS created on AWS cloud with the workbench using username,password and endpoint and create the database and use the query to load the text file in the database.*

![14](https://user-images.githubusercontent.com/44541800/86369158-adcbf880-bc9b-11ea-95ee-7146ff5d9083.png)


*Run the sqoop command for importing data from database to hdfs.*

![1](https://user-images.githubusercontent.com/44541800/86369269-d05e1180-bc9b-11ea-9c25-ad2a9c5502fb.png)


*Check whether the data is being imported using following command*

![2](https://user-images.githubusercontent.com/44541800/86369396-03a0a080-bc9c-11ea-8cd0-4539d775d28a.png)

![3](https://user-images.githubusercontent.com/44541800/86369347-ee2b7680-bc9b-11ea-8861-87189d516dc3.png)



*Run the column command to import salary and age columns.*

![4](https://user-images.githubusercontent.com/44541800/86369676-6bef8200-bc9c-11ea-8595-87b2c47879ea.png)



*Use the split command to split the data on baisi of columns and as an exception arises,  go to workbench make changes in the gender column by selecting collation as utf8mb4.*

![7](https://user-images.githubusercontent.com/44541800/86369746-7d388e80-bc9c-11ea-8709-2f4a083353bf.png)




*Run the below commands.*

![5](https://user-images.githubusercontent.com/44541800/86369687-6f830900-bc9c-11ea-9678-e6dac268b400.png)


![6](https://user-images.githubusercontent.com/44541800/86369741-7ad63480-bc9c-11ea-8f6f-f54f3aa32a15.png)




**Exporting HDFS data to RDBMS**

*Create a new directory using the below command.*

![8](https://user-images.githubusercontent.com/44541800/86369756-80cc1580-bc9c-11ea-9c26-9b82dfaa4e25.png)



*Put the data of the file in the new directory created(salarydata)*

![9](https://user-images.githubusercontent.com/44541800/86369779-86c1f680-bc9c-11ea-96c7-fdbda6d5203b.png)


*Check the data in the file.*

![10](https://user-images.githubusercontent.com/44541800/86369783-888bba00-bc9c-11ea-8025-596656e22d2f.png)


*Create a new table salaries 2 in workbench.*

![new table](https://user-images.githubusercontent.com/44541800/86375443-4d40b980-bca3-11ea-9060-efee6b382df1.png)



*Export the data using the sqoop command.*

![13](https://user-images.githubusercontent.com/44541800/86369803-8d506e00-bc9c-11ea-96e6-3c36ae287b5c.png)





*Verify the data on workbench exported using sqoop.*

![12](https://user-images.githubusercontent.com/44541800/86369796-8c1f4100-bc9c-11ea-93b7-1cca9c2f1d06.png)


