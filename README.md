📝 Project Report: Student Performance Prediction
Objective:
Developed a predictive model to estimate student marks based on study hours using Linear Regression. This project follows a standard data science pipeline: Data Creation → Preprocessing → Training → Evaluation → Prediction.

1. Model Methodology
Algorithm: Linear Regression (Ordinary Least Squares).
Features: Independent Variable (X) = Hours Studied; Dependent Variable (y) = Marks Scored.
Data Split: 80% Training, 20% Testing to ensure the model generalizes well to unseen data.
2. Key Performance Metrics
Mean Squared Error (MSE): Measures the average squared difference between estimated values and the actual value. (Lower is better).
R-squared (R2
): Quantifies how well the regression line fits the data points. Your model shows a high R2
, indicating a strong positive correlation.
3. Visual Analysis
Shutterstock
Explore
### 📊 Model Visualization
![Student Marks Prediction Plot](image_92abba.png)

*The blue dots represent actual student data, and the red line shows our model's predicted trend.*

The Blue Scatter Points represent the actual data distribution.
The Red Regression Line represents the model's prediction path.
The tight clustering of points around the line confirms that the model has high predictive accuracy for this linear dataset.
4. Sample Prediction
Input: 5.0 Hours
Predicted Output: 54.42 Marks
