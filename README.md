[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/0wrsx4Jb)
# Project Description

- This is a course project for Web Design/User Experience Engineering (INFO6150). This project aims to build a Full Stack Web Application known as Incident Ninja. Incident Ninja is designed to help businesses improve their IT operations. The main idea behind the application is that it allows the user to raise an incident which will be assigned to the support team and the issue will be resolved which will get updated on the user side. 
- The application is designed to be highly interactive and user-friendly, with many features to ensure a seamless user experience. Some of these features include a user login and registration system, incident creation and management functionality, filtering options for incidents, alert functionality for meaningful feedback, and a dashboard page to display analytics for active and inactive data.
# Tech Stack Used:
- Front End – Next.js
- Back End – Node.js, Express.js
- Databases – MongoDB

## Sprint-I Project Accomplishments:
### Backend:
1.	Created a database on MongoDB and established the connection in the backend. 
2.	Created user model that contains the user information.
Following routes are created for user model.
  -	POST /: This route is used to create a new user account, and it calls the post function from the userController module.
  -	GET /: This route is used to retrieve all existing user accounts, and it calls the getAll function from the userController module.
  -	GET /:id: This route is used to retrieve a specific user account by its ID, and it calls the get function from the userController module.
  -	PUT /:id: This route is used to update an existing user account, and it calls the put function from the userController module.
  -	DELETE /:id: This route is used to delete a specific user account by its ID, and it calls the remove function from the userController module.
  -	POST /auth: This route is used to authenticate a user and obtain an access token, and it calls the auth function from the userController module.
3.	UserController is created that define the logic for handling the HTTP requests received by the router routes. Each function corresponds to a specific route, and its main responsibility is to interact with the user data stored in the database, using the appropriate services.
4.	User Service is created to provide appropriate services to handle the RESTFUL API’s

### Frontend:
1.	Designed and developed a User Login and Registration System to allow users to create an account and login to access the application's features.
2.	Implemented a corresponding frontend functionality to send a logout request to the server when the user clicks the logout button.
3.	Added Routing Mechanism for responsive UI and to shift between frames efficiently.
4.	Designed and Created Pages and Routes for User Profile
5.	Developed hooks in the frontend to retrieve user information from the authentication state and user IDs.
6.	Used popular state management libraries such as React Redux and React Toolkit to manage user state and data in a robust and scalable manner.
7.	Ensured that user information is retrieved securely and efficiently and that it is used appropriately throughout the application.

## Sprint-II Project Accomplishments:
### Backend:
1.	Created Incident model and schema that contains incidents information.
2.	Following routes were created for incident model.
- POST /: This route is used to create a new incident resource, and it calls the post function from the incidentController module.
- GET /: This route is used to retrieve all existing incident resources, and it calls the getAll function from the incidentController module.
-	GET /:id: This route is used to retrieve a specific incident resource by its ID, and it calls the get function from the incidentController module.
-	PUT /:id: This route is used to update an existing incident resource by its ID, and it calls the put function from the incidentController module.
-	DELETE /:id: This route is used to delete a specific incident resource by its ID, and it calls the remove function from the incidentController module
3.	Incident Controller is created that define the logic for handling the HTTP requests received by the router. Each function corresponds to a specific route, and its main responsibility is to interact with the incident data stored in the database, using the appropriate services.
4.	Incident Service is created to provide appropriate services to handle the RESTFUL API’s

### Frontend:
1.	Designed Header section for the Incident Management page.
2.	Designed and developed an Incident Form based on the schema defined in the backend.
3.	Implemented API calls in the frontend to submit the Incident Form data to the backend, where it is validated and saved to the database.
4.	Designed UI for the Incident creation page.
-	Created a user interface (UI) for the Incident creation page that aligns with the design of the rest of the application.
-	Incorporated appropriate UI elements such as input fields, labels, and buttons to enable users to create incidents easily and efficiently.
5.	Developed an API call to retrieve all incidents from the backend that were created using the Incident Form.
6.	Designed and implemented a table format to display the retrieved incidents on the Incident Management page.
7.	Implemented Update and Delete API calls to update the created Incident and delete the Incident if required and added to the Incidents Retrieved table.
## Sprint-III Project Accomplishments:
1.	Designed and developed filtering functionality in the frontend to enable users to filter incidents based on specific criteria such as status, priority, agent, and user.
2.	Ensured that filtering works efficiently and that it provides users with a seamless and intuitive filtering experience.
3.	Implemented alert functionality in the frontend to provide users with meaningful feedback in response to certain actions or events.
4.	Developed toggle functionality in the frontend to enable users to switch between different table views based on their preference.
5.	Ensured that toggle functionality works efficiently and that it provides users with a smooth and intuitive table-viewing experience.

## Sprint-IV Project Accomplishments:
1.	Designed and developed a Dashboard page that displays key metrics related to incident management, such as the number of open and resolved tickets, average resolution time, and incident status distribution.
2.	Created Pie chart showing the number of incoming incidents, resolved incident, and overdue incident for each month of the year.
3.	Developed logic to retrieve the number of open, resolved, and due-today, Incidents.
4.	Designed and developed a card view in the frontend that displays the number of open, resolved, and due-today tickets in an easy-to-read format.
5.	Used a popular data visualization library such as Chart.js to create visually appealing and interactive pie chart that shows the distribution of Incident status (open, resolved, due-today).

# Steps for running the project:
1.	Install the node modules using "npm install" command in both backend and frontend.
2.	Run npm start for the backend application to run.
3.	Run npm run dev for the frontend application to run.
