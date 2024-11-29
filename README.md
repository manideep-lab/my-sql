# my-sql
'''sql
create table employee_07(
employee_id number(10) primary key,
employee_name varchar2(20),
 dob date,
 salary number(10),
 doj date,
qualification varchar(20));
   



To insert 30 rows into the `employee_09` table, you'll need an `INSERT INTO` statement for each row of data. Here's an example of how you could do this:

INSERT INTO employee_09 (employee_id, employee_name, dob, salary, doj, qualification) 
VALUES (1, 'John Doe', TO_DATE('1990-05-15', 'YYYY-MM-DD'), 55000, TO_DATE('2015-06-01', 'YYYY-MM-DD'), 'BSc Computer Science');

INSERT INTO employee_09 (employee_id, employee_name, dob, salary, doj, qualification) 
VALUES (2, 'Jane Smith', TO_DATE('1985-11-23', 'YYYY-MM-DD'), 62000, TO_DATE('2017-09-12', 'YYYY-MM-DD'), 'MBA');

INSERT INTO employee_09 (employee_id, employee_name, dob, salary, doj, qualification) 
VALUES (3, 'Alice Johnson', TO_DATE('1992-02-10', 'YYYY-MM-DD'), 47000, TO_DATE('2018-03-28', 'YYYY-MM-DD'), 'BTech Electrical');

INSERT INTO employee_09 (employee_id, employee_name, dob, salary, doj, qualification) 
VALUES (4, 'Robert Brown', TO_DATE('1980-09-05', 'YYYY-MM-DD'), 75000, TO_DATE('2012-01-18', 'YYYY-MM-DD'), 'MSc Physics');

INSERT INTO employee_09 (employee_id, employee_name, dob, salary, doj, qualification) 
VALUES (5, 'Emily Davis', TO_DATE('1995-07-22', 'YYYY-MM-DD'), 58000, TO_DATE('2019-08-30', 'YYYY-MM-DD'), 'BCom');

INSERT INTO employee_09 (employee_id, employee_name, dob, salary, doj, qualification) 
VALUES (6, 'Michael Wilson', TO_DATE('1990-03-17', 'YYYY-MM-DD'), 62000, TO_DATE('2016-02-20', 'YYYY-MM-DD'), 'MCA');

INSERT INTO employee_09 (employee_id, employee_name, dob, salary, doj, qualification) 
VALUES (7, 'Sophia Martinez', TO_DATE('1993-12-01', 'YYYY-MM-DD'), 49000, TO_DATE('2017-10-25', 'YYYY-MM-DD'), 'BBA');

INSERT INTO employee_09 (employee_id, employee_name, dob, salary, doj, qualification) 
VALUES (8, 'David Garcia', TO_DATE('1988-04-18', 'YYYY-MM-DD'), 67000, TO_DATE('2014-07-30', 'YYYY-MM-DD'), 'MTech');

INSERT INTO employee_09 (employee_id, employee_name, dob, salary, doj, qualification) 
VALUES (9, 'Olivia Taylor', TO_DATE('1991-10-10', 'YYYY-MM-DD'), 53000, TO_DATE('2018-01-15', 'YYYY-MM-DD'), 'MA English');

INSERT INTO employee_09 (employee_id, employee_name, dob, salary, doj, qualification) 
VALUES (10, 'William Lee', TO_DATE('1994-06-03', 'YYYY-MM-DD'), 58000, TO_DATE('2020-09-18', 'YYYY-MM-DD'), 'BTech Civil');

INSERT INTO employee_09 (employee_id, employee_name, dob, salary, doj, qualification) 
VALUES (11, 'Isabella Harris', TO_DATE('1990-11-12', 'YYYY-MM-DD'), 64000, TO_DATE('2016-04-05', 'YYYY-MM-DD'), 'MBA');

INSERT INTO employee_09 (employee_id, employee_name, dob, salary, doj, qualification) 
VALUES (12, 'Ethan Clark', TO_DATE('1992-08-21', 'YYYY-MM-DD'), 56000, TO_DATE('2017-12-15', 'YYYY-MM-DD'), 'BCom');

INSERT INTO employee_09 (employee_id, employee_name, dob, salary, doj, qualification) 
VALUES (13, 'Ava Young', TO_DATE('1993-05-25', 'YYYY-MM-DD'), 60000, TO_DATE('2019-06-10', 'YYYY-MM-DD'), 'BTech Computer Science');

INSERT INTO employee_09 (employee_id, employee_name, dob, salary, doj, qualification) 
VALUES (14, 'James King', TO_DATE('1984-07-30', 'YYYY-MM-DD'), 80000, TO_DATE('2011-02-01', 'YYYY-MM-DD'), 'PhD Chemistry');

INSERT INTO employee_09 (employee_id, employee_name, dob, salary, doj, qualification) 
VALUES (15, 'Charlotte White', TO_DATE('1990-12-17', 'YYYY-MM-DD'), 52000, TO_DATE('2015-10-25', 'YYYY-MM-DD'), 'MSc Biology');

INSERT INTO employee_09 (employee_id, employee_name, dob, salary, doj, qualification) 
VALUES (16, 'Benjamin Wright', TO_DATE('1987-02-10', 'YYYY-MM-DD'), 68000, TO_DATE('2014-05-10', 'YYYY-MM-DD'), 'MA History');

INSERT INTO employee_09 (employee_id, employee_name, dob, salary, doj, qualification) 
VALUES (17, 'Mia Walker', TO_DATE('1996-09-09', 'YYYY-MM-DD'), 53000, TO_DATE('2021-03-21', 'YYYY-MM-DD'), 'BSc Psychology');

INSERT INTO employee_09 (employee_id, employee_name, dob, salary, doj, qualification) 
VALUES (18, 'Alexander Scott', TO_DATE('1989-12-11', 'YYYY-MM-DD'), 72000, TO_DATE('2013-07-19', 'YYYY-MM-DD'), 'MBA');

INSERT INTO employee_09 (employee_id, employee_name, dob, salary, doj, qualification) 
VALUES (19, 'Amelia Adams', TO_DATE('1991-01-04', 'YYYY-MM-DD'), 59000, TO_DATE('2017-04-01', 'YYYY-MM-DD'), 'BBA');

INSERT INTO employee_09 (employee_id, employee_name, dob, salary, doj, qualification) 
VALUES (20, 'Lucas Nelson', TO_DATE('1992-10-15', 'YYYY-MM-DD'), 66000, TO_DATE('2018-08-15', 'YYYY-MM-DD'), 'MCA');

INSERT INTO employee_09 (employee_id, employee_name, dob, salary, doj, qualification) 
VALUES (21, 'Ella Carter', TO_DATE('1994-03-07', 'YYYY-MM-DD'), 54000, TO_DATE('2020-05-10', 'YYYY-MM-DD'), 'BCom');

INSERT INTO employee_09 (employee_id, employee_name, dob, salary, doj, qualification) 
VALUES (22, 'Daniel Perez', TO_DATE('1987-01-25', 'YYYY-MM-DD'), 75000, TO_DATE('2013-06-20', 'YYYY-MM-DD'), 'MTech');

INSERT INTO employee_09 (employee_id, employee_name, dob, salary, doj, qualification) 
VALUES (23, 'Grace Turner', TO_DATE('1993-12-02', 'YYYY-MM-DD'), 62000, TO_DATE('2017-11-03', 'YYYY-MM-DD'), 'BTech Civil');

INSERT INTO employee_09 (employee_id, employee_name, dob, salary, doj, qualification) 
VALUES (24, 'Henry Harris', TO_DATE('1986-05-10', 'YYYY-MM-DD'), 70000, TO_DATE('2012-01-08', 'YYYY-MM-DD'), 'PhD Physics');

INSERT INTO employee_09 (employee_id, employee_name, dob, salary, doj, qualification) 
VALUES (25, 'Zoe Martinez', TO_DATE('1995-02-18', 'YYYY-MM-DD'), 56000, TO_DATE('2019-07-25', 'YYYY-MM-DD'), 'BBA');

INSERT INTO employee_09 (employee_id, employee_name, dob, salary, doj, qualification) 
VALUES (26, 'Matthew Robinson', TO_DATE('1992-07-13', 'YYYY-MM-DD'), 63000, TO_DATE('2018-12-12', 'YYYY-MM-DD'), 'MBA');

INSERT INTO employee_09 (employee_id, employee_name, dob, salary, doj, qualification) 
VALUES (27, 'Lily Green', TO_DATE('1990-10-30', 'YYYY-MM-DD'), 52000, TO_DATE('2014-08-01', 'YYYY-MM-DD'), 'BCom');

INSERT INTO employee_09 (employee_id, employee_name, dob, salary, doj, qualification) 
VALUES (28, 'Jack Hall', TO_DATE('1988-09-22', 'YYYY-MM-DD'), 70000, TO_DATE('2013-04-18', 'YYYY-MM-DD'), 'MTech');

INSERT INTO employee_09 (employee_id, employee_name, dob, salary, doj, qualification) 
VALUES (29, 'Chloe Allen', TO_DATE('1994-04-11', 'YYYY-MM-DD'), 55000, TO_DATE('2020-01-15', 'YYYY-MM-DD'), 'MSc Chemistry');

INSERT INTO employee_09 (employee_id, employee_name, dob, salary, doj, qualification) 
VALUES (30, 'Jack Wilson', TO_DATE('1995-08-08', 'YYYY-MM-DD'),




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

   
