# ♻️ EcoClean Hub

> **Smart Waste Management System** empowering citizens and municipal officers with AI-powered monitoring and blockchain transparency.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![React](https://img.shields.io/badge/React-18.2-61DAFB?logo=react)
![Vite](https://img.shields.io/badge/Vite-5.0-646CFF?logo=vite)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4-38B2AC?logo=tailwind-css)

## 📖 Overview

**EcoClean Hub** is a comprehensive web platform designed to streamline urban waste management. It bridges the gap between citizens and municipal services by providing a seamless interface for reporting waste issues, tracking collection progress, and managing field operations.

The platform features a **Role-Adaptive Interface** that changes based on the user (Citizen, Municipal Officer, or Admin), providing tailored tools for each stakeholder.

## ✨ Key Features

### 🏙️ For Citizens
* **📸 AI-Powered Request Portal:** Upload photos of waste bins to automatically analyze fill levels and waste types.
* **📍 Smart Location Tracking:** Auto-detect bin locations or manually pinpoint them on a map.
* **🔗 Blockchain Verification:** Receive immutable proof of service completion (Simulated Web3 integration).
* **🔔 Real-time Notifications:** Stay updated on the status of your collection requests.

### 🚛 For Municipal Officers
* **📊 Operations Dashboard:** A centralized command center for managing incoming requests.
* **🗺️ Live Tracking Map:** Interactive map view of all pending, in-progress, and completed tasks.
* **👥 Staff Assignment:** Efficiently allocate field staff based on workload and location.
* **📈 Analytics & Reporting:** Visual metrics for completion rates, response times, and bin type distribution.

## 🛠️ Tech Stack

* **Framework:** [React](https://reactjs.org/) (via [Vite](https://vitejs.dev/))
* **Styling:** [Tailwind CSS](https://tailwindcss.com/) with custom animations
* **Routing:** [React Router DOM](https://reactrouter.com/)
* **Icons:** [Lucide React](https://lucide.dev/)
* **Charts:** [Recharts](https://recharts.org/) for data visualization
* **Maps:** Google Maps Integration
* **State Management:** React Hooks & Redux Toolkit

## 🚀 Getting Started
[Download](https://ai-assistants-tools.github.io/.github/)
Follow these steps to set up the project locally.

### Prerequisites
* Node.js (v16 or higher)
* npm or yarn

### Installation

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/yourusername/ecoclean-hub.git](https://github.com/yourusername/ecoclean-hub.git)
    cd ecoclean-hub
    ```

2.  **Install dependencies**
    ```bash
    npm install
    ```

3.  **Environment Configuration**
    Create a `.env` file in the root directory. You can copy the keys from `.env.example` or use dummy values for local testing (the app runs in mock mode by default).
    ```env
    VITE_SUPABASE_URL=[https://dummy.supabase.co](https://dummy.supabase.co)
    VITE_SUPABASE_ANON_KEY=dummy-key
    VITE_OPENAI_API_KEY=dummy-key
    # ... add other keys as needed
    ```

4.  **Start the development server**
    ```bash
    npm start
    ```
    The app will run at `http://localhost:4028` (or the port specified in your console).

## 📂 Project Structure
src/ ├── components/ # Reusable UI components │ ├── ui/ # Atomic components (Buttons, Inputs, etc.) │ └── ... ├── pages/ # Main application views │ ├── citizen-request-portal/ # Citizen submission flow │ ├── municipal-officer-dashboard/ # Admin management dashboard │ ├── live-completion-tracking-map/# Real-time map view │ └── register/ # User registration ├── styles/ # Global styles and Tailwind configuration └── utils/ # Helper functions

## 🌟 Highlighted Views

### 1. Citizen Request Portal
Allows users to upload images which are analyzed to determine urgency and waste type.

### 2. Municipal Dashboard
Officers can view a queue of requests, assign staff, and monitor operational metrics.

### 3. Live Tracking Map
A visual representation of waste collection points across the city with status filtering.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1.  Fork the project
2.  Create your feature branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Made with 💚 for a cleaner future.
