# Slack Clone

A Slack-inspired messaging application built for CSE 183 (Web Applications) at UC Santa Cruz. The project replicates core Slack features with a JavaScript frontend and a Node.js/SQL backend.

---

## Table of Contents

- [About](#about)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the App](#running-the-app)
- [Features](#features)
- [Contributors](#contributors)

---

## About

This project was built as Assignment 8 for CSE 183 at UCSC. The goal was to design and implement a functional clone of Slack, recreating key aspects of its messaging interface and underlying API.

---

## Tech Stack

- **Frontend:** JavaScript (99%+)
- **Backend:** Node.js
- **Database:** SQL
- **Package Management:** npm

---

## Project Structure

```
Slack-Clone/
├── frontend/
│   └── src/          # Frontend source files
├── backend/
│   ├── src/          # Backend application logic
│   ├── api/          # API route definitions
│   └── sql/          # Database schema and migrations
├── package.json      # Root scripts to run both servers
└── README.md
```

---

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v14 or higher recommended)
- npm

### Installation

1. Clone the repository:

```bash
git clone https://github.com/michaelajuarez/Slack-Clone.git
cd Slack-Clone
```

2. Install root dependencies:

```bash
npm install
```

3. Install frontend dependencies:

```bash
cd frontend && npm install && cd ..
```

4. Install backend dependencies:

```bash
cd backend && npm install && cd ..
```

5. Set up the database by running the SQL scripts found in `backend/sql/`.

### Running the App

To start both the frontend and backend concurrently from the project root:

```bash
npm start
```

Or run them individually:

```bash
npm run backend    # Starts the backend server
npm run frontend   # Starts the frontend dev server
```

---

## Features

- Channel-based messaging interface
- Send and receive messages in real time
- Slack-inspired UI layout with sidebars and message threads
- RESTful API backend with SQL data persistence


Built as part of CSE 183 — Web Applications, UC Santa Cruz.
