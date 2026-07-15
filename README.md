# Help Desk Ticket System

Full-stack help desk ticket management with JWT authentication, REST API, SQLite, and an interactive web UI.

## Problem Solved
Organizations need a reliable way to track, assign, and resolve IT support requests with role-based access control.

## Tech Stack
- **Backend:** Node.js, Express.js
- **Database:** SQLite (better-sqlite3)
- **Authentication:** JWT + bcrypt
- **Frontend:** Vanilla HTML/CSS/JavaScript
- **API:** RESTful architecture

## Features
- Interactive web dashboard with login/register
- JWT authentication with role-based access (user, agent, admin)
- Full CRUD ticket lifecycle (open, in-progress, resolved, closed)
- Create tickets with priority and category
- Update ticket status
- Add comments to tickets
- Dashboard statistics (total, open, in-progress, resolved)
- Filter tickets by status
- Real-time ticket detail view

## Run Locally

```bash
npm install
npm start
Open http://localhost:3000 in your browser.

## API Health Check
Visit http://localhost:3000/api/health
## Author
Lyoneh Gbojueh
