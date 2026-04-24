# omnistack11

Full-stack application built during **Rocketseat OmniStack Week 11** — a platform called *Be the Hero* that connects people to NGOs that need financial support for their incidents/cases.

## Objective

The objective of this project is to practice full-stack JavaScript development by building a complete application with a Node.js REST API, a React web frontend for NGO management, and a React Native mobile app for heroes (donors) to browse and contact NGOs.

## Project Structure

```
omnistack11/
├── backend/     # Node.js REST API (Express + Knex + SQLite)
├── frontend/    # React web app (NGO registration & incident management)
└── mobile/      # React Native app (browse incidents and contact NGOs)
```

## Features

- NGO registration and login
- Create, list, and delete incidents/cases
- Mobile app to browse all open incidents
- Contact NGO via WhatsApp or e-mail directly from the app

## Tech Stack

- **Backend**: Node.js, Express, Knex, SQLite
- **Frontend**: React, Axios
- **Mobile**: React Native, Expo

## Getting Started

```bash
# Backend
cd backend && npm install && npm start

# Frontend
cd frontend && npm install && npm start

# Mobile
cd mobile && npm install && npx expo start
```
