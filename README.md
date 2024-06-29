# practice2_report


* ```ls -lh датафайлы```  
  
![img_1.png](img_1.png)

* ```ls -lh файлы параметров```  
  
![img.png](img.png)

* ```ls -lh управляющие файлы```  

![img_2.png](img_2.png)

* ```ls -lh alert-лог```  

![img_4.png](img_4.png)

* ```lsnrctl status```  

![img_5.png](img_5.png)

* ```env | grep ORA```  

![img_6.png](img_6.png)

* ```sqlplus -s / as sysdba```
    * ```SET LINESIZE 230```
    * ```select name, created, open_mode, DATABASE_ROLE from v$database;```  
  ![img_7.png](img_7.png)
    * ```select VERSION_FULL, status, DATABASE_STATUS, INSTANCE_ROLE from v$instance;```  
  ![img_8.png](img_8.png)
    * ```select * from DBA_ROLE_PRIVS where GRANTED_ROLE='DBA';```  
 ![img_11.png](img_11.png)
    * ```desc ADMIN.TABLE1;```  
  ![img_10.png](img_10.png)
    * ```desc ADMIN.TABLE2;```  
  ![img_9.png](img_9.png)
    * ```select * from ADMIN.TABLE1;```  
  ![img_12.png](img_12.png)
    * ```select * from ADMIN.TABLE2;```  
  ![img_13.png](img_13.png)
  
