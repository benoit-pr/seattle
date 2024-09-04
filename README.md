# Building Energy Benchmarking Project

## Data

- **Dataset**: '2016 Building Energy Benchmarking'
- **Source**: Collected by the city of Seattle
- **Link**: [Seattle Data Portal](https://data.seattle.gov/Permitting/2016-Building-Energy-Benchmarking/2bpz-gwpy/about_data)

## Project Goal

The objectives of this project are to:
1. **Predict**:
   - **Energy Use** of a building
   - **Greenhouse Gas Emissions (GHG)**

2. **Provide Insights**:
   - **Global Feature Importance**: Understand which features generally influence the models' predictions.
   - **Local Feature Importance**: Explain the factors contributing to predictions for individual buildings.

3. **Model Exploration**:
   - Test and compare different models to achieve the best predictive performance.

## Notebooks

1. **1_Cleaning**:
   - Tasks: Data cleaning and analysis

2. **2_Modeling_EnergyUse**:
   - Tasks: Testing various models to predict **Energy Use**
   - **Models Used**: k-Nearest Neighbors (kNN), Random Forest, XGBoost...

3. **3_Modeling_GHG**:
   - Tasks: Testing various models to predict **GHG Emissions**
   - **Models Used**: k-Nearest Neighbors (kNN), Random Forest, XGBoost...

4. **4_Modeling_GHG_with_EnergyScore**:
   - Tasks: Testing different approaches to predict **GHG Emissions**, incorporating the **EnergyStarScore** feature.
   - **Models Used**: k-Nearest Neighbors (kNN), Random Forest, XGBoost...

**Note**: The best predictions are found in Notebook 4.

