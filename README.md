# Task Manager App (Flutter)

A simple yet powerful task management app built with **Flutter** and **Firebase**. The app helps users create, manage, and track their tasks with features like task expiration management, task sorting, searching, and more.

---

## Features

- **Create, Edit, and Delete Tasks**: Easily add new tasks, update existing ones, and delete tasks.
- **Task Expiration Management**: Automatically removes expired tasks from the list.
- **Priority-based UI**: Tasks are color-coded based on how soon they are due (Overdue, Medium, Low).
- **Task Search**: Search for tasks by title or description.
- **Task Sorting & Filtering**: Sort tasks based on various criteria and filter them based on different attributes.
- **Dark and Light Themes**: Toggle between dark and light themes.
- **Firebase Authentication**: Secure login and logout functionality using Firebase.
- **Task Options**: Edit or delete tasks via a simple context menu.

### Login Screen Features:
- **Email & Password Login**: Sign in with your email and password. Supports email validation and password visibility toggle.
- **Google Sign-In**: Login with your Google account for a fast, seamless sign-in experience.
- **Phone Sign-In**: Secure phone number-based login using Firebase Authentication.
- **User Feedback**: Toast messages for successful login and error handling (e.g., incorrect email or password).
- **Forgot Password Option**: Option to reset password (UI only, functionality can be implemented).
- **Theme Toggle**: Users can switch between dark and light themes directly from the login screen.

---

## Installation

### Prerequisites

Make sure you have the following installed:

- **Flutter** (latest stable version) - [Install Flutter](https://flutter.dev/docs/get-started/install)
- **Dart** (comes with Flutter) - [Install Dart](https://dart.dev/get-dart)
- **Firebase Account** - [Create a Firebase Project](https://console.firebase.google.com/)

### Steps to Run the Project

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/task-manager-app.git
   cd task-manager-app
