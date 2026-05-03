# Ostad Project-runner

This repository contains two separate projects:

- **Ostadserver** — An Express.js backend server
- **OstadUI** — A React frontend application built with Vite

---

## Prerequisites

Make sure you have the following installed on your system:

- [Node.js](https://nodejs.org/) (version 16 or above recommended)
- npm (comes with Node.js) or yarn

---

## Getting Started

### 1. Run Ostadserver (Express Backend)

```bash
cd Ostadserver
npm install
npm start
```

This will start the Express server, usually on `http://localhost:5000` (or your configured port).

---

### 2. Run OstadUI (React + Vite Frontend)

```bash
cd OstadUI
npm install
npm run dev
```

This will start the Vite development server, usually on `http://localhost:3000` (or your configured port).

---

## Notes

- Make sure your backend server (`Ostadserver`) is running before starting the frontend (`OstadUI`) if your frontend depends on any API from the backend.
- You can customize ports by editing the `package.json` scripts or configuration files (`vite.config.js` for frontend and `server.js` or equivalent for backend).
- For production builds:

  - Backend: Use `npm run build` if applicable or deploy as needed.
  - Frontend: Run `npm run build` inside `OstadUI` to create a production build.

---

## Useful Commands

| Command         | Description                      | Location    |
| --------------- | -------------------------------- | ----------- |
| `npm install`   | Install dependencies             | Both        |
| `npm start`     | Start Express server             | Ostadserver |
| `npm run dev`   | Start Vite development server    | OstadUI     |
| `npm run build` | Build production frontend bundle | OstadUI     |

---

## Contact

For questions or support, please contact \[Your Name] or open an issue in this repository.

---

Happy coding! 🚀
