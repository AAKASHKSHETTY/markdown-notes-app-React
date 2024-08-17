# Markdown Notepad

A simple and intuitive Markdown-based notepad built with React, HTML, CSS, and JavaScript, leveraging Firebase for backend storage. This application allows users to create, edit, and save notes in Markdown format with real-time synchronization across devices.

## Features

- **Markdown Support**: Write notes in Markdown with live preview.
- **Real-time Sync**: Notes are saved and synchronized in real-time using Firebase.
- **CRUD Operations**: Create, Read, Update, and Delete notes.

## Snapshots

<img width="747" alt="image" src="https://github.com/user-attachments/assets/90a33028-f9be-40eb-8988-07f70e453322">

<img width="747" alt="image" src="https://github.com/user-attachments/assets/2ac0858e-7565-494c-b80c-a92ec8eac60c">

## Technologies Used

- **React**: JavaScript library for building user interfaces.
- **HTML/CSS**: Markup and styling of the application.
- **JavaScript**: Functionality and logic.
- **Firebase**: Backend as a Service (BaaS) for real-time database.

## Installation

**Prerequisites**

- **Node.js**: Ensure you have Node.js installed on your machine.
- **Firebase**: Create Firebase Account and project to setup the database for the project.

## Steps to Run the Project Locally

1. Clone this Repo

2. Install Dependencies
```
npm install
```
3. Set Up Firebase

- Go to Firebase Console and create a new project.
- Enable Firestore and Firebase Authentication.
- Create a .env file in the root of your project and add your Firebase configuration:
- Add the configuration file to the firebase.js file
  
```
REACT_APP_API_KEY=your_api_key
REACT_APP_AUTH_DOMAIN=your_project_id.firebaseapp.com
REACT_APP_PROJECT_ID=your_project_id
REACT_APP_STORAGE_BUCKET=your_project_id.appspot.com
REACT_APP_MESSAGING_SENDER_ID=your_sender_id
REACT_APP_APP_ID=your_app_id
```
4. Run the Project
```
npm start
```
5. The application should now be running on http://localhost:3000

## Usage

- **Create a Note**: Click the "New Note" button to create a new markdown note.
- **Edit a Note**: Click on any existing note to edit.
- **Delete a Note**: Hover over a specific note in the sidebar's notes tab to see the delete icon, then click on it to remove the note.
