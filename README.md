# Reservoir and Well Classification Using Machine Learning

An end-to-end machine learning and deep learning project for intelligent classification of oil and gas reservoirs and wells using production, pressure, and operational data.

This project applies data analytics, feature engineering, classical machine learning, and recurrent neural networks (RNN/LSTM) to classify:

- Reservoir type
- Saturation status
- Gas-Oil Ratio (GOR) trend
- Well type (Natural Flow or Gas Lift)
- Production behavior (Steady or Unsteady)
- Water cut trend

The repository demonstrates how artificial intelligence can support reservoir surveillance, production optimization, and decision-making in petroleum engineering.

---

# Project Overview

Oil and gas production systems generate large volumes of operational and reservoir data. Interpreting these datasets manually is time-consuming and often inefficient.

This project introduces a data-driven workflow that combines:

- Exploratory Data Analysis (EDA)
- Feature Engineering
- Supervised Machine Learning
- Deep Learning for Time-Series Analysis
- Reservoir and Well Classification Logic

The objective is to automate well and reservoir characterization using historical production and pressure data.

---

# Key Features

## Exploratory Data Analysis (EDA)

The notebook performs detailed EDA including:

- Missing value inspection
- Duplicate analysis
- Statistical summaries
- Pressure trend analysis
- Choke size distribution
- Cumulative oil and gas production analysis
- Water cut trend analysis
- GOR trend analysis

---

## Feature Engineering

Custom petroleum engineering features were created, including:

- Gas-Oil Ratio (GOR)
- Water Cut
- Well production time
- Cumulative production indicators
- Pressure-related features

---

## Machine Learning Models

The project implements several ML and DL models for different classification objectives.

### Classical Machine Learning

- Linear Regression
- Random Forest Regressor
- Feature Scaling
- One-Hot Encoding

### Deep Learning Models

- Recurrent Neural Networks (RNN)
- Long Short-Term Memory Networks (LSTM)

These models are used for time-dependent classification and production trend analysis.

---

# Classification Tasks

## 1. Reservoir Type Classification

Classifies wells based on reservoir characteristics.

---

## 2. Saturation Classification

Determines whether a reservoir is:

- Saturated
- Undersaturated

---

## 3. GOR Trend Classification

Analyzes Gas-Oil Ratio behavior and reservoir performance trends.

---

## 4. Well Type Classification

Classifies wells as:

- Natural Flow (NF)
- Gas Lift (GL)

using:

- Annulus Pressure
- Formation Gas Production
- Total Gas Production
- Operational indicators

---

## 5. Production Type Classification

Determines whether production behavior is:

- Steady
- Unsteady

using sequential production data.

---

## 6. Water Cut Trend Classification

Uses time-series deep learning models to analyze:

- Increasing water cut
- Stable water cut
- Declining water cut

---

# Repository Structure

```bash
Reservoir-and-Well-Classifiction-Using-Machine-Learning-
│
├── Reservoir_and_well_Classification.ipynb
├── README.md
└── dataset/
```

---

# Technologies Used

## Programming Language

- Python

## Data Analysis Libraries

- NumPy
- Pandas
- Matplotlib
- Seaborn

## Machine Learning Libraries

- Scikit-learn

## Deep Learning Frameworks

- TensorFlow
- Keras

---

# Workflow

```text
Data Collection
        ↓
Data Cleaning
        ↓
Feature Engineering
        ↓
Exploratory Data Analysis
        ↓
Data Preprocessing
        ↓
Machine Learning Modeling
        ↓
Deep Learning Modeling
        ↓
Reservoir and Well Classification
        ↓
Prediction & Visualization
```

---

# Dataset Features

The project utilizes production and operational parameters such as:

| Feature | Description |
|---|---|
| WELL_NAME | Name/identifier of the well |
| BOTTOM_FLOWING_PRESSURE | Bottom-hole flowing pressure |
| ANNULUS_PRESSURE | Annulus pressure |
| CHOKE_SIZE | Choke opening size |
| OIL_PRODUCTION | Oil production rate |
| GAS_PRODUCTION | Gas production rate |
| FORMATION_GAS | Formation gas produced |
| WATER_PRODUCTION | Water production |
| PRODUCTION_DATE | Production timestamp |
| GOR | Gas-Oil Ratio |
| WATER_CUT | Water cut percentage |

---

# Model Pipeline

## Data Preprocessing

The notebook includes:

- Date standardization
- Numeric conversion
- Missing value handling
- One-hot encoding
- Feature scaling
- Train-test splitting

---

## Training Process

The workflow applies:

- Z-score normalization
- Min-Max scaling
- Sequential learning for time-series data
- Regression-based prediction
- Classification logic for petroleum engineering interpretation

---

# Visualizations

The project generates multiple engineering visualizations including:

- Pressure trends per well
- Choke size trends
- Cumulative production curves
- Water cut trends
- GOR trends
- Actual vs predicted model outputs
- Time-series prediction plots

---

# Example Applications

This project can support:

- Reservoir surveillance
- Production optimization
- Artificial lift monitoring
- Intelligent field management
- Production forecasting
- Early water breakthrough detection
- Data-driven reservoir characterization
- Digital oilfield development

---

# Installation

Clone the repository:

```bash
git clone https://github.com/MSunusi/Reservoir-and-Well-Classifiction-Using-Machine-Learning-.git
```

Move into the project directory:

```bash
cd Reservoir-and-Well-Classifiction-Using-Machine-Learning-
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

# Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```bash
Reservoir_and_well_Classification.ipynb
```

Run all cells sequentially.

---

# Future Improvements

Potential future developments include:

- Real-time reservoir monitoring dashboards
- Deployment as a web application
- Integration with SCADA systems
- Advanced deep learning architectures
- Explainable AI (XAI)
- Hybrid physics-informed AI models
- Automated anomaly detection
- Cloud deployment for field operations

---

# Research and Engineering Significance

This work demonstrates how AI and machine learning can be integrated into petroleum engineering workflows to improve:

- Reservoir understanding
- Production diagnostics
- Well performance monitoring
- Operational efficiency
- Data-driven decision-making

The project also highlights the growing role of digital transformation and intelligent systems in the oil and gas industry.

---

# Author

## Sunusi Ibrahim Muhammad

Petroleum Engineer | Machine Learning Researcher | Computer Vision Developer

### Research Interests

- Reservoir Engineering
- Machine Learning for Energy Systems
- Deep Learning
- Computer Vision
- AI for Petroleum Engineering
- Digital Oilfield Technologies
- Multimodal

GitHub: https://github.com/MSunusi

---

# Contributing

Contributions are welcome.

If you would like to improve the project:

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Push to the branch
5. Open a pull request

---

# License

This project is released under the MIT License.

---

# Citation

If you use this project in your research or academic work, kindly cite:

```bibtex
@misc{sunusi_reservoir_ml,
  author       = {Sunusi Muhammad Ibrahim},
  title        = {Reservoir and Well Classification Using Machine Learning},
  year         = {2026},
  publisher    = {GitHub},
  journal      = {GitHub Repository},
  howpublished = {\url{https://github.com/MSunusi/Reservoir-and-Well-Classifiction-Using-Machine-Learning-}}
}
```

---

# Acknowledgements

Special appreciation to the EJAZTECH.AI team,  open-source community and the petroleum engineering and AI communities advancing intelligent energy systems.
