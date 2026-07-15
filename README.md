# Help Desk Ticket System

Full-stack help desk ticket management with JWT authentication, REST API, and SQLite.

## Problem Solved
Organizations need a reliable way to track, assign, and resolve IT support requests with role-based access control.

## Tech Stack
Node.js, Express, SQLite, JWT, bcrypt

## Features
- JWT authentication with role-based access (user, agent, admin)
- Full CRUD ticket lifecycle (open, in-progress, resolved, closed)
- Assign tickets, add comments, filter by status/priority/category
- Dashboard statistics for admins and agents

## Run
npm install && npm start

## API
POST /api/auth/register | POST /api/auth/login | GET /api/tickets | POST /api/tickets | PATCH /api/tickets/:id/status | PATCH /api/tickets/:id/assign | POST /api/tickets/:id/comments | GET /api/dashboard/stats

## Demonstrates
Backend REST API, database design, JWT auth, role-based access, input validation, real-world IT application

## License
MIT
