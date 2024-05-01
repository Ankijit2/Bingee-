# Real-Time Chat App with File Sharing and User Activity Tracking

## Overview
This project implements a real-time chat application with features like text messaging, file sharing, and user activity tracking. It utilizes the MERN stack along with Socket.IO for real-time communication and Cloudinary for efficient file storage and delivery.

## Features
- **Real-time Chat**: Users can send and receive text messages instantaneously.
- **File Sharing**: Support for sharing images, videos, and other files in real-time.
- **User Activity Tracking**: Dynamic display of active users and their online status.
- **Admin Dashboard**: Manage users, view chat analytics, and perform administrative tasks.
- **Scalability**: Designed to handle a growing user base with scalability in mind.
- **Cloud Storage**: Leveraging Cloudinary for flexible and secure file management.

## Technologies Used
- **Frontend**: React.js with Redux
- **Backend**: Node.js with Express.js
- **Database**: MongoDB
- **Real-time Communication**: Socket.IO
- **File Storage**: Cloudinary

## Implementation

### Frontend (React.js)
Create a chat interface with components for displaying messages, sending text messages, and uploading files. Utilize Socket.IO for establishing real-time connections with the server. Implement Redux for state management to handle chat messages, user activity, etc. Update UI dynamically to reflect real-time changes like new messages, received files, and user activity updates.

### Integrating Cloudinary
Use Cloudinary's JavaScript SDK for direct file uploads from the browser to Cloudinary. Capture the uploaded file's public URL provided by Cloudinary and send it to the backend along with message data.

### Backend (Node.js, Express.js)
Set up Express.js for server-side routing and API endpoints. Integrate Socket.IO with Express.js server for real-time communication. Implement API endpoints for user authentication (if applicable), sending text messages, uploading files, and downloading files. Utilize Cloudinary's Node.js SDK for additional operations on uploaded files like resizing or applying transformations. Broadcast messages, file sharing events (including file URLs), and user activity updates to all connected users using Socket.IO.

### Admin Dashboard
Create an admin dashboard using React.js to manage users, view chat analytics, and perform administrative tasks. Implement authentication and authorization to restrict access to the admin dashboard.

### Database (MongoDB)
Store user information (if applicable) using Mongoose ODM for data modeling. Store metadata about uploaded files in MongoDB, including message ID, Cloudinary public URL, and additional details as needed.

### Cloudinary Setup
Create a Cloudinary account and obtain necessary credentials. Configure Cloudinary settings based on application requirements, such as allowed file types and transformations.

## Getting Started
1. Clone the repository.
2. Set up MongoDB and create a database for the application.
3. Set up Cloudinary and configure credentials.
4. Install dependencies for both frontend and backend.
5. Start the server and the frontend application.
6. Access the application in your browser and start chatting!

## Contributors
- [Ankijit](https://github.com/Ankijit2)


