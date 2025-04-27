# Machine-learning-project

---

### 📚 Data Preparation
1. **Load the Dataset**:  
   The file `email_phishing.csv` is loaded into a pandas DataFrame.

2. **Data Splitting**:  
   Features (`x`) and target labels (`y`) are separated.

3. **Feature Scaling**:  
   Standardization is applied using `StandardScaler` to ensure all features have similar scales.

4. **Train-Test Split**:  
   The dataset is split into training and testing sets for model evaluation.

---

### 🤖 Model Training
5. **Model Initialization & Training**:  
   Different machine learning models are trained — like:
   - Logistic Regression
   - Decision Trees
   - Random Forests
   - SVMs
   - Gradient Boosting, etc.

6. **Hyperparameter Tuning** (optional based on deeper code inspection):  
   Grid Search (`GridSearchCV`) may be used to find the best hyperparameters.

---

### 🎯 Model Evaluation
7. **Performance Metrics**:
   - Models are evaluated using **accuracy scores**, **confusion matrices**, and **classification reports**.

---

### 🎨 Visualization
8. **Decision Boundary Plotting**:
   - Visualization of the decision regions to show how models classify different regions.
   - Use of `mlxtend` library for 2D plotting.

