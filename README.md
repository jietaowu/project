
# 
```
mysql> CREATE DATABASE SQL_Learning;
Query OK, 1 row affected (0.01 sec)

```

```
mysql> USE SQL_Learning;
Database changed

mysql> CREATE TABLE Vendors
    -> (
    ->   vend_id      char(10) NOT NULL ,
    ->   vend_name    char(50) NOT NULL ,
    ->   vend_address char(50) NULL ,
    ->   vend_city    char(50) NULL ,
    ->   vend_state   char(5)  NULL ,
    ->   vend_zip     char(10) NULL ,
    ->   vend_country char(50) NULL
    -> );
Query OK, 0 rows affected (0.08 sec)

```
