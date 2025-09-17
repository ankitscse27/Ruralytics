# Ruralytics
An interactive web app simulating an XGBoost sales forecasting model using JavaScript and Chart.js. Input custom sales data to instantly visualize model performance, feature importances, and a 14-day forecast. A portfolio piece showcasing front-end, data viz, and ML workflow skills.

# 📈 Dynamic Sales Forecasting Dashboard

A responsive, single-page web application that provides an interactive simulation of a machine learning sales forecasting model. This project is built entirely with **HTML, CSS, and Vanilla JavaScript**, using **Chart.js** for data visualization.



## ✨ Key Features

-   **Interactive ML Simulation**: Simulates the workflow of training an XGBoost model, evaluating its performance, and generating forecasts without a server-side backend.
-   **Custom Data Input**: Users can input their own recent sales data to see how the model adapts and generates a tailored forecast.
-   **Dynamic Results**: The entire dashboard updates on the fly, recalculating:
    -   Model performance metrics (**MAE** and **R²**).
    -   **Feature importances**, which adjust based on patterns in the input data (e.g., weekend sales spikes).
    -   A **14-day sales forecast** complete with a confidence interval.
-   **Rich Visualizations**: All results are displayed using clean, responsive charts powered by Chart.js.
-   **Modern UI/UX**: Features a sleek, responsive design with a beautiful **dark mode** toggle.

## 🛠️ How It Works & Tech Stack

This project is a **front-end simulation** designed to mimic a real data science application. The "intelligence" is programmed directly into the JavaScript:

-   The **forecast logic** identifies trends and seasonality (like weekend sales uplifts) from the user's data and projects them forward.
-   **Feature importances** are dynamically adjusted based on the statistical properties of the input data.
-   `async/await` and `setTimeout` are used to simulate the processing time required for model training and prediction, providing a realistic user experience.

**Technologies Used:**
-   **HTML5**
-   **CSS3** (with CSS Variables for easy theming)
-   **Vanilla JavaScript**
-   **Chart.js** for all charting
-   **Font Awesome** for icons

## 🚀 Getting Started

No setup required! Since this is a pure front-end project, you can run it by simply opening the HTML file in your browser.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/ankitscse27/git clone https://github.com/ankitscse27/Ruralytics.git
    ```
2.  **Navigate to the directory:**
    ```bash
    cd Ruralytics
    ```
3.  **Open the `index.html` file in your favorite web browser.**

That's it! You can now run the analysis, enter custom data, and explore the dashboard.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
