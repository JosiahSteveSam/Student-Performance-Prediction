# 📊 **Student Performance Prediction**

This project involves developing an end-to-end application to predict a student's math score based on various factors. The application is designed to analyze the influence of demographic and educational attributes on academic performance and provide accurate predictions through a machine-learning model.

---

### **Key Features and Workflow**  
1. **Exploratory Data Analysis (EDA):**  
   - Conducted EDA to identify patterns and relationships in the data.  
   - Visualized trends based on factors like gender, race/ethnicity, parental education, and test preparation.  

2. **Feature Engineering:**  
   - Applied one-hot encoding to transform categorical data into a usable format.  
   - Used standard scaling to normalize numerical data for better model performance.  

3. **Machine Learning:**  
   - Evaluated multiple algorithms for predictive accuracy.  
   - Performed hyperparameter tuning to optimize model performance.  
   - Linear Regression was selected as the best-performing model with an **88% accuracy** and the lowest RMSE.  

4. **Web Application:**  
   - Built a simple and interactive user interface using Flask.  
   - Allowed users to input attributes such as gender, reading scores, and test preparation status to get predictions.  

5. **Deployment:**  
   - Hosted the application on AWS for real-time accessibility.  
   - Utilized GitHub Actions for CI/CD, Elastic Beanstalk for application hosting, and CodePipeline for automated deployment.  

---

### **Objective**  
The main goal of this project is to provide a data-driven approach to predict math scores and uncover insights into the factors affecting student performance, aiding educators and stakeholders in making informed decisions.  

---

### **Technologies Used**  
- **Programming:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Flask  
- **Deployment Tools:** AWS Elastic Beanstalk, GitHub Actions, CodePipeline  
