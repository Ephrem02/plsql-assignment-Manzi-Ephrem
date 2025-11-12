## Assignment Description
## Records, Collections and Goto Statements in PL/SQL
## Records
A record is like a container that holds related pieces of information together
Ex Student's profile card it contains name, age and id
Syntax:
Type student_record is RECORD(
    name varchar(20),
    age number,
    id number,
);
## Collections
It is like a list or array that can store multiple items of the same type
It has three types
-ASSOCIATIVE ARRAYS
-NESTED TABLES
-VARRAYS
An associative array is a collection of key value pairs

Nested Table is a collection of elements of the same data type that can grow or shrink dynamically

Varray is a collection with a fixed maximum size. You must specify how many elements it can hold when yo define it.

 
