# 14 Full-Stack React: Kanban Board

## Description

A web-based Kanban board for managing tasks, visualizing workflows, and tracking progress. This app allows users to create, update, and delete tasks, organize them into columns based on status (e.g., Todo, In Progress, Done), and manage priorities.

## Table of Contents
* Features 
* Deployed Link & Github Repo
* Technologies Used
* Installation 
* Usage
* License

## Features
* User Authentication: Secure login and registration using JWT.
* Task Management: Create, update, delete, and view tasks on a Kanban board.
* Drag and Drop: Move tasks between columns for easy status updates.
* Task Filtering: Filter tasks by priority, status, or assigned user.

## Deployed Link & Github Repo
* https://kanban-board2.onrender.com
* https://github.com/sabrinothman6495/Kanban-Board2


## Technologies Used
* Frontend: React, TypeScript, React Router
* Backend: Node.js, Express, JWT Authentication, Sequelize ORM
* Database: Postgres

## Installation 
### Prerequisites
* Node.js & npm
* PostgreSQL or MySQL
* Set up environment variables (see .env.example).

#### Clone the repository:
* git clone https://github.com/sabrinothman6495/Kanban-Board2
* cd kanban-board2

#### Install dependencies:
* npm install
* cd client
* npm install

#### Setup Environment Variables:
* DB_NAME=
* DB_USER=
* DB_PASSWORD=
* JWT_SECRET_KEY=

#### Initialize and Running app:

* run database: npm run seed
* build app: npm run build
* start server: npm start