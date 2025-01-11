# Firebase-Auth
1. Set Up Firebase Project
Go to Firebase Console: https://console.firebase.google.com/
Create a Project:
Click "Add Project."
Enter a project name and follow the setup wizard.
Enable Firebase Authentication:
Go to Authentication > Sign-in method.
Enable the Google sign-in provider and configure it.
Set Up Firestore Database:
Navigate to Firestore Database in the Firebase Console.
Click Create Database, choose a location, and start in Test Mode (or configure rules later).
2. Add Firebase Admin SDK to Your Backend
Generate Service Account Key:

Go to Project Settings > Service Accounts in the Firebase Console.
Click Generate New Private Key to download a JSON file (serviceAccountKey.json).
Install Firebase Admin SDK: Run this command in your project directory:

bash
Copy code
npm install firebase-admin
Store the Key File:

Place the serviceAccountKey.json file in a secure location in your project (e.g., in a config folder).
Ensure the file is excluded from version control (add it to .gitignore).
