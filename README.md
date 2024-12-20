# 📊 Student Performance Prediction

This repository contains an end-to-end application developed to predict student performance in math scores based on various attributes. The project aims to provide insights into how factors like demographics, parental education, and preparation impact academic performance, and leverages machine learning for predictive analysis.

---

## 🚀 **Features**
- **End-to-End Workflow**: Clean modular code structure to ensure scalability and maintainability.
- **Exploratory Data Analysis (EDA)**: Identified patterns and relationships between attributes.
- **Feature Engineering**: Applied:
  - One-hot encoding for categorical variables.
  - Standard scaling to normalize numerical data.
- **Machine Learning**:
  - Experimented with various algorithms.
  - Performed hyperparameter tuning.
  - Achieved **88% accuracy** with Linear Regression (best RMSE value).
- **Flask Web Application**: Created a user-friendly interface to input attributes and view predictions.
- **Deployment**: Hosted the application on AWS using:
  - **GitHub Actions** for CI/CD.
  - **Elastic Beanstalk** and **CodePipeline** for deployment.

---

## 🧑‍💻 **How It Works**
1. Input student details such as:
   - Gender
   - Race/Ethnicity
   - Parental Level of Education
   - Type of Lunch Before Exam
   - Test Preparation Course Status
   - Reading and Writing Scores
2. The application predicts the student's math score using a trained Linear Regression model.

---

## 📂 **Project Structure**
student-performance-prediction/ ├── app/ # Flask application files ├── data/ # Dataset for training and testing ├── notebooks/ # EDA and model development notebooks ├── models/ # Trained machine learning models ├── static/ # Static files for the web app (CSS, JS) ├── templates/ # HTML templates for Flask ├── requirements.txt # Python dependencies ├── Dockerfile # Docker configuration for deployment └── README.md # Project documentation


---

## 🛠️ **Technologies Used**
- **Programming Languages**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Flask
- **Deployment**: AWS (Elastic Beanstalk, CodePipeline), GitHub Actions
- **Version Control**: Git

---

## 📈 **Key Results**
- **Linear Regression** emerged as the best model with an RMSE value achieving 88% accuracy.
- Significant insights into the factors influencing student performance were derived through EDA.

---

## 💻 **Getting Started**
### **Prerequisites**
- Python 3.8+
- AWS account
- Docker (optional for containerized deployment)

### **Installation**
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/student-performance-prediction.git
   cd student-performance-prediction

