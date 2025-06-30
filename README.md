Task 5: Decision Trees and Random Forests

🎯 Objective

To build and evaluate tree-based classification models (Decision Tree & Random Forest) on a binary classification dataset for predicting the presence of heart disease.

🧰 Tools & Libraries Used
Python

Pandas

NumPy

Matplotlib / Seaborn (visualizations)

Scikit-learn (DecisionTreeClassifier, RandomForestClassifier, etc.)

Google Colab (optional)

🧪 Dataset Description
Sample Dataset Columns:

Column	Description
age	Age of the patient
sex	Sex (1 = male, 0 = female)
cp	Chest pain type (0-3)
trestbps	Resting blood pressure
chol	Serum cholesterol (mg/dl)
fbs	Fasting blood sugar > 120 mg/dl
restecg	Resting electrocardiographic results
thalach	Maximum heart rate achieved
exang	Exercise induced angina
oldpeak	ST depression induced by exercise
slope	Slope of the peak exercise ST segment
ca	Number of major vessels (0-3)
thal	Thalassemia status
target	Presence of heart disease (1 = yes, 0 = no)

🔁 Workflow
✅ Step 1: Load the Data
Upload the CSV using Google Colab's files.upload() and load into a Pandas DataFrame.

✅ Step 2: Preprocess
Separate features (X) and target (y).

Train-test split (80/20 ratio).

✅ Step 3: Train Models
Decision Tree Classifier

Limit depth (e.g., max_depth=4) to prevent overfitting.

Visualize with plot_tree().

Random Forest Classifier

Use ensemble of decision trees (e.g., n_estimators=100).

Fit and predict on test data.

✅ Step 4: Evaluate
Use classification_report, accuracy_score, and confusion_matrix.

Plot feature importances.

Perform cross-validation to validate model performance.

📈 Outputs & Metrics
📊 Decision Tree:

Visualized structure.

Classification report and accuracy.

🌲 Random Forest:

More robust accuracy.

Feature importance bar chart.

Cross-validation scores.

📌 Insights
Random Forest generally performs better due to reduced variance.

Important features (e.g., ca, thal, cp) influence predictions significantly.

Limiting tree depth helps control overfitting in decision trees.

OUTPUT

![Screenshot 2025-06-30 113421](https://github.com/user-attachments/assets/538abbd8-7878-4335-8639-523a68e4b5e7)

![Screenshot 2025-06-30 113501](https://github.com/user-attachments/assets/f0d26f81-28f1-4198-9013-b95ed619da94)

![Screenshot 2025-06-30 113408](https://github.com/user-attachments/assets/74bc362a-9d28-4644-bb39-2e3912beef59)

![Screenshot 2025-06-30 113510](https://github.com/user-attachments/assets/aa27de5d-f2ce-4a2f-b8cd-4408bfb2245c)




