# Job-Tracker-Public

![Jobtracker](https://github.com/user-attachments/assets/0bb3a291-4b50-4c19-a940-b7af24b1a561)
# Job Tracker

Job Tracker is a full-stack web application designed to help users manage their job search process. It includes features such as:

- **Job Management:** Create, update, and list job applications.
- **Calendar Integration:** Schedule interviews and view events on a calendar (integrated with Zoom meeting invites).
- **Interactive Dashboard:** View statistics such as average response times, jobs grouped by board, and more.
- **User Authentication:** Secure login with JWT tokens.
- **Responsive UI:** Built with React, AG Grid, and React Big Calendar, styled with Tailwind CSS.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
  - [Backend API Endpoints](#backend-api-endpoints)
  - [Frontend Components](#frontend-components)
- [Zoom Integration](#zoom-integration)
- [Logging & Monitoring](#logging--monitoring)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Job Management:**  
  - Add, edit, and delete job applications.
  - Track dates applied and responded.
  - Group jobs by job board and view metrics.

- **Calendar & Interview Scheduling:**  
  - View interview events on an interactive calendar.
  - Schedule Zoom meetings directly from the site.
  - Display detailed meeting information in modals.

- **User Authentication:**  
  - Secure login and logout using JWT tokens and authentication middleware.
  - Role-based UI updates (e.g., display Login/Logout in Sidebar).

- **Analytics & Reporting:**  
  - Calculate average response time using MySQL aggregations.
  - Compute overall response rates and group statistics by JobBoard.
  - Optionally, integrate logging and monitoring for debugging and analytics.

## Tech Stack

- **Backend:**  
  - [Go (Golang)](https://golang.org/)
  - [Gin Web Framework](https://github.com/gin-gonic/gin)
  - MySQL for data storage
  - JWT for authentication
  - Optional: Zoom API integration for meeting scheduling

- **Frontend:**  
  - [React](https://reactjs.org/)
  - [AG Grid](https://www.ag-grid.com/) for data tables
  - [React Big Calendar](https://github.com/jquense/react-big-calendar) for the calendar UI
  - [Tailwind CSS](https://tailwindcss.com/) for styling

- **Logging & Monitoring:**  
  - Zap / Logrus for structured backend logging
  - (Optional) Prometheus for metrics collection

## Installation

### Prerequisites

- Go 1.16+ installed
- Node.js and npm installed
- MySQL installed and running
- (Optional) Zoom account credentials (for meeting integration)

### Backend Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/job-tracker.git
   cd job-tracker/server

### Public code is not available at this time. 

