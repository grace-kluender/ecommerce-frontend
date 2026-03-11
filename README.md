# Ecommerce Frontend (React)

This repository contains the React-based frontend for a microservices e-commerce platform.

The frontend:
- Fetches products from the Product Service
- Creates orders through the Order Service
- Displays product catalog and order interactions

---

## Tech Stack

- React (JavaScript)
- Node.js
- npm
- Axios (HTTP client)

---

## Repository Structure

This repository follows a standardized structure used across all microservices repositories:

```
.
├── src/                # React application source code
│   ├── App.js          # Fetches products + creates orders
│   └── index.js        # React entry point
├── public/             # Static frontend assets
├── docs/               # Documentation and design notes
├── scripts/            # Operational helper scripts
├── .env.example        # Example environment configuration
├── package.json
└── README.md
```

---
## Prerequisites

- Node.js (v18+ recommended)
- npm (comes with Node)

Verify installation:

```
node -v
npm -v
```

---

## Configuration

This application uses environment variables to configure backend service URLs.

1. Create a local environment file
```
    cp .env.example .env
```

2. Update values if needed

NOTE: All frontend environment variables must start with REACT_APP_

---

## Run Locally

From the `ecommerce-frontend` directory:

```bash
npm install
npm start
