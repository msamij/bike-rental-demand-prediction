# Advertising Bike Rental Demand Prediction - Descision Tree Regression

## Datacrumbs Assignment 17

## Project Overview

- In this project, you will build a Decision Tree Regression model to predict the number of bike rentals based on weather and seasonal conditions. This helps understand how environmental factors influence urban mobility demand.

## Dataset: [Bike Rental Dataset](https://drive.google.com/file/d/1-v1qhOk08UVUBKhFqqp2kM8Dx4y5pfSE/view?usp=sharing)

- **Features**: temp, humidity, windspeed, season
- **Target**: count
- **Format**: CSV

## Download the dataset and extract it to project root/dataset

## Project Structure

```text
├── dataset/
│   └── data.csv                 # Advertising dataset
├── assignment.ipynb  # Jupyter notebook with model training
├── model.pkl                    # Saved trained model
└── README.md                    # Project documentation
```

## Quick Start

### 1. Installation

Clone the repository:

```bash
git clone https://github.com/msamij/advertising-sales-prediction
cd advertising-sales-prediction
```

Install dependencies:

```bash
# 1. Creates an environment.
python3 -m venv .venv

# 2. Activate the environment.
source .venv/bin/activate

# 3. Install packages.
pip install -r requirements.txt
```

### 2. Train the Model

Run the Jupyter notebook to train the model:

```bash
jupyter notebook assignment.ipynb

# Or run directly in vscode.
```

## Model Performance

| Metric       | Training Set | Test Set    |
| ------------ | ------------ | ----------- |
| **R² Score** | 0.8695       | **0.8351**  |
| **RMSE**     | 28.9159      | **44.5184** |
| **MAE**      | 22.8240      | **35.0216** |

- Model trained and evaluated (Jupyter Notebook)
- Documentation provided (README)

---

**Author**: Muhammad Sami  
**Created**: April 2026
