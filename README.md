# Spring3HibernateExample

Configuration Spring 3 and hibernate 3 CURD databases
-------------------------------------------------------


### STEP 1
    create your database in mysql 

    # bash init_databases.sh

### STEP 2
    open your eclipse and import maven project (Sprint3HibernateExample) and run App.java
    you will see like this

    Hibernate: insert into stock1.stock (STOCK_CODE, STOCK_NAME) values (?, ?)
    Hibernate: select stock0_.STOCK_ID as STOCK1_0_, stock0_.STOCK_CODE as STOCK2_0_, stock0_.STOCK_NAME as STOCK3_0_ from stock1.stock stock0_ where stock0_.STOCK_CODE=?
    Stock [stockCode=7668, stockId=3, stockName=HAIO]
    Hibernate: update stock1.stock set STOCK_CODE=?, STOCK_NAME=? where STOCK_ID=?
    Hibernate: delete from stock1.stock where STOCK_ID=?
    Done

