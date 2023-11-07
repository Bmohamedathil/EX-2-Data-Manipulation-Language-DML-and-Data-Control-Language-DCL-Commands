# EX 2 Data Manipulation Language (DML) Commands and built in functions in SQL
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
![270731124-b32bceb5-9f0f-4c30-b27f-c4375e677f46](https://github.com/Bmohamedathil/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119560261/14a79bfe-23b6-4b73-8716-80b23bd6d3db)


### OUTPUT:
![270852396-db8ff768-f851-4ee1-98d4-b25fc97b52c2](https://github.com/Bmohamedathil/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119560261/83bbaa8a-3e03-405f-a937-f4b214db8651)

### Q2) Delete the records from manager table where the salary less than 2750.


### QUERY:
![270718856-15e1ebf0-899f-4589-aee8-0ea4570cefba](https://github.com/Bmohamedathil/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119560261/649fb680-7964-4461-afb1-ae5a6c55e281)


### OUTPUT:
![270731685-ad0c2970-47bc-4591-8f4b-a295a38b092d](https://github.com/Bmohamedathil/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119560261/1322c1e8-9e7d-405f-a477-65763ffc8eb3)

### Q3) Display each name of the employee as “Name” and annual salary as “Annual Salary” (Note: Salary in emp table is the monthly salary)


### QUERY:
![270733395-72faf04a-7d00-4070-8b1b-433f67d05a51](https://github.com/Bmohamedathil/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119560261/6e524765-0e0b-49da-8e33-f207a0179c57)


### OUTPUT:
![270733298-b697b096-ba16-4329-ac6b-d015128fd061](https://github.com/Bmohamedathil/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119560261/ecb943cd-32e9-4123-816f-8980a8f93815)

### Q5)	List the names of Clerks from emp table.


### QUERY:
![270737656-b1f05e5a-a309-424e-b910-cb103f5413e3](https://github.com/Bmohamedathil/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119560261/859a56f6-4f18-4ff0-b651-32086e19b126)


### OUTPUT:
![270738265-f8bc5ab3-f99d-400e-aa3f-c1f6c4a06c5d](https://github.com/Bmohamedathil/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119560261/76136b69-472c-416e-85fc-3f4e163f4c28)


### Q6)	List the names of employee who are not Managers.


### QUERY:
![270738366-01b12f80-95f7-431c-95a7-4470c12c4a72](https://github.com/Bmohamedathil/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119560261/94ac7f64-4760-4b76-a416-f453a28c2a45)


### OUTPUT:
![270738422-0cf2a6ad-398f-4d29-bebb-c31a84334347](https://github.com/Bmohamedathil/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119560261/506ad7b0-afdf-4b47-9ddf-aaa1d0d445d1)


### Q7)	List the names of employees not eligible for commission.


### QUERY:
![270738943-42336775-5693-4b45-93b4-f60e6b80183c](https://github.com/Bmohamedathil/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119560261/5c500c99-bbbb-4ceb-9d5c-a09ee8fe803d)


### OUTPUT:
![270739010-8f6da561-78ad-4573-9c8b-406de97e5e19](https://github.com/Bmohamedathil/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119560261/9e5311ce-063b-49f1-9d75-256af2bc7802)


### Q8)	List employees whose name either start or end with ‘s’.


### QUERY:
![270739894-63e34f73-6454-4c79-bafd-403fbb23ca66](https://github.com/Bmohamedathil/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119560261/339969ad-6e5c-4e37-8f70-d2a819c08b6a)


### OUTPUT:
![270739952-b947469e-7ad5-4b63-966b-652d7d2c8c0f](https://github.com/Bmohamedathil/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119560261/c6c19f7a-106e-4170-a0dd-c187db971fff)


### Q9) Sort emp table in ascending order by hire-date and list ename, job, deptno and hire-date.


### QUERY:
![270742384-ea09fd51-d67f-4b14-abc7-7093026e69dd](https://github.com/Bmohamedathil/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119560261/38d49099-9ad7-4232-8942-b1a23548ea99)


### OUTPUT:
![270742433-b3a0080f-b755-412a-b631-2c8484061c1c](https://github.com/Bmohamedathil/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119560261/70dbcb84-6ad5-4a15-a28b-27f155e57c61)


### Q10) List the Details of Employees who have joined before 30 Sept 81.


### QUERY:
![270743084-d96047cf-2bbb-4e35-9509-b6948cc69eff](https://github.com/Bmohamedathil/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119560261/1d785568-97d8-42f8-acff-6b174d283880)


### OUTPUT:
![270743263-dc101670-2467-428c-bf52-734adc718334](https://github.com/Bmohamedathil/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119560261/27024589-e2d5-47b1-b02d-3a3053d91fd9)


### Q11)	List ename, deptno and sal after sorting emp table in ascending order by deptno and then descending order by sal.


### QUERY:
![270743688-b195dae7-d5fb-405b-b0fd-8f3cac28497c](https://github.com/Bmohamedathil/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119560261/3cf54c5d-4091-4051-8470-2d30b2f4f6ba)


### OUTPUT:
![270743781-8366de8d-6502-4a70-a202-8540b84db42c](https://github.com/Bmohamedathil/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119560261/1c94b970-4ec1-4f97-af17-2c2d745bc010)


### Q12) List the names of employees not belonging to dept no 30,40 & 10


### QUERY:
![270744159-ab24e141-c401-4a54-92a5-6b83dec1f504](https://github.com/Bmohamedathil/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119560261/5eebff67-b0e8-45ce-b232-e8cad07d0c95)


### OUTPUT:
![270744231-5b712bd1-29b3-465b-93c0-5076e2aa9128](https://github.com/Bmohamedathil/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119560261/e3a1e344-005b-42fd-9ce3-da88972b5beb)

### Q13) Find number of rows in the table EMP

### QUERY:
![270744415-c7af2c72-f955-4cfa-925e-e1768eff217b](https://github.com/Bmohamedathil/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119560261/f5130cf1-96f0-4541-8ce1-6af9827913c5)


### OUTPUT:
![270744469-c5628317-f034-4f88-951c-339f05cd7079](https://github.com/Bmohamedathil/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119560261/c20d5bdb-2c88-4d60-9843-2a57f1e1c99b)


### Q14) Find maximum, minimum and average salary in EMP table.

### QUERY:
![270744958-b50b8a48-eb40-42e5-9fd4-c638757f67ba](https://github.com/Bmohamedathil/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119560261/c0467295-3e8d-481a-90e1-1e1de319b49a)


### OUTPUT:
![270745021-fa7dd8b3-a982-48f3-b03e-bd7f9152564e](https://github.com/Bmohamedathil/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119560261/5de3c47b-ffb3-4d05-a90b-6337ec913a9b)


### Q15) List the jobs and number of employees in each job. The result should be in the descending order of the number of employees.

### QUERY:
![270745532-16718b1f-b7d9-4fbf-97df-0b4a4e74466c](https://github.com/Bmohamedathil/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119560261/b1d27303-1c05-4f8e-bf16-50469b56b745)



### OUTPUT:
![270745586-123c7d66-c434-4809-8e89-85fefdf37f24](https://github.com/Bmohamedathil/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119560261/4310d4e4-8054-4f15-aec7-30e64d24792d)

## RESULT:
Thus,the data manipulation language and data control language commands are executed.
