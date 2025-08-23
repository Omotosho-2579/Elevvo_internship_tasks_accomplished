🎓 Student Score Prediction

This project was developed as part of an internship program.  
The goal is to **predict students' exam scores** based on study-related factors using machine learning techniques.  

---

📌 Dataset
- Source: [Student Performance Factors Dataset (Kaggle)](https://www.kaggle.com/datasets) 
- The dataset includes features such as:
  - Study hours
  - Sleep duration
  - Participation level
  - Previous scores  
  - Other lifestyle and academic factors

---

 🛠️ Project Workflow
1. Data Cleaning & Preprocessing  
   - Handled missing values  
   - Encoded categorical features  
   - Normalized/standardized numerical data  

2. Exploratory Data Analysis (EDA)  
   - Visualized study hours vs exam scores  
   - Explored correlations between features and scores  

3. Model Training  
   - Linear Regression: Baseline model to predict exam scores  
   - Polynomial Regression (Bonus): Compared with linear regression for performance improvements  
   - Tested different feature combinations (study hours only vs. extended features like sleep, participation, etc.)  

4. Model Evaluation  
   - Metrics: R² score, Mean Absolute Error (MAE), Root Mean Squared Error (RMSE)**  
   - Visualized predictions vs actual scores  

---

 📊 Results
- Linear Regression: Simple and interpretable baseline  
- Polynomial Regression: Improved accuracy but risk of overfitting  
- Feature engineering showed how lifestyle factors impact predictions beyond study hours  

---

🚀 Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn

📂 Repository Structure
Elevvo_internship_tasks/
│
├── Elevvo_task001.ipynb # Main Colab Notebook
└── README.md # Project documentation



📌 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Omotosho-2579/Elevvo_task001.git
Open the notebook in Google Colab or Jupyter Notebook.

Run all cells to reproduce results.

✨ Acknowledgments
Elevvo Tech Cairo, Egypt
Internship program guidelines

Kaggle dataset providers

👨‍💻 Developed by Mohammed Abdulrafiu Omotosho
🔗 Connect with me on LinkedIn: www.linkedin.com/in/abdulrafiu-mohammed-aislt-9ab4051ba 


🛍️ Customer Segmentation with Machine Learning

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Omotosho-2579/Customer-Segmentation/blob/main/Customer_Segmentation.ipynb)

This project applies unsupervised learning techniques to group mall customers into distinct clusters based on their income and spending score. The insights can be used by businesses to improve marketing strategies, customer retention, and targeted offers.

---

📌 Dataset
- Source: [Mall Customer Dataset (Kaggle)](https://www.kaggle.com/datasets)  
- Features include:
  - Customer ID  
  - Gender  
  - Age  
  - Annual Income (k$)  
  - Spending Score (1–100)  

---

🛠️ Project Workflow
1. Data Preprocessing & Scaling**  
   - Handled missing values  
   - Normalized income and spending score  

2. Exploratory Data Analysis (EDA)**  
   - Visualized customer distributions  
   - Plotted scatterplots of income vs spending  

3. Clustering Models  
   - K-Means Clustering**: Optimal number of clusters determined using Elbow Method and Silhouette Score  
   - DBSCAN (Bonus): Explored density-based grouping  

4. Cluster Analysis  
   - Visualized clusters in 2D scatter plots  
   - Calculated average spending per cluster to understand behavior  

---

 📊 Results
- Identified customer groups such as:
  - High Income – High Spending → VIP customers  
  - **Low Income – High Spending → Potential overspenders  
  - High Income – Low Spending → Target for engagement campaigns  
- K-Means performed well, DBSCAN revealed alternative perspectives  

---

 🚀 Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  



