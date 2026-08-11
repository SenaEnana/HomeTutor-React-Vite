# Student Teacher Agent (HomeTutor System) — Frontend Practice

A modern, responsive frontend application for a HomeTutor system, built to explore the speed, configuration, and developer experience of **Vite** coupled with **React**. 

*Note: This repository is a frontend-only implementation focused on UI/UX layout and build tool experimentation. It is distinct from other versions of this project built using Webpack or Vanilla JavaScript.*

---

## 🚀 Purpose & Learning Objectives

The main goal of this project was to transition away from traditional Webpack setups and get hands-on experience with Vite. Key areas of focus included:
*   **Lightning-Fast HMR (Hot Module Replacement):** Observing real-time updates during UI development.
*   **Vite Configuration:** Managing environment variables and asset hosting within the Vite ecosystem.
*   **Optimized Bundling:** Utilizing Rollup (under the hood in Vite) for clean production builds.

## 🛠️ Tech Stack

*   **Build Tool:** [Vite](https://vitejs.dev/)
*   **Frontend Library:** [React](https://react.dev/)
*   **Language:** TypeScript (ES6+)
*   **Styling:** Tailwind CSS

---

## 📦 Getting Started

Follow these steps to get a local copy of the project up and running.

### Prerequisites

Make sure you have [Node.js](https://nodejs.org/) installed (version 18+ recommended).

### Installation

1. Clone the repository:
   ```bash
   git clone [https://github.com/SenaEnana/HomeTutor-React-Vite.git](https://github.com/SenaEnana/HomeTutor-React-Vite.git)
   ```
2. Navigate into the project directory:
   ```bash
   cd student-teacher-agent
   ```
### Development Server

   Launch the Vite local development server:
   ```bash
    npm run dev
   ```
   The application will typically be accessible at http://localhost:5173/.

### Production Build

   To build the static frontend assets for production:
   ```bash
    npm run build
   ```

---

## 🗺️ Project Structure
  ```bash
  student-teacher-agent/
├── public/          # Static assets (images, icons)
├── src/
│   ├── components/  # Reusable UI components (Navbar, Sidebar, Cards)
│   ├── views/       # Main page layouts (Dashboard, TutorList, Profile)
│   ├── App.jsx      # Main application component
│   └── main.jsx     # Vite/React entry point
├── index.html       # Single Page Application entry (moved to root by Vite)
├── vite.config.js   # Vite specific configurations
└── package.json
  ```

---

## 📝 Key Features Mimicked

Even as a frontend-only practice run, the UI is mapped out to simulate a functional HomeTutor platform:

* Tutor Discovery: Browsing and filtering available tutors based on subject or rating.

* Student/Teacher Dashboards: Separate contextual views for both agent profiles.

* Booking System UI: Clean forms and schedules simulating how a user would book a session.

---

## 👨‍💻 Author

Sena Adane
