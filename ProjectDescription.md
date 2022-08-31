# StudentDatabaseProject

Description: This is a simple database created using postgreSQL dedicated to how a school would handle having a student database. I planned out some important features necessary and got to work. 

Creating the tables: I created four tables for my database, which included a student table, emails table, classes table, and grades table. My students table, included 4 features being student_id, student_name, student_grad_year, and student_email. I created these with some unique and not null parameters, also naming the datatypes (VARCHAR and CHAR), with appropriate lengths. The student_id would be the primary key. I set the fill factor to 90 and added a tablespace which represents where the database would be stored in the file system. I then created an emails table, and repeated the process with student_email and student_email_pass, but this time added a foreign key constraint and having an update and delete constraint around the student_email feature. I created two more tables being the classes table, dealing with student classes, and grades, which addressed students gpa and gradebook login information. When not null was not added, it meant that the space could be left without information. 

Adding data: My next step was to add data into these tables. I created some data, and using the command INSERT INTO tablename I added about 5 rows into each table, making sure everything was working properly with a simple SELECT * FROM tablename command. 

Working with the data: 

Future uses and notes: 
