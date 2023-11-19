# SQL-Practice
-- create
CREATE TABLE Student(
  student_id integer not null  primary key,
  student_name varchar(50) not null,
  student_age integer not null,
  student_gender varchar(8) not null
);

insert into Student values (221123, "Elo",12,"Female");
insert into Student values(201234, "Tolokazi",21,"Female");
insert into Student values(219233,"Mila",18,"Male");
insert into Student values(234789,"Sikho",27,"Male");
select*from Student;

update Student set student_age=28
where student_age=18;
select*from Student;

select student_age from Student
Order by student_age desc;

Truncate table Student;
Select*from Student;
Rename table Student to Register;
Select*from Register;
