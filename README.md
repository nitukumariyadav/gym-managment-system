# Gym Management System

## Table of Contents
- [Overview](#overview)
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Installation and Setup](#installation-and-setup)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Configuration](#configuration)
- [Usage](#usage)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview
The Gym Management System is an online application designed to streamline the operations of a gym facility. It provides digital solutions for managing member information, billing, notifications, and more. By digitizing these processes, it aims to improve efficiency, reduce paperwork, and enhance user experience for both gym administrators and members.

## Technologies Used
- **Frontend**: HTML5, CSS3, JavaScript
- **Backend**: Firebase (Firestore, Authentication)
- **Other Tools**: Git (version control), Firebase CLI

## Features
### Admin Module
- **Login**: Secure login for administrators to access the system.
- **Member Management**: Add, update, and delete member details.
- **Billing**: Create bills for members, view payment status.
- **Notifications**: Send notifications to members about dues, gym schedules, etc.

### User Module
- **Login**: Login functionality for gym members.
- **View Bills**: Access and view payment receipts and dues.
- **Notifications**: Receive notifications regarding membership status, gym announcements.

### Additional Features
- **Supplement Store**: Integration with a supplement store for members to purchase gym-related products.
- **Diet Details**: Provide diet plans and nutritional advice for members.

## Installation and Setup
To run the Gym Management System locally, follow these steps:

### Prerequisites
- Node.js and npm installed
- Firebase CLI installed
- Git installed

### Installation
1. Clone the repository:
git clone https://github.com/nitukumariyadav/gym-managment-system.git


2. Navigate to the project directory:
cd gym-managment-system


3. Install dependencies:
npm install


### Configuration
1. Set up Firebase:
- Create a Firebase project: [Firebase Console](https://console.firebase.google.com/)
- Initialize Firebase in your project:
  ```
  firebase use --add
  firebase init firestore  // Initialize Firestore rules and indexes
  ```

## Usage
Once the project is set up:
- Use the admin login to manage members, create bills, and send notifications.
- Members can log in to view bills, receive notifications, and access other services.

## Deployment
Deploy the project to a hosting platform like Firebase Hosting:
- Build the project:
npm run build

- Deploy to Firebase Hosting:
  firebase deploy

## Contributing
Contributions are welcome! If you have suggestions, find bugs, or want to contribute code:

Fork the repository.
Create a new branch (git checkout -b feature/your-feature).
Commit your changes (git commit -am 'Add new feature').
Push to the branch (git push origin feature/your-feature).
Create a new Pull Request.
License
This project is licensed under the MIT License.

## Contact
For questions or support, contact Nitu Kumari.
email: nitu60608@gmail.com


