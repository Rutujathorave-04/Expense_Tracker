# Expense Tracker System using MERN Stack

## Project Description:

    The Expense Tracker System is a web-based application designed to assist users in tracking and managing their daily expenses. This system is built using the MERN stack (MongoDB, Express.js, React.js, and Node.js) to create a scalable, responsive, and user-friendly application.

## Features

- User Authentication and Authorization:

      Allow users to sign up and log in to their personal accounts using secure authentication mechanisms.

- Expense and Category Management:

      Enable users to create, update, and delete expense entries and categories.Track expenses by date, category.

## Technical Architecture:

- Frontend:

  Utilize React.js for building the user interface, tsparticle library for awesome background effect and used other libraries like unique-names-generator, react-datepicker, moment

  Implement responsive design using CSS frameworks like Bootstrap and Material-Icons.

- Backend:

  Use Node.js and Express.js to build a RESTful API for handling client requests and serving as the application's backend.

  Implement authentication and authorization using JSON Web Tokens (JWT) and middleware to protect endpoints.

- Database:

  Store all data, including user information, expense entries, and categories, in MongoDB, a NoSQL database.

## Run Locally

Clone the project

```bash
  git clone https://github.com/Rutujathorave-04/Expense_Tracker.git
```

Go to the project directory

```bash
  cd Expense_Tracker
```

Go to the frontend directory and Install dependencies

```bash
  cd frontend
```

```bash
  npm install
```

Go to the backend directory and Install dependencies

```bash
  cd backend
```

```bash
  npm install
```

Start the frontend server

```bash
  npm start
```

Start the backend server

```bash
  npm run dev
```

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file in backend folder

create config folder and add config.env file in it and all env variables there.

`MONGO_URL` : Your MongoDB Connection String

`PORT`: PORT number

## Tech Stack

**Client:** React, Redux, react-bootstrap, Material Icons, tsparticles

**Server:** Node, Express

**Database:** MongoDB
