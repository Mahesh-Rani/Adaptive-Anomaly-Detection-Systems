# Adaptive-Anomaly-Detection-Systems
**Adaptive Anomaly Detection Systems Using Federated Learning for Real-Time Cybersecurity in Distributed Networks**

Dataset: https://www.kaggle.com/datasets/chethuhn/network-intrusion-dataset


This repository contains the implementation of an anomaly detection system for cybersecurity using federated learning techniques. The aim is to develop adaptive systems capable of detecting anomalies in real-time across distributed networks.

**Overview**
The notebook Implementation.ipynb walks through the steps of preprocessing, feature scaling, and model training using machine learning algorithms to detect network intrusions. Key steps include:

- Data preprocessing: Cleaning and preparing data by handling missing values, infinite values, and categorical variables.
- Feature scaling: Applying Min-Max scaling to normalize feature values for better model performance.
- Model training: Training Decision Tree and Naive Bayes classifiers to predict intrusions.
- Evaluation: Comparing model accuracy, generating classification reports, and visualizing results.

**Dataset**
The dataset used for this study can be downloaded from the Kaggle Network Intrusion Dataset. It includes labeled network traffic data collected from various working hours to simulate real-world scenarios.

**Files in the Dataset**
The dataset consists of the following files:

- Friday-WorkingHours-Afternoon-DDos.pcap_ISCX.csv
- Friday-WorkingHours-Afternoon-PortScan.pcap_ISCX.csv
- Friday-WorkingHours-Morning.pcap_ISCX.csv
- Monday-WorkingHours.pcap_ISCX.csv
- Thursday-WorkingHours-Afternoon-Infilteration.pcap_ISCX.csv
- Thursday-WorkingHours-Morning-WebAttacks.pcap_ISCX.csv
- Tuesday-WorkingHours.pcap_ISCX.csv
- Wednesday-workingHours.pcap_ISCX.csv


Key Features
- Data Preprocessing: Includes handling null and infinite values, renaming columns for consistency, and identifying unique categorical features.
- Feature Engineering: Scales numerical features using Min-Max Scaling for uniformity.
- Model Training: Trains Decision Tree and Gaussian Naive Bayes models to classify network anomalies.
- Visualization: Bar plot comparison of model accuracies for better interpretability.


**Dependencies**
The following Python libraries are used in the notebook:

- pandas for data manipulation
- numpy for numerical operations
- matplotlib and seaborn for data visualization
- sklearn for preprocessing, model training, and evaluation


**Usage**
1. Clone this repository:
bash
Copy code
git clone https://github.com/yourusername/adaptive-anomaly-detection.git

2. Download the dataset from Kaggle and place the CSV files in the appropriate directory.
3. Open the Implementation.ipynb notebook in Jupyter or Google Colab.
4. Run the notebook cells sequentially to preprocess data, train models, and evaluate results.


**Results**
The trained models achieved the following accuracy:

- Decision Tree Classifier: ~88% accuracy
- Naive Bayes Classifier: ~85% accuracy

The notebook provides detailed classification reports and visualizations to compare model performances.

**Future Work**
Future iterations may explore:

- Advanced machine learning models like Random Forest, Gradient Boosting, or Neural Networks.
- Implementation of federated learning for distributed anomaly detection.
- Real-time anomaly detection using streaming data.
