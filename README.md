# Data-Driven Monitoring of Power Distribution Systems

This is the project repository for the course **EE-272 (Exploratory Project), Semester 4**.

## Project Overview

This project focuses on data-driven approaches for monitoring power distribution systems. The key objectives are:

- **Modeling**: Simulating power distribution networks using OpenDSS.
- **Data Generation**: Creating datasets via Monte Carlo simulations and OpenDSS Python abstraction.
- **Monitoring Techniques**: Implementing various machine learning models for system monitoring.

## Methodology

The project is divided into three main phases:

1. **Modeling Power Distribution Systems**

   - Use OpenDSS to model IEEE 33-bus and IEEE 69-bus distribution systems.
   - Define network parameters and characteristics for accurate simulation.

2. **Data Generation via Simulation**

   - Employ Monte Carlo simulations to create diverse datasets.
   - Utilize OpenDSS Python module to streamline the simulation process.

3. **Machine Learning for System Monitoring**
   - Implement and compare multiple ML-based monitoring techniques:
     - **Fuzzy Logic**
     - **Random Forest (RF)**
     - **Artificial Neural Networks (ANN)**
     - **k-Nearest Neighbors (kNN)**
     - **Long Short-Term Memory (LSTM)**
     - **Convolutional Neural Networks (CNN)**

## Getting Started

### Prerequisites

Ensure you have the following dependencies installed:

```bash
pip install -r requirements.txt
```

### Running the Simulations

1. Set up OpenDSS and configure the IEEE 33/69-bus models.
2. Run the Monte Carlo simulation scripts to generate datasets.
3. Train ML models using the generated datasets.

## Results & Analysis

- Performance evaluation of different ML models.
- Comparison of traditional vs. ML-based monitoring techniques.
- Visualization of predictions and system behavior.

## Future Work

- Enhancing dataset quality with more realistic variations.
- Exploring graph based techniques for system monitoring of nodes and buses.
- Implementing real-time monitoring using edge computing.

## Contributors

- **Sakshi Kumar**
- **Chhavi Jhari**
