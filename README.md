Personality Detection from Resume using Machine Learning

An intelligent Machine Learning project that predicts a candidate’s MBTI personality type from resume data using NLP and classification algorithms. This project combines resume parsing, text preprocessing, TF-IDF feature extraction, and machine learning models to automate personality analysis for recruitment and career alignment.

📌 Project Overview

Traditional recruitment mainly focuses on technical skills and qualifications. This project extends the hiring process by analyzing resumes to predict personality traits based on the Myers-Briggs Type Indicator (MBTI) framework.

The system processes resume text, extracts meaningful features, and predicts one of the 16 MBTI personality types such as:

INTJ
ENFP
INFJ
ESTJ
ENTP
and more.

The project also compares multiple ML models to determine the most effective approach for personality prediction.

🚀 Features
Resume text preprocessing and cleaning
TF-IDF based feature extraction
MBTI personality classification
Logistic Regression implementation
Random Forest implementation
K-Means Clustering
Hierarchical Clustering
Confusion Matrix visualization
ROC Curve analysis
Accuracy comparison plots
Label encoding for MBTI classes
🧠 MBTI Personality Framework

The project uses the MBTI model consisting of 4 dimensions:

E / I → Extroversion vs Introversion
S / N → Sensing vs Intuition
T / F → Thinking vs Feeling
J / P → Judging vs Perceiving

These combine into 16 unique personality types.

📂 Dataset
Dataset Source: Kaggle
Total Records: ~9,500 resumes
Features include:
Skills
Education
Certifications
Career Objective
Job Position
Responsibilities
Experience
Target Variable:
MBTI Personality Type

⚙️ Technologies Used
Programming Language
Python
Libraries
pandas
numpy
scikit-learn
matplotlib
seaborn
nltk
scipy
ML & NLP Techniques
TF-IDF Vectorization
Label Encoding
Chi-Square Feature Selection
Logistic Regression
Random Forest
K-Means Clustering
Hierarchical Clustering
🔄 Project Workflow
Data Collection
Data Cleaning
Text Normalization
Stopword Removal
Lemmatization
TF-IDF Feature Extraction
Feature Selection
Model Training
Model Evaluation
Personality Prediction

🧹 Data Preprocessing

The preprocessing pipeline included:

Lowercasing text
Removing punctuation and numbers
Stopword removal
Tokenization
Lemmatization
Outlier handling
Vocabulary construction
TF-IDF vectorization

After preprocessing, resumes were transformed into numerical vectors suitable for ML models.

🤖 Machine Learning Models
1. Logistic Regression
Best balance between accuracy and interpretability
Final selected model
2. Random Forest
High performance
Slight overfitting observed
3. K-Means Clustering
Unsupervised grouping of resumes
4. Hierarchical Clustering
Dendrogram-based clustering analysis

📊 Model Performance
Model	Accuracy
Logistic Regression	78%
Random Forest	80%
K-Means	~25%
Hierarchical Clustering	~22%

Although Random Forest achieved slightly higher accuracy, Logistic Regression was selected as the final model due to better generalization and lower overfitting.

📈 Evaluation Metrics

The models were evaluated using:

Accuracy
Precision
Recall
F1-Score
ROC Curve
AUC Score
Confusion Matrix

📷 Visualizations

The project includes:

Word Clouds
ROC Curves
Confusion Matrices
Accuracy Comparison Graphs
Dendrograms
Null Value Heatmaps
🏗️ Future Improvements
Deep Learning implementation (LSTM/BERT)
Better resume parsing
Multi-language support
Improved personality prediction accuracy
Real-time web deployment
Better handling of class imbalance
📌 Conclusion

This project demonstrates how NLP and Machine Learning can be combined to automate personality prediction from resumes. By using TF-IDF feature extraction and Logistic Regression, the system achieved reliable performance while maintaining interpretability and efficiency.

The project highlights the importance of preprocessing and feature engineering in text-based ML applications and provides a strong foundation for AI-driven recruitment systems.
