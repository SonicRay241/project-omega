# Real-Time Product Price Prediction Pipeline

This project demonstrates a real-time data pipeline that calculates product prices based on stock and demand. The system integrates **Flask** for AI model deployment, **RabbitMQ-Stream** for real-time message streaming, and **ElysiaJS** as the backend consumer and server.

## 🚀 Overview

The goal of this project is to provide dynamic price predictions that adapt in real time to changes in product stock levels and customer demand.

The pipeline includes:

* **Data ingestion** through RabbitMQ-Stream for real-time stock and demand updates
* **Model deployment** with Flask to calculate product prices using AI/ML logic
* **Backend integration** with ElysiaJS to consume predictions and serve them to clients via APIs

## 🧰 Tech Stack

* **Python 3.9+**
* **Flask** – AI model deployment as REST API
* **RabbitMQ-Stream** – real-time data pipeline for stock and demand updates
* **ElysiaJS** – backend server and consumer of predictions
* **NumPy / Pandas / scikit-learn** – preprocessing and model logic

## ✨ Features

* Real-time price prediction based on **stock and demand fluctuations**
* AI-powered pricing model deployed with **Flask**
* **Stream-based architecture** for scalability and low-latency updates
* API endpoints served via **ElysiaJS** for integration with frontend or external services

## 🔄 Data Flow Diagram

![Data Flow Diagram Placeholder](https://github.com/SonicRay241/project-omega/blob/diagram.png)

*(Replace with your own architecture diagram image)*

## 📄 License

This project is licensed under the MIT License.
