# beshunodejs

run npm install to install the project dependencies

Setting up the PostgreSQL database
Install the following PostgreSQL environments.

PostgreSQLan opensource relational databse management system.
pgAdmin, standalone destop application for managing PostgreSQL databases.
Once installed and well configured, create a database and a table to work with.

Create a database, online_vidya_db.
CREATE DATABASE online_vidya_db
Create a table, online_vidya_db.
CREATE TABLE online_vidya_db (
  id SERIAL PRIMARY KEY,
  sno VARCHAR(20) NOT NULL,
  name VARCHAR(100) NOT NULL,
  phone VARCHAR(10) NOT NULL,
  email VARCHAR(50) NOT NULL,
  course VARCHAR(20) NOT NULL)
Running the application
Start the development server by Running:
npm run dev
In a browser, visit http://localhost/3000;

Interact with the application.
