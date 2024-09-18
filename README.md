Notes App
About
This is a simple notes application that allows you to create, read, update, and delete (CRUD) notes. It is built using Node.js with Express for the backend, and modern front-end tools like React for the user interface. The app includes user authentication and server-side validation for managing notes securely.
Features
•	Create Notes: Add new notes with a title and content.
•	View Notes: View all your saved notes in an organized list.
•	Edit Notes: Update the content or title of existing notes.
•	Delete Notes: Remove unwanted notes from your collection.
•	User Authentication: Sign up, log in, and manage your account to access your personalized notes.
Technologies Used
•	Backend: Node.js, Express.js
•	Database: MongoDB (via Mongoose)
•	Frontend: React.js
•	Styling: Tailwind CSS
•	Build Tool: Vite
•	Other Tools: Axios for API requests, Bcrypt for password hashing
Getting Started
To run this application locally, follow these steps:
Prerequisites
•	Node.js (v20.14.0)
•	npm
Installation
1.	Clone the repository
git clone https://github.com/LeviFerraz/notes-app
2.	Navigate to the project directory
cd notes-app
3.	Install the backend dependencies
cd backend
npm install
4.	Navigate to the frontend/notes-app directory and install dependencies
cd ../frontend/notes-app/node_modules
npm install
Running the Application
1.	Start the backend server
Navigate to the backend folder and run:
npm run dev
2.	Start the frontend development server
In a separate terminal window, navigate to the frontend/notes-app/node_modules directory and install the node modules:
npm install
Then start the development server:
npm run dev
3.	Access the App
Open your web browser and navigate to http://localhost:3000 to use the Notes App.
Environment Variables
Ensure you configure the .env file in the backend directory with the following details:
•	MONGO_URI: Your MongoDB connection string
•	JWT_SECRET: Secret key for JSON Web Token
