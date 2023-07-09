# Full Stack Web Application - Company Portal

This is a full stack web application project designed as a company portal where workers can log in using their business credentials. Depending on their role as an admin or non-admin, they will be routed to different pages and have access to various features and functionalities.

## Features

- User Authentication: Workers can log in using their business credentials to access the portal.
- Role-Based Routing: Depending on their role as an admin or non-admin, users will be redirected to different pages.
- Company Selection: After login, users will be directed to a page where they can choose the company they want to view data for, from a dropdown list.
- Home Page: The home page displays announcements from the selected company
- Create Announcement (Admin Only): Admin users have the ability to create new announcements to display to the whole company.
- Navigation Bar: A fixed navigation bar at the top of the screen allows users to easily navigate to different pages based on their role.
- Users Page (Admin Only): Admin users can view all active users in the company and have the option to create new users by filling out a user data form.
- Teams Page (Admin Only): Admin users can view all teams in the company, along with associated members. They can also create new teams by filling out a team data form.
- Projects Page: Users can view all the projects associated with a selected team. Users can also create new projects by filling out a project data form.

## Technologies Used

The application is built using the following technologies:

- Front-end:
  - HTML
  - CSS
  - TypeScript
  - AngularJS

- Back-end:
  - Java
  - Spring Boot
  - PostgreSQL

## Installation

To run the project locally, follow these steps:

1. Clone the repository: `git clone https://github.com/JavierPHS/Business-Management-Full-Stack-Application`
2. Open up project backend directory in IDE of your choice
3. Edit the application.properties file in the resources folder to match your current postgreSQL credentials
4. Perform a clean install of the project
5. Run GroupFinalApplication.java to start server
6. Open terminal window
7. Navigate to the frontend portion of the project: `cd frontend`
8. Install the dependencies: `npm install`
9. Start the server: `npm start`
10. Access the application by opening your browser and visiting `http://localhost:4200`.


## Acknowledgements

This project was developed as part of a web development course and follows best practices and conventions recommended by the course instructors.
