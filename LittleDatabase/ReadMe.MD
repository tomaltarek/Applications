# Introduction
This is a database application meaning you can store your data in a full-featured RDBMS environment. 
With little knowledge of SQL you can use this appliation.
The applciation is powered by Java Derby technology.  

## What needs done?
Just download this folder to your computer. 

## Configuration: 
(For windows)
Cut derby jar file and paste it to C:\Program Files\Java\jre1.8.0_221\lib\ext folder of your computer.
You are good to go. Enjoy using a full RDBMS database

## Creating your database
You dont have to create a database , a ready-made database is sitting for you. The name of the database is test. 
All you have to do is run a cmd/pwershel  from the folder and type: java Crud. Yo will see a a database named test is created.

## Creating your first table
Just type: 
create tabel friends 
(id int PRIMARY KEY, name varchar(12));

## Creating your first record
Type: java Crud
Then type: insert into test 
values ('some text', 'some text');

## Your first Query
Tyep: java QueryDB
Then type: 
select * from test;

## Source Code
If you are interested about the source code [here it is] (https://github.com/tomaltarek/Java-Rudimentary-/tree/master/JoyeeFriends) 
