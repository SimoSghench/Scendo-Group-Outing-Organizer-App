# Scendo – Group Outing Organizer App

Scendo is a web application designed to simplify the organization of group outings. Developed as a final project for the Software Architecture Design course at Università degli Studi di Napoli Federico II, this project simulates a real-world scenario by addressing both functional and non-functional requirements in a robust client-server architecture.

## Overview

Scendo offers a comprehensive platform where users can create, manage, and participate in group outings. The application supports:
- User registration with email verification.
- Creation of both public and private events.
- An invitation system for engaging friends and managing responses.
- Role-based access (Creator, Organizer, Participant) to provide tailored functionalities.

## Features

- **User Registration & Authentication:**  
  Secure sign-up process with email confirmation.

- **Event Management:**  
  Create and manage outings by specifying details like category, description, time, location, and participant limits.

- **Invitation System:**  
  Invite friends via email, manage incoming requests, and allow creators/organizers to handle invitations.

- **Calendar Integration:**  
  View all scheduled events in a user-friendly calendar interface.

- **RESTful API:**  
  A complete set of endpoints for all core operations to facilitate future integrations.

## Architecture

Scendo is built on a modern client-server architecture with the following layers:

- **Backend:**  
  Developed in Java using Spring Boot, the backend manages business logic, handles RESTful API calls, and interacts with a relational database via JPA.

- **Frontend:**  
  A responsive web interface built with React, delivering dynamic user experiences.

- **Database:**  
  Utilizes an H2 in-memory database for rapid development and testing, with easy adaptability to other DBMS in future releases.

This layered design ensures a clear separation of concerns, making the application scalable and maintainable.
