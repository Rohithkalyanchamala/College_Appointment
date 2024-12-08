# College Appointment System

A Spring Boot application to manage appointments between students and professors effectively, providing features for booking, tracking availability, and testing API functionality.

---

## Features

- **Appointment Booking**: Allows students to book appointments with professors seamlessly.
- **Professor Availability**: Tracks and updates professor availability in real-time.
- **API Testing**: Comprehensive testing of `GET`, `POST`, `DELETE`, and `PUT` API calls.
- **Database Integration**: Uses a relational database to store user, appointment, and availability data.
- **Spring Boot Integration**: Built using Spring Boot for efficient development and deployment.

---

## Technologies Used

- **Backend**: Java, Spring Boot
- **Database**: MySQL (or any relational database of choice)
- **Testing**: Postman
- **Build Tool**: Maven
- **Version Control**: Git and GitHub

## User Flow

- **1** :Student A1 authenticates to access the system.
- **2** :Professor P1 authenticates to access the system.
**3** :Professor P1 specifies which time slots he is free for appointments.
**4** :Student A1 views available time slots for Professor P1.
**5** :Student A1 books an appointment with Professor P1 for time T1.
**6** :Student A2 authenticates to access the system.
**7** :Student A2 books an appointment with Professor P1 for time T2.
**8** :Professor P1 cancels the appointment with Student A1.
**9** :Student A1 checks their appointments and realizes they do not have any pending appointments.











