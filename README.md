# About TickOff

TickOff is a completely ordinary To-DO application built using MERN stack. It provides user authentication and task management based on categories.

# Setting up TickOff

Below are the instructions to setup TickOff locally.

## Prerequisites

Node.js, NPM and Python3 must be installed on the system.

## Cloning the Repository

```bash
git clone https://github.com/Hemangshu-Dey/TickOff.git
cd TickOff
```

## Configurations

**Backend Environment File**: Navigate to the backend folder and create `.env` file. Add the following content to the file:

    PORT=
    MONGODB_URI=
    JWT_KEY=
    FRONTEND_URL=
    
 - Create an account at MongoDB setup the key. `JWT_KEY` can be any secret or randomly generated key. `FRONTEND_URL` should contain the link of the hosted frontend or otherwise left empty.

 - Set up a virtual environment and make necessary package installations.
      `python -m venv venv`,
      `venv\Scripts\activate`,
      `pip install -r requirements.txt`

**Frontend Environment File**: Navigate to the frontend folder and create `.env` file. Add the following content to the file:

    VITE_BACKEND=
    
 - Here, `VITE_BACKEND` should contain the URL of the backend server.

## Running the Application

**Backend:**

  - Navigate to the backend directory.
  - Start the application: `python src/app.py`.

**Frontend:**

  - Navigate to the frontend directory.
  - Install dependencies: `npm install`.
  - Start the application: `npm run dev`. 
