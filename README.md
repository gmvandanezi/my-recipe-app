# React-Node Recipe App 🍲
Welcome to the React-Node Recipe App! This application allows users to view, add, and manage their favorite recipes. It's built using React for the frontend and Node.js with Prisma for the backend.

## Getting Started 🚀

Prerequisites:
Node.js and npm installed on your machine.
An account on ElephantSQL for the database.
A Spoonacular API key for the recipe API

# Setting Up:

Clone the Repository:
```
git clone https://github.com/gmvandanezi/my-recipe-app.git
```
```
cd react-node-my-recipe-app
```

## Setting up the Backend:

Navigate to the backend directory:
```
cd backend
```

Install the necessary packages:
```
npm install
```

Spoonacular API:
```
Add the api key to the API_KEY variable in the .env file
```

ElephantSQL Setup:
```
Create a new database instance on ElephantSQL.
Copy the connection string provided by ElephantSQL.
```

Prisma Setup:
```
Replace the DATABASE_URL in the .env file with your ElephantSQL connection string.
```

Initialize Prisma and generate the Prisma client:
```
npx prisma init
```
```
npx prisma generate
```

Start the backend server:
```
npm start
```

## Setting up the Frontend:

Navigate to the frontend directory:
```
cd frontend
```

Install the necessary packages:
```
npm install
```

Start the frontend development server:
```
npm run dev
```

