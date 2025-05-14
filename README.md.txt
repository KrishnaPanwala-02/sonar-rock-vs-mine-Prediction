#  Sonar Rock vs Mine Prediction using Machine Learning

A robust machine learning project that classifies sonar signals as **Rock** or **Mine** using advanced preprocessing techniques and a high-performance model based on **Gradient Boosting**. This project showcases data cleaning, dimensionality reduction with **PCA**, and a custom prediction system.

---
##  Dataset

- **Source**: UCI Machine Learning Repository
- **Format**: CSV (60 features, 1 label column)
- **Target**: 
- `R` → Rock 
- `M` → Mine

---
##  Project Highlights

-  Gradient Boosting Classifier (GBM) for high accuracy
-  PCA (Principal Component Analysis) for dimensionality reduction
-  Z-Score based Outlier Removal
-  Label Encoding and Feature Scaling
-  Model Accuracy up to **92%**
- Predictive system that takes real input and classifies it

---
##  Libraries Used

- `pandas`, `numpy`
- `scikit-learn` (PCA, LabelEncoder, GradientBoostingClassifier)
- `matplotlib`, `seaborn`

---
## How to Run the Project

###  1. Clone the Repository
```bash
git clone https://github.com/your-username/sonar-rock-vs-mine.git
cd sonar-rock-vs-mine
2. Install Required Libraries
pip install numpy pandas matplotlib seaborn scikit-learn
3. Run the Python File
python sonar_prediction.py

# Sample Output

Training Accuracy: ~100%
Test Accuracy: ~88%

 #Confusion Matrix
Predicted Rock Predicted Mine
Actual Rock 
Actual Mine 

#Project Structure

📦 sonar-rock-vs-mine
├── sonar_prediction.py
├── Copy of sonar data.csv
├── README.md

🙌 Acknowledgements

UCI Machine Learning Repository
scikit-learn documentation
Kaggle for insights and inspiration

📬 Contact

Made with ❤️ by Krishna Panwala
 Email:krishnapanwala1627@gmail.com
 GitHub: KrishnaPanwala-02