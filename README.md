# 🚀 DDoS Attack Detection

This project implements a machine learning-based system to detect and classify Distributed Denial of Service (DDoS) attacks using supervised learning algorithms. It is built upon the **NSL-KDD** dataset, which is widely used for network intrusion detection research.

---

## 🌟 Features

- **🔧Data Preprocessing**: Handles missing values, normalizes the data, and splits it into training and testing sets.
- **📊Feature Engineering**: Selects relevant features for improving model performance.
- **🤖Supervised Learning Algorithms**:
  - Random Forest Classifier
  - Logistic Regression
  - K-Nearest Neighbors (KNN)
- **📋Performance Metrics**:
  - Accuracy
  - Precision
  - Recall
  - F1-score
- **📉 Visualization**: Visual representations of dataset distributions and performance metrics.

---

## ⚙️Installation and Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/MohdUmarSiddiq/DDoS-Attack-Detection.git
   cd DDoS-Attack-Detection
   ```
2. ⚙**Install Dependencies**:
Install the required libraries listed in requirements.txt:
  ```bash
  pip install -r requirements.txt
  ```
3. ## 📄 Dataset

The project uses the **NSL-KDD** dataset, a benchmark dataset for intrusion detection research. You can download it from the following link:

- [Download NSL-KDD Dataset]((https://www.kaggle.com/datasets/hassan06/nslkdd)) 📥

After downloading, place the dataset files in the `data/` directory.


## 🖥️ Usage
Run the Jupyter Notebook to execute the project:
```bash
jupyter notebook DDOS_Attack_Detection.ipynb
```
Steps covered in the notebook:

1.Load and preprocess the data.

2.Train and evaluate the machine learning models.

3.Visualize the results.

## 🏆 Results
The project achieved significant performance across multiple attack categories:

🌲 Random Forest: Achieved the highest accuracy of XX%.

🏡 K-Nearest Neighbors (KNN): Balanced precision and recall for specific attack types.

📈 Logistic Regression: Effective in binary classification scenarios.

Detailed performance metrics are included in the notebook.

## 📊 Visualization Examples
🔢 Confusion matrix for model evaluation.

⭐ Feature importance for Random Forest.

🧮 ROC and AUC curves.

## 🚀 Future Improvements
🔗 Implementing ensemble learning techniques for better generalization.

🤖 Experimenting with deep learning models like LSTMs or CNNs for improved detection accuracy.

## 🤝 Contributing
Feel free to fork this repository, raise issues, or submit pull requests to enhance the project.


