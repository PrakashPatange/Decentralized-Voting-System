
Vote App
A MERN stack voting application that allows users to create, share, and participate in polls.

Features
Authenticated User Features:

Create and manage personal polls.
Share polls with friends.
View and analyze aggregate results of polls.
Delete unwanted polls.
Add new options to existing polls.
General User Features:

View and vote on all polls (authenticated or unauthenticated).
See poll results displayed in charts (e.g., using Chart.js).
Environment Setup
Create a .env file in the server directory with the following variables:
PORT=4000
DATABASE=mongodb://localhost/<DATABASE_NAME>
SECRET=ThisIsATemporarySecretKey
Replace <DATABASE_NAME> with the name of your MongoDB database.

Technologies Used
Backend:Node.js JavaScript runtime for the server.
Express: Web framework for building APIs.
MongoDB: NoSQL database for storing data.
Mongoose: Object Data Modeling (ODM) library for MongoDB.
bcrypt: Password hashing for secure authentication.
jsonwebtoken: Token-based authentication.
Frontend:
React: JavaScript library for building user interfaces.
Additional Libraries:
Chart.js or Google Charts: For visualizing poll results.
Getting Started
Clone the repository.
Navigate to the project directory and install dependencies:
npm install
Set up the .env file as described above.
Start the server:
npm start
Navigate to the frontend directory and start the React app:
npm start
User Stories
Authenticated Users:

Can create, manage, and delete polls.
Share polls with others.
View detailed results in chart format.
Add new options to existing polls.
Unauthenticated Users:

Can view and vote on all polls.
Access poll results in chart format.
Future Enhancements
