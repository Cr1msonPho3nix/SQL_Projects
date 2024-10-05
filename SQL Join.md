# Scenario
In this scenario, you’ll investigate a recent security incident that compromised some machines.

You are responsible for getting the required information from the database for the investigation.

## 1. Match employees to their machines
- First, you must identify which employees are using which machines. The data is located in the 'machines' and 'employees' tables. You must use a SQL inner join to return the records you need based on a connecting column. In the scenario, both tables include the device_id column, which you’ll use to perform the join.<br><br>
![inner_join](https://github.com/Cr1msonPho3nix/SQL_Projects/blob/main/img/Join/1.inner_join.PNG)<br>

## 2. Return more data
- You now must return the information on all machines and the employees who have machines. Next, you must do the reverse and retrieve the information of all employees and any machines that are assigned to them. To achieve this, you’ll complete a left join and a right join on the employees and machines tables. The results will include all records from one or the other table. You must link these tables using the common device_id column.<br>
Left Join<br><br>
![left_join](https://github.com/Cr1msonPho3nix/SQL_Projects/blob/main/img/Join/2.1.left_join.PNG)<br><br>
Right Join<br><br>
![right_join](https://github.com/Cr1msonPho3nix/SQL_Projects/blob/main/img/Join/2.2.right_join.PNG)<br><br>

## 3. Retrieve login attempt data
- To continue investigating the security incident, you must retrieve the information on all employees who have made login attempts. To achieve this, you’ll perform an inner join on the employees and log_in_attempts tables, linking them on the common username column.<br>
![inner_join_user_login_attempt](https://github.com/Cr1msonPho3nix/SQL_Projects/blob/main/img/Join/3.inner_join_user_login_attempt.PNG)<br>