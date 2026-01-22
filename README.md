# Task 5: Train-Test Split & Evaluation Metrics - Heart Disease Prediction

### Project Overview
This project involves building a classification model using **Logistic Regression** to predict the presence of heart disease. The primary focus of this task was to implement a proper **Train-Test Split** and evaluate the model using multiple performance metrics beyond simple accuracy.

---

### Implementation Steps
Following the "Mini Guide" provided by Elevate Labs:
1. **Data Splitting:** Divided the dataset into **Training (80%)** and **Testing (20%)** sets. 
   - *Purpose:* Training data is used to teach the model patterns, while testing data acts as unseen data to evaluate how well the model generalizes.
2. **Model Training:** Implemented a **Logistic Regression** model using Scikit-Learn.
3. **Prediction:** Generated predictions on the test set to compare against actual results.
4. **Evaluation:** Calculated the following metrics:
   - **Accuracy:** Overall correctness.
   - **Precision:** The ratio of true positive heart disease cases to all predicted positives.
   - **Recall:** The ability of the model to identify all actual cases of heart disease.
5. **Confusion Matrix:** Created a matrix to visualize True Positives, True Negatives, False Positives, and False Negatives.

---

### Evaluation Results & Insights
* **Model Performance:** The model achieved high scores across all metrics, indicating it is well-suited for this binary classification task.
* **Recall Importance:** In a medical context, **Recall** is critical. A high recall ensures that we minimize "False Negatives" (missing a patient who actually has heart disease).
* **Confusion Matrix Analysis:** The matrix shows that the model successfully distinguished between healthy and diseased patients with minimal errors.



---

### Deliverables
* `Elevate_Labs_Task_5.ipynb`: Jupyter Notebook containing the code, training process, and evaluation charts.
* `heart.csv`: The Heart Disease dataset used for this analysis.
* `README.md`: Project documentation and results interpretation.

---

### Technologies Used
* **Python**
* **Pandas** (Data Handling)
* **Scikit-Learn** (Model Training & Evaluation Metrics)
