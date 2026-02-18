# Ecommerce Frontend (React)

This repository contains the React-based frontend for a microservices e-commerce platform.

The frontend:
- Fetches products from the Product Service
- Creates orders through the Order Service

At this stage (Phase 1), the focus is on repository structure, local development setup, and establishing a Git workflow foundation.

---

## Tech Stack

- React (JavaScript)
- Node.js
- npm
- Axios (HTTP client)

---

## Repository Structure

This repository follows a standardized structure used across all microservices repositories:

├── src/ # React application source code
│ ├── App.js # Fetches products + creates orders via backend APIs
│ └── index.js# React entry point
├── public/ # Static frontend assets (HTML entry point, icons, etc.)
├── docs/ # Documentation and design notes
├── scripts/ # Operational helper scripts
├── package.json
└── README.md


---

## Prerequisites

- Node.js (LTS recommended)
- npm

---

## Run Locally

From the `ecommerce-frontend` directory:

```bash
npm install
npm start
