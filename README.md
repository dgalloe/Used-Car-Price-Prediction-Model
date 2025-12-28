# Used-Car-Price-Prediction-Model
Developed machine learning models to predict used car prices for Rusty Bargain's customer valuation app. Evaluated multiple algorithms based on prediction quality, speed, and training time to balance business requirements and performance.

## 1. Objectives 🎯
- Build predictive models to determine market value of used cars
- Evaluate model performance using RMSE metric
- Balance prediction quality, prediction speed, and training time requirements
- Test multiple machine learning approaches (Linear Regression, Random Forest, Gradient Boosting)
- Prepare and clean automotive sales data for modeling

## 2. Key Findings 🏆
- Gradient Boosting models (CatBoost, LightGBM, XGBoost) provided best prediction accuracy
- Linear Regression trained fastest but had poorest predictive performance
- Random Forest offered good balance between speed and accuracy
- Feature importance analysis revealed key price determinants:
- Vehicle age (registration year) most significant
- Power (engine performance) strongly correlated with price
- Vehicle type and brand significantly impact valuation
- Data cleaning required handling missing values in categorical features (vehicle_type, gearbox, model, fuel_type)
- Model evaluation showed consistent trade-offs between computational efficiency and predictive power

## 3. Visualizations Included 🎨
- Missing value distribution across dataset features
- Gearbox type distribution (manual vs automatic)
- Fuel type distribution across vehicle listings
- Feature importance analysis from tree-based models
- Model performance comparison charts
- Prediction error distributions

## 4. Skills Demonstrated 🛠️
- Data Preparation: Missing value imputation, feature renaming, data type handling
- Machine Learning: Implementation of regression algorithms (Linear, Random Forest, Gradient Boosting)
- Model Evaluation: RMSE calculation, training time measurement, prediction speed assessment
- Feature Engineering: Categorical encoding, numeric feature analysis
- Data Visualization: Distribution plots, categorical analysis, performance comparisons
- Business Requirements Analysis: Balancing technical metrics with practical business needs
- Model Optimization: Hyperparameter consideration and algorithm selection

## 5. Technical Details 💻
- Programming Language: Python
- Main Libraries: pandas, scikit-learn, LightGBM, CatBoost, XGBoost, matplotlib, seaborn
- Dataset: 354,369 used car listings with 16 features including technical specifications and pricing
- Evaluation Metric: Root Mean Square Error (RMSE)
- Key Features: Vehicle type, registration year, gearbox, power, model, mileage, fuel type, brand, repair status
- Models Tested: Linear Regression, Random Forest Regressor, LGBMRegressor, CatBoostRegressor, XGBRegressor
- Performance Dimensions: Prediction quality, prediction speed, training time

## 6. Installation and Usage
```bash
# Clone the repository
git clone https://github.com/yourusername/used-car-price-prediction.git

# Navigate to project directory
cd used-car-price-prediction

# Install required dependencies
pip install -r requirements.txt

# Run the analysis notebook
jupyter notebook used_car_price_prediction.ipynb
