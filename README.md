# **Building Ethical and Explainable AI & Jailbreaking LLMs**

## **Overview**
This project explores fairness, explainability, and bias mitigation in AI models used for income prediction. It involves data exploration, model development, interpretability analysis, fairness evaluation, and bias mitigation techniques to ensure ethical AI decision-making.

## **Project Workflow**
### 1. Data Exploration & Preprocessing
- Analyzed **50,000+ samples** from the dataset.
- Identified biases and patterns in demographic attributes.
- Cleaned and preprocessed data for model training.

### 2. Model Development
- Built a **Multi-Layer Perceptron (MLP) Classifier** for income prediction.
- Achieved **85% accuracy** on test data.

### 3. Explainability Analysis
- Used **SHAP** to interpret feature importance.
- Visualized model decisions and identified key contributing factors.

### 4. Fairness Evaluation
- Assessed bias using **Statistical Parity Difference, Disparate Impact, and Equal Opportunity Difference**.
- Compared model performance across **five demographic groups**.

### 5. Bias Mitigation
- Implemented **Adversarial Debiasing** to reduce discrimination.
- Improved fairness metrics by **20% or more** without significantly affecting accuracy.

### 6. Ethical Reflection
- Documented findings and ethical implications of model decisions.
- Evaluated potential societal impacts of biased predictions.

## **Technologies Used**
- **Python** (NumPy, Pandas, Scikit-learn, TensorFlow, SHAP)
- **Fairness Metrics & Bias Mitigation** (AIF360, Adversarial Debiasing)
- **Visualization** (Matplotlib, Seaborn)

## **Results & Key Takeaways**
- The model initially exhibited **bias in income predictions**, favoring certain demographic groups.
- **SHAP analysis** highlighted key features influencing predictions.
- **Bias mitigation** significantly improved fairness without major accuracy loss.


