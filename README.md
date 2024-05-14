# Hospital Management
![Screenshot 2024-04-30 102239](https://github.com/Ronrudy/Hospital-Management-System/assets/136009363/2fec3ece-df89-4c5a-a428-efe20a2172b7)

# Introduction
The hospital management system is designed to enhance the efficiency and effectiveness of healthcare management processes. It simplifies the workflow, improves communication, and ensures accurate record-keeping.
This repository contains a Hospital Management System built using Django, a high-level Python web framework. The system provides a comprehensive solution for managing various aspects of hospital operations, including patient management, doctor management, appointment scheduling, and more.

## Features and Usage:
![Screenshot 2024-04-30 102906](https://github.com/Ronrudy/Hospital-Management-System/assets/136009363/e173c603-0d8f-4286-bd07-2e474cee8f4b)

* User Authentication: Secure login and registration functionality for administrators, doctors, and patients.
* Patient Management: Operations for managing patient records, including personal details, medical history, and admission/discharge information.
* Doctor Management: Operations for managing doctor profiles, including specialization, contact details, and availability.
* Appointment Scheduling: Allows patients to schedule appointments with doctors based on availability.
* Dashboard Functionality: Provides personalized dashboards for administrators, doctors, and patients, displaying relevant information such as upcoming appointments, patient lists, and more.

# Technologies
## Frontend
* HTML: Used for Structuring Pages
* CSS: Used for Styling the pages

## Backend
* Django: python based framework used for building the backend structure
* db.sqlite3: Used as database.

# Other Technologies
* Git: used for controlling and tracking changes in the project codebase
* Github: hosting service for Git repositories

# How to run this project
* Install Python(3.7.6) (Dont Forget to Tick Add to Path while installing Python)
* Open Terminal and Execute Following Commands :
pip install django==3.0.5

* Then run following Commands in the directory folder :
py manage.py makemigrations
py manage.py migrate
py manage.py runserver
Now enter following URL in Your Browser Installed On Your Pc
http://127.0.0.1:8000/




