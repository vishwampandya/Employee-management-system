# Employee-management-system
A  employee management system , with simple GUI that even a small shopkeeper can rely on.

# Running the application
Eihter build the application and run the .exe file.
or
Compile all the classes in a sequential manner and run the front_page.java file .

# Database Schema
  there are two tables 
  1) login
    where admin username and password is stored.
    +----------+-------------+------+-----+---------+-------+
    | Field    | Type        | Null | Key | Default | Extra |
    +----------+-------------+------+-----+---------+-------+
    | username | varchar(10) | YES  |     | NULL    |       |
    | password | varchar(10) | YES  |     | NULL    |       |
    +----------+-------------+------+-----+---------+-------+
    
  2) employee
    where all the employee details are stored.
    +-----------+--------------+------+-----+---------+-------+ 
    | Field     | Type         | Null | Key | Default | Extra |
    +-----------+--------------+------+-----+---------+-------+
    | name      | varchar(10)  | YES  |     | NULL    |       |
    | fname     | varchar(20)  | YES  |     | NULL    |       |
    | age       | int(10)      | YES  |     | NULL    |       |
    | dob       | date         | YES  |     | NULL    |       |
    | addess    | varchar(20)  | YES  |     | NULL    |       |
    | phone     | varchar(160) | YES  |     | NULL    |       |
    | email     | varchar(50)  | YES  |     | NULL    |       |
    | education | varchar(30)  | YES  |     | NULL    |       |
    | post      | varchar(20)  | YES  |     | NULL    |       |
    | aadhar    | varchar(160) | YES  |     | NULL    |       |
    | emp_id    | int(100)     | YES  |     | NULL    |       |
    +-----------+--------------+------+-----+---------+-------+

