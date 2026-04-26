# ClustrCore

An all-in-one college management platform that helps students access events, resources, resume submissions, and connect with faculty and peers.

## Tech Stack
- **Backend:** Node.js, Express.js, MongoDB (Mongoose)
- **Frontend:** HTML, CSS, JavaScript
- **Authentication:** JWT, bcryptjs
- **Additional:** Nodemailer (Email), Twilio (SMS), PDFKit (PDF generation), Multer (File uploads)

## Features
- **Student Dashboard:** Centralized hub for students to access courses, announcements, and updates
- **Event Management:** Discover, register, and participate in college events and activities
- **Resource Library:** Share and access academic resources, notes, and study materials
- **Resume Builder:** Submit, manage, and download resumes for placement drives
- **Chatbot Support:** AI-powered chatbot to answer FAQs and assist with common queries

## How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ShubhiParashar-CSE/ClustrCore.git
   cd ClustrCore
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Set up environment variables:**
   Create a `.env` file in the root directory and add your configuration (database URL, email credentials, etc.)

4. **Start the server:**
   ```bash
   npm run dev
   ```
   The server will run on `http://localhost:3000` (or your configured port)

## What I Learned
- Building a full-stack application with a clear separation between frontend and backend
- Implementing JWT-based authentication and secure password hashing
- Integrating third-party services like email (Nodemailer) and SMS (Twilio)
- Managing complex database relationships using MongoDB and Mongoose
- Creating a user-friendly interface with multiple dashboards for different user roles
