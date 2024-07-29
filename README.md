PROJECT_NAME: JOB PORTAL  WEBSITE USING MERN STACK

Overview:-
A fully functional job portal web application built using the MERN (MongoDB, Express.js, React, Node.js) stack. This platform connects job seekers with employers, providing a seamless experience for job searching, job posting, and application management.

Features:-

User Authentication: Secure user authentication and authorization using JWT tokens, with role-based access control for job seekers and employers.

Job Seeker Features:

Profile Management: Create and update profiles, including resume upload and skillset management.

Job Search: Advanced search and filtering options to find jobs based on various criteria such as location, job type, and skills.

Application Tracking: Track applied jobs and receive notifications about application status.

Employer Features:

Job Posting: Create, update, and manage job postings with detailed job descriptions, requirements, and application deadlines.

Candidate Management: View and manage applications, shortlist candidates, and schedule interviews.

Admin Dashboard: An admin interface to oversee platform activities, manage users, job postings, and handle reports.

Real-time Notifications: Push notifications for job application status updates and new job postings using Socket.IO.

Responsive Design: Fully responsive design ensuring usability across various devices and screen sizes.

Technologies Used:-

Frontend: React.js with Redux for state management, React Router for navigation, and Material-UI for modern UI components.

Backend: Node.js and Express.js for RESTful API development, JWT for authentication, and Socket.IO for real-time updates.

Database: MongoDB for data storage and Mongoose for object data modeling.

Deployment: Deployed on Heroku with continuous integration using GitHub Actions.

Getting Started:-

Clone the repository:

bash:-

git clone https://github.com/yourusername/mern-job-portal.git

cd mern-job-portal

Install dependencies:

bash:-

# Install backend dependencies:-

cd backend

npm install

# Install frontend dependencies:-

cd ../frontend

npm install

Set up environment variables:-

Create a .env file in the backend directory and add the following:-

makefile:-

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

Run the application:-

bash:-
# Start the backend server

cd backend
npm start

# Start the frontend server

cd ../frontend
npm start

Access the application:
Open your browser and navigate to http://localhost:3000.
