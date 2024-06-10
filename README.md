# My Fullstack Application

This is a fullstack application with a Spring Boot for backend and a React for frontend.

## Features

- **Add User**: Create a new user.
- **View Users**: View a particular user.
- **Edit User**: Update user details.
- **Delete User**: Remove a user from the system.
- **Home Page**: Display all users.

## Project Structure

API Endpoints
GET /api/users: Retrieve all users.
GET /api/users/{id}: Retrieve a specific user by ID.
POST /api/users: Create a new user.
PUT /api/users/{id}: Update a user by ID.
DELETE /api/users/{id}: Delete a user by ID.

Project Structure Details

Backend (Spring Boot)
Controller: Handles incoming API requests and returns responses.
Repository: Interacts with the database.
Model: Represents the data structure.
Frontend (React)
Components: Reusable UI components (e.g., UserList, UserForm).
Pages: Main pages of the application (e.g., HomePage, AddUserPage, EditUserPage).
Services: Handles API calls to the backend.
Routing: Manages navigation between different pages.
Usage

Add a User:
Navigate to the "Add User" page.
Fill out the form and submit.

View User:
On the home page, click the view button next to a user.
You will find the details of that particular user.

Edit a User:
On the home page, click the edit button next to a user.
Update the details and submit.

Delete a User:
On the home page, click the delete button next to a user.

