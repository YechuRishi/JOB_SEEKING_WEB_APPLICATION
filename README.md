# MERN Job Seeking Web Application

A full-stack job portal built with the MERN stack (MongoDB, Express, React, Node.js). Employers can post jobs and job seekers can browse and apply with resume uploads.

## Tech Stack
- **Frontend:** React.js, CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB, Mongoose
- **Auth:** JWT with HTTP-only cookies, bcrypt for password hashing
- **File Uploads:** Cloudinary
- **Middleware:** dotenv, cookie-parser, express-fileupload, cors

## Features
- User registration and login with roles (Job Seeker, Employer)
- Role-based authorization for job posting and applications
- Resume upload and storage on Cloudinary
- Secure JWT authentication and error handling

## Setup
1. Clone repo and install dependencies in `backend` and `frontend`.
2. Create `.env` with MongoDB URI, JWT secret, Cloudinary keys.
3. Run backend: `npm run dev`
4. Run frontend: `npm start`
