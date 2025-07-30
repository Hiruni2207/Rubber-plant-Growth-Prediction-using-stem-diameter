# 🌱 Rubber Plant Growth Prediction Using Stem Diameter

This project focuses on predicting the growth of rubber plants based on **stem diameter** using environmental features such as **temperature, moisture, irrigation level, and days after seeding**. The goal is to build a machine learning model that accurately estimates stem diameter, which serves as a key indicator of rubber plant growth in nursery management.

---

##  Key Features

- 📊 **Data-driven modeling** for predicting stem diameter
- 🤖 Machine Learning model built and saved as a `pickle` file (`predictor.pickle`)
- 📈 Evaluation metrics and plots to compare predicted vs actual stem diameter
- 🔍 Correlation analysis of growth-related parameters
- 💡 Built for agricultural decision support and smart rubber nursery management

---

##  Project Structure
│
├── Rubber.ipynb # Main notebook for analysis
├── Rubber new.ipynb # Updated version (if used)
├── Actual vs Predict.ipynb # Evaluation and visualization
├── diameter.csv # Dataset: stem diameter values
├── moisture.csv # Dataset: environmental data
├── model_evaluation_results.csv # Output metrics for model performance
├── correlation_matrix_heatmap.png # Heatmap visualization
├── predictor.pickle # Trained model (saved as .pkl)
└── README.md # Project documentation (you are here)


---

##  Methodology

1. **Data Preprocessing**: Merged and cleaned CSV files for modeling.
2. **Exploratory Data Analysis**:
   - Correlation heatmap to identify key features.
   - Visual inspection of trends and outliers.
3. **Modeling**:
   - Trained machine learning model (e.g., Linear Regression, Random Forest, etc.)
   - Saved using `pickle` for future predictions.
4. **Evaluation**:
   - Compared predicted vs actual stem diameter using metrics like MAE, RMSE.
   - Plotted residuals and actual vs predicted values.

---

##  How to Use

1. Clone the repository:
```bash
git clone https://github.com/Hiruni2207/Rubber-plant-Growth-Prediction-using-stem-diameter.git
cd Rubber-plant-Growth-Prediction-using-stem-diameter

