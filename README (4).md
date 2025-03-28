# Cybersecurity Threat Classification using Machine Learning

## Introduction
With the increasing frequency of cyber threats, the need for automated and intelligent threat detection systems is more crucial than ever. This project aims to develop a machine learning model to classify network traffic into different categories using the **NSL-KDD dataset**.

## Features
- **Data Preprocessing:**
  - Encoding categorical features (`protocol_type`, `service`, `flag`)
  - Splitting dataset into training (80%) and testing (20%)
  
- **Feature Scaling:**
  - Standardizing numerical features for better model performance
  
- **Model Selection & Training:**
  - **Random Forest Classifier** (Ensemble learning with multiple decision trees)
  - **Support Vector Machine (SVM)** (Kernel-based optimization for classification)
  
- **Evaluation Metrics:**
  - Accuracy, Precision, Recall, F1-Score, Confusion Matrix
  - Feature Importance analysis using the Random Forest model

## Results
- **Random Forest Model:** Achieved ~99.8% accuracy, performing well in classification tasks.
- **SVM Model:** Achieved ~99.4% accuracy, showing strong predictive capabilities.
- **Feature Importance:** Key features such as `dst_bytes`, `srv_count`, and `serror_rate` were highly influential in classification.

## Future Improvements
- Address class imbalance using **SMOTE** or advanced resampling techniques.
- Implement **deep learning models** to enhance detection.
- Perform additional **feature engineering** to improve classification accuracy.

## Installation and Usage
### Prerequisites
- Python 3.x
- Required Python libraries (install using `pip install -r requirements.txt`):
  ```sh
  pandas
  numpy
  scikit-learn
  seaborn
  matplotlib
  ```

### Running the Project
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/cybersecurity-ml.git
   ```
2. Navigate to the project directory:
   ```sh
   cd cybersecurity-ml
   ```
3. Run the Python script:
   ```sh
   python main.py
   ```
