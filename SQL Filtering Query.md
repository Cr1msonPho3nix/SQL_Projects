# Scenario
In this scenario, you need to get specific information about employees, their machines, and the departments they’re in. Your team needs this data to perform various tasks, such as running updates, posting a privacy notice in certain departments, and sending an alert to an employee with an issue on a machine.

You are responsible for finding the required information by querying a database. You’ll add filters to your queries to locate the information more quickly.

## 1. List all organization machines
- In this task, you need to get a list of all organization machines and their operating systems. The data is contained in the machines table.<br>Table names:
  - Organization machines table  is **device_id**.
  - Operating systems table  is **operating_system**.
  - Machines table  is **machines**.<br>
![All_machines](https://github.com/Cr1msonPho3nix/SQL_Projects/blob/main/img/Filtering%20Query/1.all_machines.PNG)

## 2. Retrieve a list of the machines with OS 2
- In this task, you need to obtain a list of all machines with the 'OS 2' operating system because these machines need an update.
![Filtering_OS2](https://github.com/Cr1msonPho3nix/SQL_Projects/blob/main/img/Filtering%20Query/2.machines_OS2.PNG)

## 3. List employees in specific departments
- In this task, you need to retrieve a list of all the employees in the 'Finance' and 'Sales' departments to obtain their office numbers. A notice about handling confidential financial information will be posted to these offices.<br>Table names:
  - Employees information table is **employees**.
  - Departments information row is **department**.
  - Departments that you want to filter are **Finance** and **Sales**.<br>
Sorting 'Finance' employees:<br>
![Select_finance](https://github.com/Cr1msonPho3nix/SQL_Projects/blob/main/img/Filtering%20Query/3.1.Select_finance.PNG)
Sorting 'Sales' employees:<br>
![Select_sales](https://github.com/Cr1msonPho3nix/SQL_Projects/blob/main/img/Filtering%20Query/3.2.Select_sales.PNG)

## 4. Identify employee machines
1. Our team recently discovered that there are issues with machines in the South building. In this task, you need to obtain certain employee and computer information. A machine in 'South-109' has an issue. You need to determine which employee uses that computer so you can send them an alert.
  - Office information columnn name is **office**.<br>
![Select_office_alone](https://github.com/Cr1msonPho3nix/SQL_Projects/blob/main/img/Filtering%20Query/4.1.select_office_alone.PNG)<br>

2. Next, your team has determined that there is an issue with all the machines in the South building. Offices in the organization are named with the building name, a hyphen, and the office number in that building (for example, 'South-109').
![Select_office_all](https://github.com/Cr1msonPho3nix/SQL_Projects/blob/main/img/Filtering%20Query/4.2.select_office_all.PNG)<br>
