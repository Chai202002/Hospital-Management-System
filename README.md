# Hospital-Management-System
The objective of Hospital management system is: 
• To computerize all details regarding patient details and Hospital details. 
• Scheduling the appointment of patient with doctors to make it convenient for both.
• The information of the patients should be kept up to date and their record should be kept in  the system for historical purpose. 
• Implementation of Hospital management system will result in considerable reduction in file  search time, efficiency in medical data retrieval and quick availability of historical data of  patients.  
• Make an easy-to- use environment for the users.


Hospitals interact with a lot of people in a day and there are various activities involved 
in day-to-day operations of hospitals, for example booking of appointments, managing 
doctor schedules, etc. The purpose of the project entitled as Hospital Management 
System is to computerize the front office Management of Hospital to develop software 
which is user friendly, simple, fast, and cost effective. It deals with the collection of 
patient’s information like add patient, update patient, delete patient, view patient 
details. Traditionally, it was done manually. The main function of the system is register 
and store patient details and doctor details and retrieve these details as and when 
required, and also to manipulate these details meaningfully. There is a separate 
interface for patients. Patients have a separate login. Patients can book appointments. 
Patients can view/update/cancel already booked appointments if necessary. Cancelled 
appointments create free slots for other patients. The system avoids clash of 
appointments with other patients. Each patient is therefore ensured his/her slot. There 
is a separate interface for doctors. Doctors have a separate login. The system takes into 
consideration doctor schedules and does not allow appointments when a doctor is
already busy. Doctors are able to view patient details and edit/delete the patient details. 
Doctor can view all the insert/update/delete activates done by the patient so that a 
proper record of a patient can be maintained. Atrigger is the most important part of the 
SQL.It is a special type of stored-procedure which automatically runs when an event 
occurs in the database.Trigger run when a user tries to modify data through a data 
manipulation language (Like Insert,Update and Delete) event.In this project a trigger 
has been implemented on patient table so that any event performed by a patient can be 
seen by a doctor.In this way it helps to maintain the activities of a patient.Doctor’s are 
categorized based on the department.Hence,it is easier for a patient to book an 
appointment.


• The user module: It is used to encrypt the password. The users need to register or
log in to enter the website and access the website features.
• The patients module: It is used to store the details of patient such as patient id (pid), 
email, name, gender, slot, disease, time, date, dept, number. These details are 
considered to book an appointment for the patient. Trigger concept has been used 
on this table any action such as insert, update, delete done on this table will be 
reflected in a table by the name ‘triger’ with an additional attribute tid (primary key), 
action which stores the action performed and timestamp which stores the time at 
which action was performed. 
• The doctors module: It is used to store the details related to doctors. The detail such 
as doctor id (did), email, doctorname,dept. 
• The triger module: It is used to store the action performed on patients module. It has 
autoincrement key that is tid (primary key) . pid and email, name are the foreign 
key. Other attribute such as action and timestamp are non-prime attributes . 
• The test module: It is used to check whether the front end data entered in user table 
is getting stored in mysql database. 
The following schema is used in the project:
1. user ( id, username, usertype, email, password) 
2. patients ( pid, email, name, gender, slot, disease, time, date, dept, number) 
3. doctors ( did, email, doctorname, dept) 
4. trigr ( tid, pid, email, name, action, timestamp) 
5. test ( id, name, email) 
user table stores information of a user here user can be a patient or doctor.user table has got attributes 
such as id(primary key), username(primary key), usertype,email,password.patients table stores the 
information of a patient.patients table has got the attributes such as pid(primary key), email(primary 
key),name,gender,slot,disease,time,date,dept,number.doctors table stores information of doctor’s the 
attributes of this table are did(primary key),email(primary key),doctorname,dept.trigr stores the trigger 
actions performed by patients.test table has got the attributes such as id(primary key),name,email.


The software consists of the following: 
• Front end tools of the website: Bootstrap 
• Operating System: Windows 11 
• Programming languages for the website: HTML, CSS,PYTHON 
• Backend of the website: Flask 2.0.2 (python 3.9.0), SQLAlchemy, MYSQL 
• Database used: MYSQL 
• Text editor used: VISUAL STUDIO CODE 
• Communication interface: XAMPP 
The hardware used: 
• System name: HP Pavilion Ryzen 5 Hexa Core 5500U.
• RAM:8GB




