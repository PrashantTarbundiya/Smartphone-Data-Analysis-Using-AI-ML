📱 Smartphone Data Analysis Using AI/ML
📌 Project Overview
This project focuses on analyzing smartphone data using AI and ML techniques. The dataset, sourced from Kaggle/GitHub, contains various attributes related to smartphones, including brand, model, pricing, ratings, storage, processor, camera specifications, battery details, and more. The primary objective is to clean, preprocess, and visualize the data while applying machine learning models for classification and regression tasks.

📂 Dataset Details
Domain: Smartphones
Attributes:
Categorical: Brand, Model, Color, Processor, Battery Type
Numerical: Original Price, Discounted Price, Ratings, Rating Count, Reviews, Memory, Storage, Display Size, Battery Capacity
Text: Rear Camera, Front Camera
Class Label: Discounted Price
🔧 Project Workflow
Data Preprocessing:

Removed null values from the dataset.
Replaced missing numerical values with the mean.
Replaced missing categorical values with the mode.
Statistical Analysis:

Computed count, sum, range, min, max, mean, median, mode, variance, and standard deviation.
Data Visualization:

Used Matplotlib to generate scatter plots, histograms, and pie charts.
Analyzed relationships between features such as price, ratings, battery capacity, and storage.
Machine Learning Models:

Classification: Used K-Nearest Neighbors (KNN) Classifier to predict battery type.
Regression: Used KNN Regressor to predict display size.
Model Evaluation: Applied accuracy, precision, recall, F1-score, mean absolute error (MAE), mean squared error (MSE), and root mean squared error (RMSE).
📊 Results & Conclusion
Successfully implemented data preprocessing and exploratory data analysis.
KNN Classifier was used to classify battery type, and KNN Regressor predicted display size based on selected features.
Gained insights into handling datasets, dealing with missing values, and interpreting statistical and machine learning results.
🚀 Technologies Used
Python (NumPy, Pandas, Matplotlib, Scikit-learn)
Jupyter Notebook/PyCharm for implementation
📜 Usage Instructions
Clone the repository:
bash
Copy
Edit
git clone https://github.com/your-username/your-repository.git
Install dependencies:
bash
Copy
Edit
pip install numpy pandas matplotlib scikit-learn
Run the script:
bash
Copy
Edit
python script.py
👥 Contributors
Prashant Tarbundiya (23BCE347)
Vatsal Vadgama (23BCE35)
📌 Future Enhancements
Implement additional ML models such as Decision Trees, Random Forest, or Deep Learning models.
Extend the dataset with more attributes for better insights.
Build an interactive web dashboard for visualization.
