# ToDo App

A simple ToDo application built using Node.js, Express, and MongoDB Atlas.
   
The main functionality of your app is as follows:

Users can add tasks on the Main Page by entering a task description and clicking the Add button.
Users can delete tasks by clicking the Delete button next to the task they wish to remove.
Users can edit tasks by clicking the Edit button next to the task they wish to modify, which takes them to the Edit Page. On the Edit Page, they can update the task description and save their changes by clicking the Update button.
Users can navigate between the Main Page and Edit Page using the Back button on the Edit Page.


## Features

- Add tasks
- Delete tasks
- Edit tasks

## Installation

### Prerequisites

- Node.js (version 14 or higher)
- npm (version 6 or higher)
- MongoDB Atlas account

### Instructions

1. GIT repository: https://github.com/jackthiru1/updated-todo-app.git


2. Navigate to the project folder:

cd updated-todo-app


3. Install the dependencies:

npm install


4. Create a `.env` file in the root folder of the project and add the following:

MONGODB_URI=your_mongodb_uri_here
PORT=3001


Replace `your_mongodb_uri_here` with the MongoDB Atlas connection string.

5. Start the server:

node server.js


6. Open your browser and navigate to `http://localhost:3000`.



