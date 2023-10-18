# Hospital-Api

API for hospital.

> API for the Covid hospital for doctors, patients and reports.



#  Features
 - Register doctors
- Login for doctors
- Register patients
- Create Covid-19 test result
- Make list of all reports of a patients
- Make list of all reports with a specified status


# Database Models
- Doctor (name, email, password)
- Patient (name,  phone, reports[])
- Report (doctor, patient, status, date)

#  Folder Structure
- config (configuration files)
-  - moongose.js (for database connection)
- middleware
- - jwt for auth(auth.js)

 - models
  - doctor.js (for creating doctor database model)
  - patient.js (for creating patient database model)
  - report.js (for creating report database model)

- routes
  -api
    -v1
       - doctors.js (contains routes related to doctors)
       - patients.js (contains routes related to patients)
       - reports.js (contains routes related to reports)
- index.js
- package.json
- package-lock.json

#  How to Start
> npm start


# package install 
> npm install



# When Running in Local System
>  run the the code in postman with corresponding routes and data

host link
doctor register
 https://hospital-api-2bb3.onrender.com/api/v1/doctors/register

doctor login
https://hospital-api-2bb3.onrender.com/api/v1/doctors/login
