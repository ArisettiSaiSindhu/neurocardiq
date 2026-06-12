Developed an AI-driven healthcare system for early mental health risk assessment by analyzing multimodal physiological signals from the brain (EEG) and heart (ECG). The project leverages the DREAMER dataset to extract neurological and cardiac features associated with emotional and psychological states such as stress, anxiety, and depression.

Implemented signal preprocessing, feature extraction, and brain–heart interaction modeling techniques to capture the relationship between neural and cardiac responses. Combined EEG features, ECG-derived Heart Rate Variability (HRV) metrics, and interaction-based features through feature fusion to improve prediction performance.

Built and evaluated machine learning models including Random Forest and XGBoost, achieving 97.58% accuracy in mental health risk classification. Integrated SHAP (SHapley Additive Explanations) to provide interpretable predictions and identify the most influential physiological features contributing to risk assessment.

Designed and deployed a Flask-based web application that enables users to upload EEG and ECG signal images, perform real-time analysis, visualize prediction confidence, track historical assessments, and receive personalized mental health recommendations. Implemented SQLite-based backend storage for user authentication, prediction history management, and monitoring.
