# Climate CO₂ Forecast ML

A machine learning project focused on forecasting carbon dioxide (CO₂) emissions to support **SDG 13: Climate Action**.  
This project uses open-source data from **Our World in Data** and Python tools to build predictive models that help visualize and understand CO₂ trends worldwide.

---

## Project Objectives

- Predict future CO₂ emissions using supervised learning (regression models)
- Identify key indicators influencing CO₂ emissions (e.g., population, GDP)
- Visualize emissions trends to support data-driven climate action
- Reflect on ethical and sustainability considerations in AI

---

## Dataset

- **Source**: [Our World in Data - CO₂ and Greenhouse Gas Emissions](https://ourworldindata.org/co2-emissions)
- **Format**: CSV
- **Main Features Used**:
  - `year`
  - `country`
  - `co2` (total CO₂ emissions)
  - `gdp`
  - `population`
  - `energy_per_capita`
  - `renewables_share_energy`

---

## Tools & Technologies

- **Python**
- **Jupyter Notebook**
- **Libraries**:
  - `Pandas`, `NumPy` – Data manipulation
  - `Matplotlib`, `Seaborn` – Visualization
  - `Scikit-learn` – Machine learning (regression models)

---

## Workflow Overview

1. Load and clean the dataset  

[Data Preview](screenshots/data_preview.png)

2. Select relevant features  
3. Handle missing data  
4. Split into train/test sets  
5. Train regression models (Linear Regression, Random Forest)  
6. Evaluate performance using MAE, RMSE, and R²  

[Model Metrics](SCREENSHOTS/MODEL%20PERFORMANCE%20METRICS.png)

7. Visualize predictions vs actual values  

[Actual vs Predicted](SCREENSHOTS/ACTUAL%20VS%20PREDICTED%20CO2%20EMISSIONS.png)

8. Reflect on bias and fairness

[Ethical Reflection](SCREENSHOTS/ETHICAL%20REFLECTION%20SECTION.png)
---
## Machine Learning Approach
- Model Used: Linear Regression
- Features: Year, GDP, population, energy source emissions, carbon intensity metrics
-Target: Total CO₂ emissions (co2)
- Evaluation Metrics: MAE, RMSE, R² Score

## Results

The model performs reasonably well on historical emissions data.

Strong correlation observed between fossil fuel sources and total CO₂ output.

Useful for forecasting trends and informing high-level sustainability decisions.

*(Detailed results in the Jupyter Notebook)*

---

## Ethical Considerations

- Data bias: Some countries have limited reporting quality
- Promoting fairness: Model built to encourage global climate justice
- Sustainability: Insight generation for informed carbon reduction policies

---

## How to Run

1. Clone the repository:
   ```bash
   git clone `git@github.com:HellenDianaNjeri/CLIMATE_CO2-FORECAST.git`
   cd CLIMATE_CO2-FORECAST

2. Install dependencies

`pip install -r requirements.txt`

3. Lauch Jupyter Notebook

`jupyter notebook CO2_Forecast.ipynb`