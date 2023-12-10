# Blog Website
This is a simple CRUD application for Blog. It allows creating, reading, updating and deleting blog records in a database.

 # Usage
 <ul>
   <li>Nodejs,nodemon</li>
   <li>Mysql Database</li>
 </ul>
 
 # Installation
 <ol>
   <li>Clone the repository</li>
   <li>
     <h5>For Client Folder</h5>
     <ul>
       <li> cd client /</li>
       <li> npm i </li>
       <li> npm run dev </li>
     </ul>
  <li>
    <h5>For Server Folder,You will use a new terminal check foldername</h5>
   <ul>
   <li>cd server /</li>
   <li>npm i</li>
   <li>nodemon index.js</li>
     </ul>
   </li>
   </li>
     
   </li>
 </ol>
 
 # DataBase Setup
 <h5>
To set up the database schema locally:
 </h5>
<ol>
  <li> CREATE DATABASE Blog ;</li>
  <li> USE Blog ;</li>
  <li> 
  CREATE TABLE User (
  id INT PRIMARY KEY AUTO_INCREMENT,
  username VARCHAR(50),
  email VARCHAR(50) UNIQUE,  
  password VARCHAR(255)
);</li>
  <li>
    CREATE TABLE Post (
  id INT PRIMARY KEY AUTO_INCREMENT,
  title VARCHAR(50),
  content VARCHAR(1000),
  user_id INT
);
  </li>
</ul>
