
***

# VIRTUAL BANKING SYSTEM

  

>  *This is a **VIRTUAL BANKING SYSTEM** using*

>

>+  **Java**

>

>+  **MySQL**

***

# Steps to Set-up this Project

>1.  **First U need to install [Java](https://www.java.com/download/ie_manual.jsp)**

>  2.  **U need to download [MySQL](https://www.mysql.com/downloads/)**

>  3.  **Open Mysql , Make your own Password for root dataBase (Note it in your notebook or computer)**

>  4.  **Open CMD or any terminal**

>  5.  **Go to the following file**

  
>
```
C:\Program Files\MySQL\MySQL Server 8.0\bin
```
>6.  **Open the file with terminal**

>  7.  **Enter Following code**

>
 ```
mysql -uroot -p
```
>

>8.  **Enter the password of Data base**

>9.  **Enter the following code || Copy/Paste it 😄**

>
```

create  database  name; // Any name of your own(Note it)

use  name;

CREATE  TABLE users

ADD COLUMN username VARCHAR(50) PRIMARY KEY,

ADD COLUMN password  VARCHAR(50) NOT NULL,

ADD COLUMN balance DOUBLE DEFAULT  0,

ADD COLUMN phone VARCHAR(15),

ADD COLUMN email VARCHAR(255),

ADD COLUMN gender ENUM('male', 'female', 'other'),

ADD COLUMN wlimit DOUBLE DEFAULT  1000.0;

CREATE  TABLE transactions

  (

  id INT AUTO_INCREMENT PRIMARY KEY,

  username VARCHAR(50) NOT NULL,

  date  TIMESTAMP  DEFAULT CURRENT_TIMESTAMP,

  description  VARCHAR(255),

  amount DOUBLE NOT NULL,

  balance DOUBLE NOT NULL

  );
```


>10.  **Open the all above files in code editor , Change the database name & Password**

  
  

***

  

# About

  

* This is like a online Banking System using java, sql. </br>

* Here first user have to have to create "**New Customer**" to create new account. </br>

*  *Signup Page* is opened , write the **Username , password , Phone , Email , gender** . </br>

* Now you can Withdraw Deposite, Transfer, Money ,Check Passbook ,etc . </br>

* U can access again using **Existing Customer**

* To access **Admin** username is *admin* & password is *pass* .

***
# Follow Me
Follow me on [LinkedIn](https://www.linkedin.com/in/mayur-narkhede-a17a07320/)

Give me a ⭐ if U like
  
***