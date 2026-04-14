# Milking Tracker Application

A modern, responsive web application designed for dairy farmers to track milking sessions while providing a soothing audio environment for their cattle to help increase milk yields. 

## Key Features
- **Stress-Free Milking Interface:** A beautiful, responsive interface to track active milking sessions.
- **Integrated Cattle Audio:** Synchronized relaxing music player embedded within the timer to create a soothing environment.
- **Smart Farm Tracking:** Overview of total yields and total sessions straight from the home dashboard.
- **Comprehensive Analytics:** A dedicated history page listing previous sessions.
- **Mobile-First Design:** Fully responsive web application optimized for desktops, tablets, and phones.

---

## Technical Stack
- **Frontend:** Next.js (React), Custom CSS Modules
- **Backend:** Node.js, Express.js
- **Database:** SQLite with Sequelize ORM

---

## Setup & Run Instructions (Local Environment)

This project has been pre-configured so that you can install and launch the entire full-stack application (both Frontend and Backend API) with just two commands from the root directory!

### Prerequisites
- Make sure you have **Node.js** installed on your machine. (Download from `nodejs.org` if needed).

### Installation
1. Open your Terminal or Command Prompt.
2. Navigate into the main project root folder (`Music Milk`).
3. Run the following command:
   ```bash
   npm install
   ```
   *Note: This might take a minute. It will automatically install all the necessary dependencies for both the `client` and `server` sub-folders for you.*

### Starting the Application
1. While still inside the main project root folder, run:
   ```bash
   npm run dev
   ```
2. You will see both the API Server and the Frontend spinning up together successfully. 
3. Open your web browser and go to:
   **http://localhost:3000**

You are all set! The local SQLite database (`database.sqlite`) will automatically initialize and store all your milking sessions.
