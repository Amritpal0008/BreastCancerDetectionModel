# BreastCancerDetectionModel
🩺 Breast Cancer Detection using Support Vector Machine (SVM)
This project implements a machine learning model using Support Vector Machine (SVM) to classify breast cancer as malignant or benign based on the Wisconsin Breast Cancer Dataset.

🔍 Problem Statement
Breast cancer is one of the most common cancers in women worldwide. Early detection can significantly increase survival rates. This project aims to build a classifier that can accurately predict whether a tumor is benign or malignant using SVM.

📊 Dataset
Source: Built-in dataset from Scikit-learn

Features: 30 numeric features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass.

Target: Diagnosis (M = Malignant, B = Benign)

⚙️ Technologies Used
Python

NumPy

Pandas

Scikit-learn

Matplotlib / Seaborn (for visualization)

🧠 Model
Algorithm: Support Vector Machine (SVM)

Kernel: (e.g., RBF/Linear – specify what you used)

Preprocessing: Feature scaling using StandardScaler

Evaluation Metrics: Accuracy, Confusion Matrix, Precision, Recall, F1 Score



📁 Project Structure
bash
Copy
Edit
├── breast_cancer_svm.ipynb     # Jupyter Notebook with code and results
├── requirements.txt            # List of Python dependencies
├── README.md                   # Project overview
└── dataset/                    # (Optional) Folder for dataset if not using built-in loader
🚀 How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/AMRITPAL0008/BreastCancerDetectionModel.git
cd BreastCancerDetectionModel
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the notebook:

bash
Copy
Edit
jupyter notebook BreastCancerDetectionModel.ipynb
✅ Future Work
Try other algorithms like Random Forest or Logistic Regression

Hyperparameter tuning using GridSearchCV

Deploy using Flask/Streamlit

🧑‍💻 Author
Amrit Pal
B.Tech CE student at NIT Jalandhar
