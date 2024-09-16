# No Traffic System

**A Decentralized, AI-Driven Traffic Management System to Eliminate Congestion**

This project is designed to revolutionize traffic management in urban areas by leveraging real-time data, AI, and IoT technologies to prevent traffic congestion. The system optimizes vehicle flow by dynamically adjusting traffic signals, rerouting vehicles, and giving priority to emergency services—all without the need for human intervention or a central authority.

---

## Table of Contents

1. [Overview](#overview)
2. [Features](#features)
3. [Technologies](#technologies)
4. [System Architecture](#system-architecture)
5. [Installation](#installation)
6. [Usage](#usage)
7. [Contributing](#contributing)
8. [License](#license)

---

## Overview

The **No Traffic System** provides a decentralized solution for managing city traffic by using data from road sensors, GPS-enabled vehicles, and AI algorithms. Each intersection operates autonomously, making decisions based on local data to reduce delays and emissions while providing safe and efficient transportation.

Key benefits include:
- Elimination of traffic jams
- Reduced carbon emissions
- Real-time rerouting to avoid congested roads
- Priority lanes for emergency vehicles

---

## Features

- **Real-Time Traffic Data Collection:** Uses IoT sensors to gather traffic data, including vehicle count, speed, and road conditions.
- **Decentralized Traffic Management:** Each intersection operates independently, adjusting traffic lights and vehicle flow based on local conditions.
- **Dynamic Rerouting:** Vehicles are rerouted in real-time to avoid congestion using AI-driven predictions.
- **Priority for Emergency Vehicles:** Automatically clears the path for emergency vehicles by optimizing traffic lights and rerouting civilian traffic.
- **Adaptive Traffic Lights:** Traffic lights adjust dynamically based on real-time traffic data to improve intersection flow.
- **Reduced Carbon Footprint:** Fewer idling vehicles result in lower emissions, contributing to a greener city.
  
---

## Technologies

- **Internet of Things (IoT):** For collecting traffic data using road sensors and GPS-enabled devices.
- **Artificial Intelligence (AI):** Machine learning models predict traffic patterns and provide optimal routes.
- **Edge Computing:** Local decision-making at intersections, reducing latency and central dependencies.
- **GPS:** Used for real-time vehicle tracking and rerouting.
- **Cloud Platform:** Central dashboard for analytics and monitoring.

---

## System Architecture

The system consists of several key components:

1. **IoT Sensors:** Deployed at key intersections to measure vehicle density, speed, and other traffic parameters.
2. **AI/ML Model:** A machine learning model predicts traffic flow based on historical and real-time data.
3. **Decentralized Traffic Control Units:** Each intersection is equipped with a traffic control unit that processes sensor data locally and adjusts signals and routes in real time.
4. **GPS & Rerouting Module:** Vehicles are rerouted based on AI predictions to optimize overall traffic flow.
5. **Emergency Priority System:** A dedicated module ensures emergency vehicles are always prioritized.
6. **Cloud Dashboard:** Provides analytics, historical traffic patterns, and system health monitoring.

---

## Installation

### Prerequisites

- **Node.js** (v14.x or later)
- **Python** (v3.8 or later)
- **Docker** (optional, for containerized deployments)
- **IoT hardware** (e.g., traffic sensors, Raspberry Pi for edge computing)

### Steps

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/no-traffic-system.git
    cd no-traffic-system
    ```

2. Install backend dependencies:
    ```bash
    cd backend
    npm install
    ```

3. Install frontend dependencies:
    ```bash
    cd frontend
    npm install
    ```

4. Run the backend server:
    ```bash
    npm start
    ```

5. Run the frontend app:
    ```bash
    cd frontend
    npm start
    ```

---

## Usage

1. Start the backend server and ensure IoT sensors are correctly configured.
2. Access the frontend dashboard at `http://localhost:3000` to monitor real-time traffic data.
3. You can simulate traffic flow or use actual sensor data to test the system's response to congestion, emergency vehicle routing, and rerouting features.

### Simulated Traffic Mode

To test the system with simulated traffic, use the provided scripts in the `/simulation` folder:
```bash
python simulate_traffic.py

