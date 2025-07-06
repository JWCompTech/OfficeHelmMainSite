# OfficeHelmMainSite

Welcome to the **OfficeHelmMainSite** repository! This project hosts the official landing page for OfficeHelm, built with React for the frontend and Node.js/Express for the backend.

---

## Table of Contents

- [About](#about)  
- [Features](#features)  
- [Getting Started](#getting-started)  
- [Project Structure](#project-structure)  
- [Scripts](#scripts)  
- [Deployment](#deployment)  
- [Contributing](#contributing)  
- [License](#license)  

---

## About

This project provides a simple, responsive "Coming Soon" landing page with a contact form that submits messages to a backend API. It is designed to be lightweight, easy to deploy, and a solid foundation for future frontend enhancements.

---

## Features

- React-based frontend with a clean, modern UI  
- Contact form with client-side validation  
- Node.js/Express backend to handle contact form submissions  
- Proxy setup for development to connect frontend and backend easily  
- Easily extensible for adding status pages, authentication, and more  

---

## Getting Started

### Prerequisites

- Node.js 18+  
- npm (comes with Node.js)  

### Installation

1. Clone the repo:  
   ```bash
   git clone https://github.com/yourusername/OfficeHelmMainSite.git
   cd OfficeHelmMainSite
   ```

2. Install backend dependencies:  
   ```bash
   npm install
   ```

3. Create and navigate to the frontend folder, then install frontend dependencies:  
   ```bash
   cd frontend
   npm install
   ```

### Running Locally

- Start backend server (from root folder):  
  ```bash
  npm run dev
  ```

- Start frontend dev server (from `frontend` folder):  
  ```bash
  npm run dev
  ```

The frontend will be accessible at `http://localhost:5173` and proxy API requests to the backend at `http://localhost:3000`.

---

## Project Structure

```
OfficeHelmMainSite/
├── frontend/           # React frontend project (Vite)
│   ├── src/            # React source files
│   └── ...
├── server.js           # Node/Express backend server
├── package.json        # Backend project config and scripts
├── .gitignore
└── README.md
```

---

## Scripts

| Script         | Description                      |
|----------------|---------------------------------|
| `npm start`    | Run the backend server           |
| `npm run dev`  | Run backend with auto-reload     |
| `npm run build` (in `frontend`) | Build React frontend for production |

---

## Deployment

- Build the React app for production:  
  ```bash
  cd frontend
  npm run build
  ```

- Serve the built static files with the Express backend or deploy frontend and backend separately.

- Deploy the Node.js backend and React frontend to your hosting provider (e.g., Namecheap Node hosting).

---

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to open issues or submit pull requests.

---

## License

This project is licensed under the LGPL-3.0 license.

---

*Made with ❤️ by Josh Wise*  
