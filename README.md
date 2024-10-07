# Job Market Insights Application--(JOBBY)


## Overview
Job Market Insights is a web application that provides users with up-to-date job listings, detailed job descriptions, the ability to submit applications, and reviews from former employees. The application features a dynamic, visually rich UI and is built using the MERN stack. It is designed to make job searching and application a seamless process.

## Features
- Display current job listings with detailed descriptions.
- Allow users to submit job applications.
- Show reviews from former employees about specific job roles.
- Dynamic UI with animations and transitions using Tailwind CSS and Framer Motion.
- Frontend and backend integrated using REST APIs.
- Deployed on Heroku for live access.

## Technologies Used
- **Frontend:** React.js, Tailwind CSS, Framer Motion
- **Backend:** Node.js, Express.js
- **Database:** MySQL
- **Deployment:** Heroku
- **Other Tools:** REST APIs

## Installation

### Prerequisites
- Node.js
- MySQL
- Git

### Steps to Install and Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/M-Charith/Job-Market-Insights.git
   cd Job-Market-Insights
   ```

2. **Install Backend Dependencies:**
   ```bash
   cd backend
   npm install
   ```

3. **Configure Database:**
   - Create a MySQL database and configure it in the `.env` file in the backend folder.
   - Example:
     ```
     DB_HOST=localhost
     DB_USER=root
     DB_PASS=yourpassword
     DB_NAME=job_insights
     ```

4. **Run Backend Server:**
   ```bash
   npm start
   ```

5. **Install Frontend Dependencies:**
   ```bash
   cd ../client
   npm install
   ```

6. **Run Frontend Development Server:**
   ```bash
   npm start
   ```

7. **Access the application:**  
   Open `http://localhost:3000` in your browser.

## Usage
- Search for jobs using the job listings page.
- Click on individual jobs to see detailed descriptions and reviews from former employees.
- Submit job applications through the application form.

## Deployment
The application has been deployed on Heroku. You can access the live version via this [link](#).

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Author
- [M. Charith](https://github.com/M-Charith)

---

This README provides a structured overview of the project and guides users on how to run the application.
