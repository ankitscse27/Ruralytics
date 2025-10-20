# 📈 Ruralytics: Dynamic Sales Forecasting Dashboard

**Ruralytics** is a powerful, interactive single-page web application that serves as a **front-end simulation** of a production-grade XGBoost sales forecasting model. It is a key portfolio piece demonstrating expertise in client-side data simulation, dynamic visualization, and sophisticated ML workflow representation using only **HTML, Vanilla JavaScript, and Chart.js**.

---

## ✨ Innovation & Core Features

Ruralytics' primary innovation is its ability to **dynamically analyze and forecast data** entirely on the client side, mimicking the intelligence of a server-side machine learning engine.

### 🧠 Intelligent ML Simulation

The application's JavaScript logic is engineered to provide a realistic, adaptive experience:

* **Custom Data-Driven Results:** Users input their own recent daily sales data, which the JavaScript logic instantly analyzes to determine trends and seasonality (e.g., weekend spikes).
* **Dynamic Feature Importance:** The model's key drivers (Feature Importance) are **not fixed**. They adjust on the fly based on the statistical patterns detected in the user's input, reflecting how a real model adapts to new data.
* **Realistic Workflow:** `async/await` and `setTimeout` are used to simulate the processing time for model "training" and prediction, enhancing the user's experience of a complex, back-end process.

### 📊 Actionable Visualization Dashboard

All model output is presented on a single, modern dashboard using **Chart.js** for maximum clarity and interactivity.

* **14-Day Forecast:** Generates a sales projection complete with a **95% Confidence Interval**, vital for robust inventory and staffing decisions.
* **Performance Metrics:** Displays real-time model evaluation metrics like **MAE** (Mean Absolute Error) and **R²** (Coefficient of Determination) after each analysis run.
* **Modern UI/UX:** Features a fully **responsive design** and an aesthetically pleasing, easy-to-use interface with a built-in **Dark Mode** toggle.

---

## 🛠️ Technical Stack

Ruralytics is a zero-dependency, pure front-end solution.

| Component | Technology | Purpose |
| :--- | :--- | :--- |
| **Logic & Simulation** | **Vanilla JavaScript** | Handles data processing, forecasting algorithms, and dynamic result generation. |
| **Visualization** | **Chart.js** | Core engine for all dynamic charts (Forecast, Feature Importance, Residuals). |
| **Structure & Styling** | **HTML5 & CSS3** | Single-page application template with responsive design and **CSS Variables** for easy theming. |
| **Icons** | **Font Awesome** | Provides a clean, professional icon set. |

---

## 🚀 Getting Started

As a pure front-end solution, **no complex installation or server setup is required.**

1.  **Clone the Repository:**
    git clone [https://github.com/ankitscse27/Ruralytics.git](https://github.com/ankitscse27/Ruralytics.git)
    cd Ruralytics
    
2.  **Run:** Simply open the `ay7.html` file in your preferred web browser.

The application will load, ready for you to input data and run the dynamic forecast simulation.

---

## 📄 License

This project is licensed under the **MIT License**.
