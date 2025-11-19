# Bike Sharing Demand Prediction (Hourly)  
**INFO40975 - Final Project**  
**Syeda Iman Kamran**  
**Project #8 - Regression Task**

---

### Abstract  
This project focuses on analyzing and predicting hourly bike rentals and their demand using the UCI Bike Sharing Dataset’s hour.csv. The task is to use regression and predict the total number of bikes that will be rented depending on the season, weather, time and more. Using the AutoML library PyCaret, many regression models were created and Light Gradient Boosting Machine took over as the best model. The final model had a high R2 value showing that 95% of the predictions were correct and only an error of 26 bikes on average. These predictions were very accurate and useful for understanding where more bikes should be stationed in a city.

---

### Video Presentation (5 minutes)  
[Link](https://www.youtube.com/watch?v=RX5hzq6usJo)  

---

### Project Overview  
- **Dataset**: UCI Bike Sharing Dataset - hourly data (`hour.csv`)  
- **Goal**: Predict total number of bikes rented per hour (`cnt`)  
- **Important rule**: Did NOT use `casual` and `registered` columns (they would cause data leakage/cheating)  
- **Tool used**: PyCaret (AutoML)  
- **Best model**: Light Gradient Boosting Machine (LightGBM)  
- **Final performance** (on unseen test data):  
  - R² = 0.9497 (95% accurate)  
  - MAE ≈ 26 bikes per hour  

### How to Run  
1. Open the notebook `AI_Project_SyedaImanKamran.ipynb`  
2. Run all cells from top to bottom  
3. Works with Python 3 + PyCaret 3.3.2  

### License  
MIT License - free to use, share, and fork!
