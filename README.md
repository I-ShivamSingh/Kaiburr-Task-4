# Kaiburr Task 4: WEB UI Frontend

This project is the frontend part of Kaiburr Task 4, created using React. It complements the REST API developed using Spring Boot (Kaiburr Task 1) by providing a user-friendly web interface to interact with the server data.

## Table of Contents

- [Key Features](#key-features)
- [Technologies Used](#technologies-used)
- [How the Task Is Made](#how-the-task-is-made)
- [Prerequisites](#prerequisites)
- [How to Run the Application](#how-to-run-the-application)
- [Screenshots](#screenshots)

## Key Features
- Create new servers with specific details.
- Delete individual servers or all servers.
- View a list of servers with their details.

## Technologies Used
- React: A popular JavaScript library for building user interfaces.
- JavaScript/ES6: The primary programming language for React development.
- Material-UI: A popular UI component library for React applications, similar to Angular Material.
- Bootstrap: A responsive and customizable CSS framework.
- RESTful API: Communicates with the backend using RESTful web services.

## How the Task Is Made

The task consists of creating a web-based frontend using React that interacts with a REST API implemented using Spring Boot. The frontend provides functionality to view a list of servers, create new servers, and delete servers.

The application uses React components to separate different parts of the user interface:

- **Create Server Component**: Allows users to create a new server by providing server details.
- **Server List Component**: Displays a list of servers, and users can delete individual servers.

The frontend communicates with the backend using HTTP requests to perform CRUD (Create, Read, Update, Delete) operations on the server data.


## Prerequisites
- Node.js and npm (Node Package Manager)

## Project Setup
Before running the application, make sure you have the following:

1. Node.js and npm installed. You can download them from [here](https://nodejs.org/).

### How to Run the Application
Follow these steps to run the frontend of the Kaiburr Task 4:

1. Clone the repository to your local machine:

    ```bash
    git clone <repository-url>

2. Navigate to the project folder:

    ```bash
    cd kaiburr-task-4

3. Install the project dependencies:

    ```bash
    npm install

4. Start the Angular development server:

    ```bash
    npm start

5. Open a web browser and access the application at 
    ```bash
    http://localhost:3000/

## Screenshots

### Create Server Inserting Data
![App Screenshot](https://drive.google.com/uc?id=1mSZ3g0Jxrzsdpf6JJTZ0xM3qpQ4iSwd3)

### Server List after Creating a Server
![App Screenshot](https://drive.google.com/uc?id=1Kovs9xAFAaXarEBZsep8e6rUasY5GOzq)

### Server_API.server: MongoDB Database Collection after Creating a Server
![App Screenshot](https://drive.google.com/uc?id=1tb29rKndXcGEezE97Wws5MoeJ8axZLri)

### Server Creation is reflected in http://localhost:8080/api/servers
![App Screenshot](https://drive.google.com/uc?id=1VFNDVzvOwT7U7QrgzmTROY-2Z3v1W1OM)

### Web UI FrontEnd after Creating multiple servers
![App Screenshot](https://drive.google.com/uc?id=1DQ-89MVbj3MNQHFL1a6ltul6aIFHHdiu)
![App Screenshot](https://drive.google.com/uc?id=1MzJ_jzNPzTYU7Cmt_aHEgceL4TBxKMEX)

### Deleting a Server
![App Screenshot](https://drive.google.com/uc?id=1qaz7087hdbaBGihcCeUDLtb_k2CW4-lS)

### Server List after deleting a server
![App Screenshot](https://drive.google.com/uc?id=1hOhRx_HwQaDEKWat7xEP4DLf5xXHq7CH)

### Server_API.server: MongoDB Database Collection after Deleting a Server
![App Screenshot](https://drive.google.com/uc?id=1uUucOCFHmF4rGkQoOYNqK30_rCj9gWfH)

