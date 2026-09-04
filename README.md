# LaunchPad Internship Portal

A full-stack internship portal where students can explore internship opportunities and submit applications.

## Live Demo

Live application: ADD_YOUR_DEPLOYED_URL_HERE

GitHub repository: ADD_YOUR_GITHUB_REPOSITORY_URL_HERE

Walkthrough video: ADD_YOUR_VIDEO_URL_HERE

## Project Overview

LaunchPad is a responsive internship portal designed to make internship discovery and application simple for students.

Users can:

- Browse internship opportunities
- Search by role, company, or skill
- Filter by domain and work mode
- View internship details
- Submit an application
- Receive validation and submission feedback

## Features

- Responsive desktop and mobile design
- Internship search and filtering
- Pagination
- Application form
- Server-side validation
- SQLite database persistence
- Loading, error, and empty states
- Health-check endpoint
- Structured server logging
- API rate limiting
- Secure HTTP headers
- Automated API tests

## Technology Stack

### Frontend

- HTML5
- CSS3
- JavaScript
- Responsive design

### Backend

- Node.js
- Express.js
- SQLite
- better-sqlite3

### Security and Testing

- Helmet
- express-rate-limit
- Prepared SQL statements
- Node.js built-in test runner

## Project Structure

```text
internship-portal-capstone/
├── public/
│   ├── index.html
│   ├── style.css
│   └── app.js
├── tests/
│   └── api.test.js
├── docs/
│   └── QA-CHECKLIST.md
├── server.js
├── package.json
├── SECURITY.md
├── README.md
└── internships.db
