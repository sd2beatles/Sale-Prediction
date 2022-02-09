# Sale-Prediction (Ranked 4th)


## :globe_with_meridians: Introduction 



In this competition I was working with a challenging time-series dataset consisting of daily sales data, kindly provided by stores in Koarea. To predict total sales for every product and store in the next month. By solving this competition I was able to apply and enhance your data science skills. I was ranked 4th in the competition. 

### According to the discolsure agreement, a full discolue of contents is forbidden. Therefore, beacuse I have excluded all the private infomration on the clients,the dimension of transformed data is much smaller than that of the original data




## :globe_with_meridians: Steps

- Part 1: Collection of Data From  API
  - Creating a database and tables for data storage
  - Choosing one of the two given formats; 
    - Pandas DataFrame (python3)
    - MySQL 

- Part 2: Build up Amazon Web Services RDS 
  - Connecting to a DB instance running the MySQL databse engine

- Part 3: Modeling
  Light GBM has shown the good performance. 
  


## :globe_with_meridians: Special Notes

:pencil2:  _AWD RDS(Amazon Relational Database Service)_

In order to connect to Database instance, we need to first obtain an endpoint and port value from the AWS Management Console. 
Right after acquisition of the information, we are now able to connect to a DB instance using MySQL client by typing the below command line. 

```sql
mysql -h endpoint -P port_number -u masteruser -p
```

