# SmartAgrox (Agri-Smartwise) 🌱

Welcome to **SmartAgrox**, an advanced, modern web application designed to empower farmers and agricultural enthusiasts with cutting-edge technology. By integrating Satellite Imagery, Artificial Intelligence, Geographic Information Systems (GIS), and real-time data, SmartAgrox provides actionable insights to improve crop yield, monitor farm health, and streamline agricultural operations.

![SmartAgrox Overview](https://img.shields.io/badge/Status-Active-brightgreen) ![React](https://img.shields.io/badge/React-18.3.1-blue) ![TypeScript](https://img.shields.io/badge/TypeScript-5.5.3-blue) ![Vite](https://img.shields.io/badge/Vite-5.4.1-purple)

## 🌟 Key Features

* **🛰️ Satellite Vision & GIS Integration:**
  * Uses **Sentinel Hub API** and **GeoTIFF** to fetch and visualize high-resolution satellite imagery (NDVI, moisture, etc.).
  * Interactive maps powered by **Leaflet** and **React-Leaflet**.
  * Spatial analysis utilizing **Turf.js** and **GeoBlaze**.

* **🤖 AgriBuddy (AI Assistant):**
  * An intelligent, personalized agricultural assistant powered by **Google Generative AI (Gemini)**.
  * Get instant answers to farming queries, crop disease diagnosis, and localized best practices.

* **🌍 Multi-Language Support:**
  * Fully localized interface supporting multiple regional languages (Bengali, Gujarati, Kannada, Malayalam, Marathi, Punjabi, Tamil, etc.) using **i18next**.

* **📊 Yield Prediction & Analytics:**
  * Data-driven crop yield prediction models.
  * Beautiful, interactive charts and data visualizations using **Recharts**.

* **🔔 Smart Farming Alerts:**
  * Configurable alert settings for weather changes, soil conditions, and critical agricultural events.

## 🛠️ Technology Stack

* **Frontend Framework:** React 18 with TypeScript
* **Build Tool:** Vite
* **Styling & UI:** Tailwind CSS, Radix UI, Shadcn UI, Framer Motion
* **State Management & Fetching:** React Query, Axios
* **Routing:** React Router DOM
* **Backend & Database:** Firebase (Firestore, Authentication)
* **AI & Machine Learning:** Google Generative AI (`@google/generative-ai`)
* **Mapping & Geospatial:** Leaflet, Sentinel Hub JS, Turf.js
* **Internationalization:** i18next

## 🚀 Getting Started

Follow these instructions to set up the project locally for development and testing.

### Prerequisites

Ensure you have the following installed on your local machine:
* **Node.js** (v18 or higher recommended)
* **npm** or **yarn**

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/deekshith1818/smartAgrox.git
   cd smartAgrox
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Set up Environment Variables:**
   Create a `.env` file in the root directory and add your API keys (Firebase, Google Gemini, Sentinel Hub, etc.).
   ```env
   VITE_FIREBASE_API_KEY=your_firebase_api_key
   VITE_GEMINI_API_KEY=your_gemini_api_key
   # Add other required environment variables
   ```

4. **Start the Development Server:**
   ```bash
   npm run dev
   ```
   The application will be available at `http://localhost:3000`.

## 📂 Project Structure

```
smartAgrox/
├── src/
│   ├── components/      # Reusable UI components (common, agrovision, etc.)
│   ├── pages/           # Application pages (AgriBuddy, YieldPredictionPage, etc.)
│   ├── services/        # API and business logic (agriBuddyService, yieldPredictionService, etc.)
│   ├── lib/             # Utility functions and configurations
│   ├── i18n/            # Localization files (locales)
│   ├── styles/          # Global styles and animations
│   ├── App.tsx          # Main Application Component
│   └── main.tsx         # Entry point
├── public/              # Static assets
├── package.json         # Project metadata and dependencies
└── vite.config.ts       # Vite configuration
```

## 🤝 Contributing

We welcome contributions! Please follow these steps to contribute:
1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

## 📜 License

This project is licensed under the MIT License.
