# Data-Clone
A Command Line Interface SQL Clone Using C++ <br/>

## How to Run?<br/>
>* Install Any C++ Compiler and a source code editor.<br/>
>* Open the folder and Run main.cpp<br/>

## Supported SQL Commands <br/>
*###### To create table: <br/>
          CREATE TABLE STUDENTS ( GRNO INT , NAME VARCHAR , PHONE INT , BRANCH VARCHAR ); <br/>
          
*###### To insert data into table: <br/>
          INSERT INTO STUDENTS VALUES ( 11910113 , Krishna , 6006277089 , IT ); <br/>
          
*###### Error handling is also done: <br/>
          ****datatype error**** </br>
          INSERT INTO STUDENTS VALUES ( 11910354 , Swaminath , CS , 9865124786 ); </br>
          ****column error****<br/>
          INSERT INTO STUDENTS VALUES ( 11910354 , Swaminath , CS ); <br/>

*###### To select the data from the table :<br/>
          SELECT * FROM STUDENTS;<br/>
          SELECT NAME , PHONE FROM STUDENTS;<br/>
          SELECT NAME FROM STUDENTS WHERE GRNO = 11910234;<br/>
          
 *###### To get description of table :<br/>
          DESCRIBE STUDENTS;<br/>

 *###### To update the data in table :<br/>
          UPDATE STUDENTS SET NAME = KARTIK WHERE GRNO = 11910113;<br/>

 *###### To delete data from the table :<br/>
          DELETE FROM STUDENTS WHERE GRNO = 11910234;<br/>
          
 *###### To drop the table from schema :<br/>
          DROP TABLE STUDENTS;<br/>

## Output Screenshot<br/>
<img width="593" alt="image" src="https://user-images.githubusercontent.com/74672126/175497311-01c341a0-9c58-4d80-ae9b-78fd014826d6.png">
