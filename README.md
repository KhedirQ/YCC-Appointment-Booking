## Executive Summary:
YCC (Yezidi Cultural Center)Appointment Scheduling App
The YCC Appointment Scheduling App is a web-based application built using Ember.js in the frontend to allows users (clients)to view the office calendar, book new appointments, change existing appointments, and cancel appointments. It provides a user-friendly interface for clients to manage their appointments and offers efficient scheduling capabilities for a small office with two employees.In backend the app uses node.js and MongoDB local to allow administrator to create,read,update and delete appointments as well as save the user information.
## Installation

You will need the following things properly installed on your computer.

* [Git](https://git-scm.com/)
* [Node.js](https://nodejs.org/) (with npm)
* [MongoDB](https://fastdl.mongodb.org/windows/mongodb-windows-x86_64-7.0.4-signed.msi)
* [Ember CLI](https://cli.emberjs.com/release/)
* [Google Chrome](https://google.com/chrome/)

## Running the application

* git clone <repository-url>` this repository
* open command prompt and type in mongod to run the MongoDB server
* cd ycc-schedulingbackend and run the command prompt then type in node server.js
* cd ycc-schedulingfrontend and run the command prompt then type in ember serve
* Visit your backend app at [http://localhost:3000](http://localhost:3000).
* Visit your frontend app at [http://localhost:4200](http://localhost:4200).
  

## License 
This project is licensed under (MIT) License
## Further Reading / Useful Links

* [ember.js](https://emberjs.com/)
* [ember-cli](https://cli.emberjs.com/release/)
* Development Browser Extensions
  * [ember inspector for chrome](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi)
  * [ember inspector for firefox](https://addons.mozilla.org/en-US/firefox/addon/ember-inspector/)
## Getting Started:

The app provides the following key features:
View the office calendar to check available appointment slots.
Book new appointments on available slots.
Change existing appointments by selecting a different time slot.
Cancel appointments when necessary.
Secure user authentication for access.
A simple and intuitive user interface for managing appointments

## User Stories
## User Story 1:
As a registered user, I want to view the office calendar so I can check available appointment slots.
## Acceptance Criteria 1:
When I log in as a registered user, I should see a calendar view.
The calendar should display dates and available appointment slots.
I can click on a date to see the available time slots for that day.
The available time slots should be clearly visible.

## User Story 2: 
As a registered user, I want to book a new appointment so I can schedule a meeting with the office.
## Acceptance Criteria 2:
After viewing the available time slots, I can select a date and time for my appointment.
I must provide a valid reason or description for the appointment.
Once booked, the appointment should appear on my user dashboard.
I should receive a confirmation email with the appointment details.

## User Story 3: 
As a registered user, I want to change an existing appointment so I can reschedule it to a different time.

## Acceptance Criteria 3:
On my user dashboard, I should see a list of my existing appointments.
I can select an appointment and choose to reschedule it.
I must provide a new date and time for the appointment.
The system should update the appointment details accordingly.

## User Story 4: 
As a registered user, I want to cancel an appointment so I can free up that time slot.

## Acceptance Criteria 4:
On my user dashboard, I should see a list of my existing appointments.
I can select an appointment and choose to cancel it.
The system should prompt me for confirmation before canceling.
Once confirmed, the appointment should be removed from my dashboard.

## User Story 5:
As a system administrator, I want to manage user accounts and access control to ensure the security and integrity of the system.

## Acceptance Criteria 5:
I should have access to a dedicated admin panel for managing user accounts.
I can view, edit, or delete user accounts.
I can set user roles and permissions, including admin roles.
I can access logs and reports to monitor user activities.

## User Story 6:
As an unregistered user, I want to sign up for an account so I can access the appointment scheduling system.
## Acceptance Criteria 6:
There should be a clear and user-friendly registration form.
I must provide a valid email address, username, and password.
Upon successful registration, I should receive a confirmation email with an activation link.

## User Story 7:
As a user, I want to receive email notifications for appointment confirmations, changes, and cancellations.

## Acceptance Criteria7:
Users should receive an email confirmation when booking an appointment.
Users should receive an email when an appointment is changed or canceled.
The email notifications should include relevant details and instructions.

## Mis-User Stories
1.	Mis-User Story 1: As an attacker, I want to gain unauthorized access to the admin panel so I can manipulate user data.

2.	Mis-User Story 2: As a malicious user, I want to disrupt the scheduling system so appointments can't be booked.

## Mitigation Criteria 1:
•	Strong Authentication: Implement robust authentication mechanisms for admin access, such as multi-factor authentication (MFA) and strong password policies such as 
o	Enforcing complex password requirements, such as a mix of uppercase and lowercase letters, numbers, and special characters.
o	Enabling account lockout mechanisms after a certain number of failed login attempts


## Mitigation Criteria 2:
•	Logging and Monitoring: Implement comprehensive logging and monitoring of admin panel activities. Log login attempts, successful and unsuccessful, and regularly review these logs for unusual or suspicious activities.
•	Input Validation: Implement strict input validation to ensure that user-submitted data is within expected ranges and formats. This helps prevent injection attacks and data 
Mitigation Criteria 3:
•	Secure APIs: If your scheduling system uses APIs, ensure that they are secured and include rate limiting and authentication mechanisms. Verify API requests to prevent abuse.

•	Data Backups: Regularly back up appointment data and critical system components to ensure data recovery in case of an attack or system disruption.

Mockup Diagram 
Home Page

![image](https://github.com/KhedirQ/YCC-Appointment-Booking/assets/79780374/3b46f91a-4b68-4636-a888-afec7aa28f15)
Blog page

![image](https://github.com/KhedirQ/YCC-Appointment-Booking/assets/79780374/79ae31b3-c7f1-487b-a387-96a9ed05434c)

Reservation Review info page 

![image](https://github.com/KhedirQ/YCC-Appointment-Booking/assets/79780374/057842bc-0573-4168-a46b-529f4679fbc7)

C4 Modeling 
Context Diagram 

![image](https://github.com/KhedirQ/YCC-Appointment-Booking/assets/79780374/3f5e369b-92f1-4994-bb9a-6d9f35b3f84e)

Container Diagram

![image](https://github.com/KhedirQ/YCC-Appointment-Booking/assets/79780374/57d88032-761f-4cd8-888c-7105d21ae013)

Component Diagram 

![image](https://github.com/KhedirQ/YCC-Appointment-Booking/assets/79780374/8686846d-4291-47d2-8848-3e0a82abca3d)
