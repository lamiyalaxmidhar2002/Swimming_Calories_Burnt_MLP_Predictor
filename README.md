
# Swimming Calories Burnt Predictor (MLP Regression)

##  Overview  
This project demonstrates how to use a **Multi-Layer Perceptron (MLP) regression model** to predict calories burnt during swimming workouts.  
The model uses biometric and workout-related features (e.g., duration, distance, age, weight, heart rate) to learn non-linear relationships and provides accurate calorie burn predictions.  

---

##  Methodology
1. **Data Preparation**  
   - Cleaned and normalized input data.  
   - Selected 5+ biometric/workout features.  

2. **Modeling**  
   - Implemented an **MLP Regression model** using XGBoost Regressor.  
   - Tuned hidden layers, activation functions, and optimizer.  

3. **Evaluation**  
   - Compared against a baseline linear regression model.  
   - Achieved **R² = 0.979** on the test set.  

---

## Results
- The MLP model captured **non-linear feature interactions** more effectively than linear regression.  
- Visualizations (predicted vs. actual calories) confirmed strong alignment.  

---
