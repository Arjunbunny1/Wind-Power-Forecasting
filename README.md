# Wind-Power-Forecasting

## Project Overview
Wind power forecasting is crucial for grid stability and efficient energy distribution. The variability of wind energy makes accurate predictions challenging. In this project, we utilize machine learning models to improve wind power forecasting accuracy, ensuring better integration of renewable energy into power grids.

## Problem Statement
The unpredictability of wind power threatens grid stability and effective energy allocation. Reliable forecasting and optimized dispatching depend on accurate predictions. Machine learning models, such as neural networks, CNNs, and LSTMs, enhance forecasting accuracy by leveraging historical climate data.

## Dataset
We use the [Wind Turbine SCADA Dataset](https://www.kaggle.com/datasets/berkerisen/wind-turbine-scada-dataset), which contains real-time data collected from wind turbines. The dataset includes parameters such as wind speed, power output, and temperature, which are essential for training machine learning models.

## Approach
1. **Data Preprocessing:**
   - Cleaning and handling missing values
   - Feature selection and engineering
   - Normalization and scaling

2. **Model Selection:**
   - Implementing various machine learning models such as CNNs and LSTMs
   - Using deep learning techniques to enhance forecasting accuracy

3. **Training & Evaluation:**
   - Splitting data into training and testing sets
   - Evaluating model performance using error metrics (MAE, RMSE, etc.)
   - Comparing ML models with traditional statistical methods

4. **Deployment & Integration:**
   - Saving the trained model
   - Creating a pipeline for real-time predictions

## Results & Insights
- AI-driven approaches outperform traditional statistical models in wind power forecasting.
- Historical climate data significantly enhances short-term prediction accuracy.
- LSTMs and CNNs effectively capture temporal dependencies, improving model reliability.

## Installation & Requirements
To run this project, install the necessary dependencies:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow keras
```

## Acknowledgments
Special thanks to Kaggle for providing the dataset and the open-source ML community for their valuable contributions.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

