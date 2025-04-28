# Electrochemical Cell ML Modeling

This project applies machine learning techniques to model the discharge performance of electrochemical cells based on key design variables.

⚡ Important:
Due to the size and complexity of the main notebook, it might not render properly on GitHub.
To easily explore the project, you can open it directly in Google Colab here: (https://colab.research.google.com/drive/19l3Di-25Cavi3ZjqGFYMi8dAUp4KfLUH?usp=sharing)

## Overview

As part of the CHEN E4580 Artificial Intelligence in Chemical Engineering course, we modeled the relationship between electrochemical cell design parameters and performance metrics such as capacity (mAh/g) and energy (mWh/g). The goal was to predict performance without running physical experiments.

## Techniques Used

- **Data Preprocessing**: Cleaning, visualization, and dimensionality reduction using PCA.
- **Regression Modeling**: Predictive modeling of target variables from input features.
- **Model Explainability**: Applied LIME and SHAP to interpret model outputs and explain feature importance.
- **Evaluation Metrics**: Assessed model performance through error metrics and validation plots.

## Features

- CRATE (Discharge rate)
- Electrode Thickness (LENGTH)
- Kinetic Reaction Rate Constant (RXNK)
- Porosity
- Effective Tortuosity
- Volume Fraction of Active Material (VFRAC_AM_PERCENT)
- Percent Active Material (PERCENT_ACTIVE)
- Conductivity
- Bulk Diffusivity (DIFF_BULK)
- Bulk Crystal Diffusivity (DIFF_C_BULK)

## Project Structure

- `notebooks/` – Jupyter notebooks for data analysis and modeling
- `src/` – Python scripts for loading data, preprocessing, training, and evaluation
- `data/` – Input datasets (features and targets)
- `README.md` – Project documentation

## How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/electrochemical-cell-ml-modeling.git
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Navigate to the `notebooks/` folder and run the main analysis notebook.

## Acknowledgements

This project is part of coursework for CHEN E4580: Artificial Intelligence in Chemical Engineering (Fall 2022).

---

For more, visit [davidernesto.io](https://davidernesto.io)!
