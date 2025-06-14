# Emotion Detection in Text using Machine Learning

This project aims to detect emotions in text using a supervised Machine Learning approach. It is developed as part of an internship assignment by **Lakhan Tomar**, a pre-final year B.Tech Computer Science student.

## 📌 Project Overview

The model classifies text into **four emotional categories**:

- 😠 Anger  
- 😄 Joy  
- 🌞 Optimism  
- 😢 Sadness

### 🧠 Approach:
- **Model Used:** Logistic Regression  
- **Feature Extraction:** TF-IDF Vectorization  
- **Dataset:** Kaggle  
- **Accuracy Achieved:** ~90.95%  
- **Evaluation Metric:** Confusion Matrix

## 📊 Sample Output

The performance of the model has been evaluated using a confusion matrix to visualize prediction accuracy across all emotion classes.

## 🧰 Tools & Technologies

- Python  
- Scikit-learn  
- Pandas & NumPy  
- Matplotlib & Seaborn (for visualization)  
- Jupyter Notebook

## 📁 Project Structure
emotion-detection/
├── data/ # Dataset files (if included)
├── notebooks/ # Jupyter notebook(s) with code and output
├── visuals/ # Confusion matrix and other visual outputs
├── emotion_detection.py # Main script (if applicable)
├── README.md # Project overview and documentation
└── Report.pdf # PDF with code walkthrough and analysis


## 📎 Resources

- 🔗 **GitHub Repository:** [Insert your GitHub link here]
- 📄 **PDF Report:** Attached in repository

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/emotion-detection.git
   cd emotion-detection
2. Install dependencies:
   pip install -r requirements.txt
3. Run the notebook:
   jupyter notebook notebooks/emotion_detection.ipynb
   
💡 Future Work
Improve model performance using advanced models (e.g., SVM, Random Forest, or Transformers like BERT)
Hyperparameter tuning for optimization
Deploy as a web app using Flask or Streamlit

👨‍💻 Author
Lakhan Tomar
B.Tech CSE – Pre-final Year
[Galgotias University]
