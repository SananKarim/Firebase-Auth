# Firebase Authentication Setup Guide

## 1. Set Up Firebase Project

### Go to Firebase Console
Visit [Firebase Console](https://console.firebase.google.com/).

### Create a Project
1. Click **"Add Project."**
2. Enter a project name and follow the setup wizard.

### Enable Firebase Authentication
1. Navigate to **Authentication > Sign-in method.**
2. Enable the **Google sign-in provider** and configure it.

### Set Up Firestore Database
1. Navigate to **Firestore Database** in the Firebase Console.
2. Click **Create Database,** choose a location, and start in **Test Mode** (or configure rules later).

---

## 2. Add Firebase Admin SDK to Your Backend

### Generate Service Account Key
1. Go to **Project Settings > Service Accounts** in the Firebase Console.
2. Click **Generate New Private Key** to download a JSON file (`serviceAccountKey.json`).

### Install Firebase Admin SDK
Run the following command in your project directory:

```bash
npm install firebase-admin
