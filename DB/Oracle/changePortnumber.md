*  Connect to database 
~~~

SQL> connect username/password

Connected.
~~~

*  Execute the below command to change the port

~~~
SQL> Exec DBMS_XDB.SETHTTPPORT(8082); [Assuming you want to have HTTP going to this port]    
PL/SQL procedure successfully completed.
~~~
