# -Logistic-Regression
1. **Load & Clean Dataset**
   - Drop unnecessary columns (`id`, `Unnamed: 32`)
   - Encode target (`M` → 1, `B` → 0)

2. **Train/Test Split**
   - 80% training, 20% testing

3. **Feature Scaling**
   - Standardization using `StandardScaler`

4. **Model Training**
   - Logistic Regression

5. **Model Evaluation**
   - Confusion Matrix
   - Precision, Recall, F1-score
   - ROC Curve & AUC Score

6. **Threshold Tuning**
   - Explore how changing the classification threshold affects precision and recall

7. **Sigmoid Explanation**
   - Visualize the sigmoid function used by logistic regression

---

##  Outputs

- Confusion matrix heatmaps
- ROC curve
- Precision/Recall vs. Threshold plot
- Sigmoid function curve
