# ☀️ WeatherApp (React Native)

A simple, stylish, and fully cross-platform mobile weather application built using **React Native**. This project focuses on connecting a mobile frontend to a **free, public Weather API** to deliver real-time, location-based forecast data. It's an excellent example of handling external data in a mobile environment.

---

## ✨ Key Features

* **Cross-Platform:** Works seamlessly on both iOS and Android devices.
* **Real-Time Data:** Fetches and displays current temperature, humidity, and atmospheric conditions.
* **API Integration:** Demonstrates best practices for connecting a mobile app to a RESTful weather API.
* **Location Search:** Allows users to find weather data for various cities worldwide.
* **Modern UI:** Clean, mobile-first design for an optimal user experience.

## 🛠️ Technology Stack

| Technology | Purpose |
| :--- | :--- |
| **Framework** | ⚛️ **React Native** | Core mobile development framework. |
| **Language** | **JavaScript / TypeScript** | Primary language for the application logic. |
| **Data Source** | **External Free API** | For fetching all weather data (e.g., OpenWeatherMap). |

---

## 🚀 Getting Started

This project requires a standard React Native development environment setup.

### Prerequisites

* Node.js (LTS version)
* React Native CLI or Expo CLI
* Android Studio / Xcode
* An API key from your chosen free weather service.

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/adithp/WheaterApp.git](https://github.com/adithp/WheaterApp.git)
    cd WheaterApp
    ```
2.  **Install dependencies:**
    ```bash
    npm install
    # or
    yarn install
    ```
3.  **Setup API Key:**
    * Create a file named **`.env`** in the project's root directory.
    * Add your API key (ensure you use the correct variable name required by your code):
        ```
        REACT_APP_WEATHER_API_KEY="YOUR_FREE_API_KEY_HERE"
        ```

### Running the App

You can run the app on a simulator/emulator or a physical device:

**For Android:**
```bash
npx react-native run-android
