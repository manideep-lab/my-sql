# my-sql

create table employee_07(
employee_id number(10) primary key,
employee_name varchar2(20),
 dob date,
 salary number(10),
 doj date,
qualification varchar(20));
   



To insert 30 rows into the `employee_09` table, you'll need an `INSERT INTO` statement for each row of data. Here's an example of how you could do this:

```sql
create table employee_07(
employee_id number(10) primary key,
employee_name varchar2(20),
 dob date,
 salary number(10),
 doj date,
qualification varchar(20));


---------------------------------------------
Set serveroutput on;
CREATER OR REPLACE PROCEDURE greet_user(p_name_IN varchar2)AS
BEGIN
 DBMS_OUTPUT.PUT_LINE('HELLO,'||p_name||'!');
END;
/


Executing the procedure:


BEGIN
  greet_user('jhon');
END;

   
