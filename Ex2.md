# EX 2 Data Manipulation Language (DML) Commands and built in functions in SQL
## Date: 11/08/23
## AIM:
To create a manager database and execute DML queries using SQL.


## DML(Data Manipulation Language)
<div align="justify">
The SQL commands that deal with the manipulation of data present in the database belong to DML or Data Manipulation Language and this includes most of the SQL statements. It is the component of the SQL statement that controls access to data and to the database. Basically, DCL statements are grouped with DML statements.
</div>

## List of DML commands: 
<div align="justify">
INSERT: It is used to insert data into a table.<br>
UPDATE: It is used to update existing data within a table.<br>
DELETE: It is used to delete records from a database table.<br>
</div>

## Create the table as given below:
```sql
create table manager(enumber number(6),ename char(15),salary number(5),commission number(4),annualsalary number(7),Hiredate date,designation char(10),deptno number(2),reporting char(10));
```
## insert the following values into the table
```sql
insert into manager values(7369,'Dharsan',2500,500,30000,'30-June-81','clerk',10,'John');
insert into manager values(7839,'Subu',3000,400,36000,'1-Jul-82','manager',null,'James');
insert into manager values(7934,'Aadhi',3500,300,42000,'1-May-82','manager',30,NULL);
insert into manager values(7788,'Vikash',4000,0,48000,'12-Aug-82','clerk',50,'Bond');
```

### Q1) Update all the records of manager table by increasing 10% of their salary as bonus.

### QUERY:

