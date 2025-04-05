# 🌬️ Wind Energy Analytics Dashboard


An AI-powered dashboard for wind energy analysis, turbine performance simulation, and wind speed forecasting.


## 🚀 Features

- **Real-time Wind Analysis**
  - Open-Meteo API integration for live weather data
  - Wind speed/direction visualization (Weibull distributions, wind roses)
  - Air density calculations based on temperature/humidity

- **Turbine Performance Simulation**
  - 5+ commercial turbine models (Vestas, GE, Suzlon, Enercon)
  - Customizable turbine parameters (cut-in/rated/cut-out speeds)
  - Power curve visualization with air density corrections

- **AI Forecasting**
  - Random Forest model (R²=0.92) for 48-hour wind predictions
  - Confidence intervals for forecast reliability
  - Energy output projections with capacity factor analysis

## 🛠️ Technologies

```python
import streamlit  # Web dashboard
import plotly  # Interactive visualizations
import scikit-learn  # Machine learning (Random Forest)
import pandas  # Data processing
import numpy  # Numerical calculations
from windrose import WindroseAxes  # Wind direction plots


[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://usxtmpzozcrxezyfavzhcc.streamlit.app/)
