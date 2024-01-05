# TODO List Application

This repository contains a simple TODO list application built using Node.js, HTML, CSS, JavaScript, and MongoDB. The application allows users to manage tasks by adding, updating, deleting, and marking them as completed.

## Features

- **Add Tasks:** Users can add new tasks to the TODO list.
- **Update Tasks:** Modify existing tasks as needed.
- **Delete Tasks:** Remove tasks that are no longer required.
- **Mark as Completed:** Users can mark tasks as completed or undone.
- **Persistent Storage:** Utilizes MongoDB to store task data, ensuring persistence between sessions.

## Technologies Used

- **Node.js:** Backend server environment for running JavaScript.
- **Express.js:** Web application framework for Node.js.
- **MongoDB:** NoSQL database to store task information.
- **HTML/CSS:** Frontend structure and styling.
- **JavaScript:** Frontend and backend logic for functionality.

## Installation

Follow these steps to set up and run the TODO list application locally:

1. Clone the repository
    
    git clone https://github.com/apk471/todo-list.git
    

2. Navigate to the project directory:

   
    cd todo-list
    

3. Install dependencies:

    
    npm install
    

4. Set up MongoDB:
   - Ensure MongoDB is installed and running locally or provide a MongoDB URI in the configuration.

5. Run the application:

    
    npm start
  

6. Access the application in your web browser:

    
    http://localhost:3000
    

## Configuration

- **Environment Variables:** Configure the MongoDB connection URI and other environment-specific variables in a `.env` file (not included in this repository).
- **Port:** The default port for the application is 3000, but you can modify it by setting the `PORT` variable.

## Usage

- Open the application in your web browser.
- Start managing your tasks by adding, updating, deleting, and marking them as completed.
- Changes made to tasks will be stored persistently in the MongoDB database.

## Contribution

Contributions to enhance and improve the TODO list application are welcome. Feel free to fork the repository, make changes, and submit pull requests.

## License

This project is licensed under the [MIT License](LICENSE).

---
Feel free to modify the structure and content of this README file to best suit your application and its functionalities.