![271174892-081ff76d-e743-4fee-993b-4fd367716f94](https://github.com/Thilagavathi7/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119407159/f6955536-fb8c-40aa-9909-c491656b8853)

### OUTPUT:

![271174912-b667993b-d5b9-4197-be2c-ee7cab1c7d1e](https://github.com/Thilagavathi7/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119407159/db1bbaa9-1cd8-4522-80e0-3faeae48dd65)

### Q2) Delete the records from manager table where the salary less than 2750.

### QUERY:

![271174961-c3469723-36d2-4488-ac58-b5c8683a0e93](https://github.com/Thilagavathi7/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119407159/670400cb-2636-4fbe-9319-732cda49ed25)

### OUTPUT:

![271174985-91233fd3-5dfa-4318-b62f-db528e31914c](https://github.com/Thilagavathi7/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119407159/d9abfd90-6f1b-4753-98ed-8285697eae13)

### Q3) Display each name of the employee as “Name” and annual salary as “Annual Salary” (Note: Salary in emp table is the monthly salary)

### QUERY:

![271175005-180d48fb-dd02-4d7e-991d-79e92d50f3ae](https://github.com/Thilagavathi7/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119407159/cf332c50-39c3-45ec-926e-cb2f41fb4eb9)

### OUTPUT:

![271175026-cbf1e6e9-9633-4cf9-ad85-341e7b03c613](https://github.com/Thilagavathi7/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119407159/8a460dc6-c0d8-481f-a84a-d99f535b6033)

### Q5)	List the names of Clerks from emp table.

### QUERY:

![271175071-feb4b41d-8428-440b-8961-078212a7e836](https://github.com/Thilagavathi7/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119407159/bdd7c035-bd19-4c9d-ace2-3a5aacb4aa14)

### OUTPUT:

![271175098-86f71191-94a7-45e6-b756-6020a06350b7](https://github.com/Thilagavathi7/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119407159/7260f3f7-f2d1-4a52-933c-3780a26dca51)

### Q6)	List the names of employee who are not Managers.

### QUERY:

![271175146-a65b548c-2cd5-45c9-b21b-89cbdb1114c4](https://github.com/Thilagavathi7/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119407159/9e298d25-7d18-4bee-ab95-6b8f8d05e63d)

### OUTPUT:

![271175187-02933c79-0073-4274-9b90-2bc9f4814d8b](https://github.com/Thilagavathi7/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119407159/34e07028-26bf-423d-98ae-4149d1560428)

### Q7)	List the names of employees not eligible for commission.

### QUERY:

![271175220-6d3c980b-752e-4df5-9648-2a4bcf6e1962](https://github.com/Thilagavathi7/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119407159/45e23487-fcf4-4e20-aa09-8a6c9c7cdffb)

### OUTPUT:

![271175271-f4a825b1-ac41-4d65-9b0c-e59a55e4ca33](https://github.com/Thilagavathi7/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119407159/744b47ab-81a7-4f28-b5d1-bf10f0b9195c)

### Q8)	List employees whose name either start or end with ‘s’.

### QUERY:

![271175311-aec361f2-371a-43c0-8be2-7fae5ecfa2e8](https://github.com/Thilagavathi7/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119407159/27d2697f-1f2a-409c-9374-e3e97fc715b4)

### OUTPUT:

![271175346-6c098d6f-d039-4325-9810-93275772b07f](https://github.com/Thilagavathi7/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119407159/b37e3a38-d62d-4491-8512-f12a5fe0ec5d)

### Q9) Sort emp table in ascending order by hire-date and list ename, job, deptno and hire-date.

### QUERY:

![271175362-89b37e50-40ad-42ab-9d4a-dbba66165238](https://github.com/Thilagavathi7/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119407159/1a3be6cd-b68a-4fcc-b5ea-98c566f2ca26)

### OUTPUT:

![271175394-9bd94ed7-a460-4084-8ede-87fdaf6191cf](https://github.com/Thilagavathi7/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119407159/3e73fadf-6fb6-4289-80dc-fbb6d9a74e1b)


### Q10) List the Details of Employees who have joined before 30 Sept 81.


### QUERY:
![271175413-a5349ed1-9a23-4d89-ad1f-4f1ea9cd63c0](https://github.com/Thilagavathi7/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119407159/faeb0611-f0ac-41ee-b245-826fb3672dc0)


### OUTPUT:

![271175439-85269e01-cc98-47d0-8e3a-18ca0b00d42e](https://github.com/Thilagavathi7/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119407159/d8b135db-5e02-49a5-b06e-34bc7edecaa5)

### Q11)	List ename, deptno and sal after sorting emp table in ascending order by deptno and then descending order by sal.


### QUERY:
![271175474-faf3c43b-22f9-467b-ac0d-ce28c829d279](https://github.com/Thilagavathi7/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119407159/78d4cbc8-8ac7-4056-9a21-24700c72e1dd)


### OUTPUT:

![271175517-4298c229-f964-4b6d-a0a2-a95cf3efb38c](https://github.com/Thilagavathi7/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119407159/54ac0b0b-07bf-4a1f-8960-35e1ec05cd6a)

### Q12) List the names of employees not belonging to dept no 30,40 & 10


### QUERY:
![271175548-b8bed764-1ff6-4925-a0e7-a6c41359274e](https://github.com/Thilagavathi7/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119407159/e53fe9df-5a16-482a-a7bb-ab3fbe64175f)


### OUTPUT:

![271175574-971930f3-b375-4560-acfc-2319350f6264](https://github.com/Thilagavathi7/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119407159/5de30dab-82dc-4e4d-9cc0-febbe9142288)


### Q13) Find number of rows in the table EMP

### QUERY:

![271175622-ddeee89b-b882-4857-b1b6-9d03bafb1db5](https://github.com/Thilagavathi7/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119407159/6d7cf19b-8800-4325-8068-cd4539fc2a81)

### OUTPUT:

![271175637-d33535ee-03c1-4985-a55c-a101cc7ee17b](https://github.com/Thilagavathi7/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119407159/2b9df9f2-6a38-4f7b-b409-6deae05dd2fe)

### Q14) Find maximum, minimum and average salary in EMP table.

### QUERY:

![271175678-cf58aa29-f3fa-4c7f-8d1f-d6a59c8ea7dd](https://github.com/Thilagavathi7/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119407159/263588c7-a77b-496d-b729-2a11dc208c7f)


### OUTPUT:

![271175689-4b00eb99-b144-4f53-becb-39f06680a9f3](https://github.com/Thilagavathi7/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119407159/10f02c7d-9dae-4b81-a789-bc7dfeac36fa)


### Q15) List the jobs and number of employees in each job. The result should be in the descending order of the number of employees.

### QUERY:

![271175705-534963f4-9772-4bab-90ec-1ccef54fb3c5](https://github.com/Thilagavathi7/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119407159/b8fcabb7-3566-43ec-82c8-a80f8e80a6f1)

### OUTPUT:

![271175721-c0e4cac3-dd5f-40df-84f2-d3126c560d40](https://github.com/Thilagavathi7/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119407159/1d987d82-12e4-4c42-a255-9dab76f5eb48)

### RESULT:

To create a manager database and execute DML queries using SQL is executed successfully.
