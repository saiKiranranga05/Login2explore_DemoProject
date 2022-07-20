# Login2explore_DemoProject
A small project to demonstrate the new technology JsonDB

INTRODUCTION
This is a simple and elegant HTML,CSS,Js/jQuery Login/SignUp Page,
          to demonstrate the data sending & request handling over JsonPoweredDB-api for database management.
-This project uses JsonPoweredDB for the backend usage of saving all users data in the Json-format.
-Being the most efficient database, the time taken to POST & GET user-data from the database is almost null.
-Unlike SQL and relational databases, this JsonPoweredDB feels user and developer friendly.

SYNTEX USAGE

//GET

{
    "token": "90939164|-31949293979390979|90940219",
    "cmd": "GET",
    "dbName": "Student",
    "rel": "Student-Rel",
    "jsonStr":{
        "name": "Sai Kiran"
    }
}
//PUT

{
    "token": "90939164|-31949293979390979|90940219",
    "cmd": "PUT",
    "dbName": "Student",
    "rel": "Student-Rel",
    "jsonStr": {
        "id": "1",
        "name": "Sai Kiran",
        "email": "saikirank382@gmail.com",
        "mobileno": "9581453486"
    }
}
//UPDATE

{
    "token": "90939164|-31949293979390979|90940219",
    "cmd": "UPDATE",
    "dbName": "Student",
    "rel": "Student-Rel",
    "jsonStr": {
       "1":{
        "full_name": "SaiKiran",
        "email_address":"saikirank382@gmail.com",
        "mobile_number": 9581453486

       }
    }
   // BENFIT OF USING Json Power DB
   
   -Proprietary algorithm for High Performance CRUD operations. Multiple times faster than popular DBMS.
-Serverless support for faster development - A UI developer can develop complete dynamic application.
-DBMS with built in web / application server and embedded caching makes the performance lightning fast.
-Server side Native NoSQL - best query performance.
-In-built support to query on multiple JPDB databases.
-Multi-mode DBMS - Document DB, Key-Value DB, RDBMS support.
-Schema free - easy to develop and maintain.
-Web-services API - Can be used with any programming language that has support for HTTP.

//Illustrations

![image](https://user-images.githubusercontent.com/107807305/179895452-4513a2de-7bc1-4fce-834c-14a263dc9a0d.png)

![image](https://user-images.githubusercontent.com/107807305/179895536-a3a931de-40ec-4abe-b815-aca25e216db6.png)

![image](https://user-images.githubusercontent.com/107807305/179895586-c59db57c-a091-4680-8dc7-dadf565d3a41.png)


