# ✈️ SkyCast AI — Airfare Price Prediction

> An end-to-end machine learning system that estimates airfare prices from historical flight data.

SkyCast AI is a machine learning-powered airfare prediction platform designed to estimate the expected price of a flight based on factors such as airline, travel class, number of stops, journey duration, booking window, route distance, and geographic information.

The project combines a trained machine learning model with a FastAPI backend and a React/Vite frontend to provide an interactive airfare estimation experience.

---

## 📸 Screenshots

### Flight Prediction Interface

![SkyCast AI Flight Prediction](Documents_&_Images/home.png)

The prediction interface allows users to enter their journey details, including:

- Departure airport
- Destination airport
- Airline
- Travel class
- Number of stops
- Departure time
- Arrival time
- Flight duration
- Days until departure

The application also calculates the approximate route distance automatically.

---

### Estimated Fare

![Estimated Airfare](Documents_&_Images/prediction.png)

After submitting the flight details, SkyCast AI provides an estimated airfare along with a summary of the selected flight.

> **Important:** The displayed price is a historical machine-learning estimate and is not a live airline ticket price.

---

### Model Explanation

![Model Analysis](Documents_&_Images/fare-analysis.png)

The application also provides information about the model and the features that contribute most strongly to the prediction.

The current model reports grouped feature importance, helping users understand which factors influence the trained model most.

---

# 🎯 Project Objective

The goal of SkyCast AI is to build an end-to-end airfare prediction system that can:

1. Clean and validate historical flight data
2. Engineer useful flight and geographic features
3. Compare multiple regression algorithms
4. Train and tune a machine learning model
5. Save the complete preprocessing and prediction pipeline
6. Serve predictions through a REST API
7. Provide an interactive web interface
8. Explain model performance and feature importance

---

# 🧠 Machine Learning

SkyCast AI treats airfare prediction as a **supervised regression problem**.

### Target

```text
price
