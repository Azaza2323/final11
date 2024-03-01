This Node.js web application provides a platform for users to view top news headlines, manage user accounts including admin roles, and explore movies from The Movie Database (TMDB) API. It features user authentication, dynamic content rendering with EJS, email functionality, and CRUD operations on a MongoDB database.

Features
User Authentication: Supports user registration, login, and profile management.
News Headlines: Fetches and displays top news headlines from NewsAPI.
Movies Exploration: Allows users to browse, search, and filter movies using The Movie Database (TMDB) API.
Admin Panel: An admin interface to manage user roles and details.
Email Integration: Sends out emails for user registration using Nodemailer.
Tech Stack
Backend: Node.js, Express.js
Database: MongoDB with Mongoose
Frontend: EJS, CSS
APIs: NewsAPI, The Movie Database (TMDB) API
Other Libraries: cors, body-parser, node-fetch, nodemailer
Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

Prerequisites
Node.js
npm
MongoDB account and cluster
Installation
Clone the repository
bash
Copy code
git clone <repository-url>
Install NPM packages
Copy code
npm install
Create a .env file in the root directory and add the following environment variables:
makefile
Copy code
DB_URI=<Your_MongoDB_URI>
NEWS_API_KEY=<Your_NewsAPI_Key>
TMDB_API_KEY=<Your_TMDB_API_Key>
EMAIL_USER=<Your_Email_Address>
EMAIL_PASS=<Your_Email_Password>
Ensure MongoDB is running and accessible through the URI provided in .env.
Running the Application
Start the server
sql
Copy code
npm start
The application should now be running on http://localhost:3000.
Usage
Visit http://localhost:3000 to explore the homepage and movies.
Access /login or /signup to manage user authentication.
Use the admin panel by navigating to /admin after logging in with an admin account (default admin account needs to be set up directly in the database).
Contributing
Please read CONTRIBUTING.md for details on our code of conduct, and the process for submitting pull requests to us.

License
This project is licensed under the MIT License - see the LICENSE.md file for details.
