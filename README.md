  # Maharashtra Climatic Trends: Exploratory Data Analysis

## 📌 Project Overview
This project provides a comprehensive analysis of historical weather data across major urban centers in Maharashtra, India. The primary objective was to transform raw, inconsistent meteorological data into a clean, actionable dataset to identify regional climatic variations and trends.

## 🛠️ Key Technical Features
* **Data Pipeline & Cleaning**: Standardized temporal data formats and optimized column schemas for efficient querying.
* **Advanced Imputation Strategy**: Addressed data sparsity by implementing city-wise mean imputation for `Average Temperature`, `Minimum Temperature`, and `Sunshine Duration`, ensuring data integrity without introducing global bias.
* **Statistical Analysis**: Conducted descriptive analytics to identify extremes in precipitation and temperature ranges across diverse geographical zones (Coastal vs. Inland).
* **Outlier Management**: Performed rigorous data pruning, including the removal of low-confidence records (e.g., Ichalkaranji) to improve the reliability of the overall model.

## 📊 Dataset Specifications
The analysis utilizes a multi-city dataset (`cities_weather_maharashtra.csv`) containing:
- **Temporal Data**: Date-indexed records from 2020 to 2025.
- **Thermal Metrics**: Daily Average (`avg`), Minimum (`min`), and Maximum (`tmax`) temperatures.
- **Atmospheric Metrics**: Precipitation (`prcp`), Pressure (`pres`), and Sunshine (`sun`).
- **Geospatial Scope**: 36 unique cities across the state of Maharashtra.

## 💻 Technologies Used
- **Language**: Python 3.x
- **Data Manipulation**: `Pandas`, `NumPy`
- **Visualization**: `Matplotlib`, `Seaborn`
- **Environment**: Jupyter Notebook / Google Colab

## 🚀 Getting Started

### Prerequisites
Ensure you have Python installed, then install the required dependencies:
```bash
pip install pandas 
pip install numpy
pip install matplotlib
pip install seaborn
