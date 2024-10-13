# VehicleCare Center

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
  - [Running the App](#running-the-app)
- [Deployment](#deployment)

## Overview

VehicleCare Center is a web application designed to help car owners manage their vehicle maintenance schedules and track related expenses. Built using [Next.js](https://nextjs.org/) with [Firebase](https://firebase.google.com/) for backend services and [Material-UI](https://mui.com/) for UI components, it provides an organized system that reminds users of upcoming maintenance tasks and logs car-related expenses.

## Features

- **User Authentication**: Uses Firebase Authentication for social login (Google, Facebook, or email/password) to allow users to create profiles and save data.
- **Maintenance Reminders**: Users can set reminders for recurring maintenance tasks based on mileage or time intervals, stored in Firebase Firestore.
- **Expense Tracking**: Users can log and categorize car-related expenses (e.g., fuel, repairs) and view monthly/annual summaries.
- **Real-Time Updates**: Provides real-time updates on maintenance logs and expense entries using Firebase Firestore.
- **Notifications**: Sends reminders for maintenance tasks and overdue services using Firebase Cloud Functions.
- **File Uploads**: Allows users to upload receipts, invoices, and service records to Firebase Storage.
- **Reporting & Dashboard**: A dashboard to view maintenance history, upcoming tasks, and expense summaries with data visualizations.

## Project Structure

Modify here
```plaintext
car-maintanence-app/
│
├── pages/              # Next.js pages for routing
│   ├── api/            # API routes for serverless functions
│   ├── _app.js         # Custom App component
│   ├── index.js        # Home page
│   └── ...             # Other pages
├── components/         # Reusable UI components
├── styles/             # Global styles and theme configuration
├── public/             # Static assets like images
├── firebase.js         # Firebase configuration and initialization
├── package.json        # Project dependencies and scripts
└── README.md           # Project documentation (this file)
```

## Prerequisites

Before you begin, ensure you have met the following requirements:

- **Node.js** installed on your machine. You can download it from [nodejs.org](https://nodejs.org).

- **Yarn** (package manager) installed. You can install it from [yarnpkg.com](https://yarnpkg.com).

## Installation

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/cosmin-oros/VehicleCare-Center.git
    ```

2. Navigate to the project directory:

    ```bash
    cd car-maintenance-app
    ```

3. Install the dependencies:

    ```bash
    yarn install
    ```

## Usage

### Running the App

To start the development server and run the app in your browser, use the following command:

```bash
yarn dev
```

This will start the Next.js server at http://localhost:3000.

## Deployment

Firebase Hosting

