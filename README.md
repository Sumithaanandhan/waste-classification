# Waste Classification using CNN

## 🌱 Project Overview
This project applies **Deep Learning (Convolutional Neural Networks - CNNs)** to classify waste images into different categories such as plastic, paper, glass, metal, and more.  
The aim is to support **sustainable waste management** by automating waste segregation using AI.

---

## 🗓️ Week 1 - Data Exploration & Preprocessing

### ✅ Tasks Completed
- Collected local dataset named **`garbage-dataset`** containing 10 categories:
  - `battery`, `biological`, `cardboard`, `clothes`, `glass`, `metal`, `paper`, `plastic`, `shoes`, `trash`
- Verified dataset folder structure and class names
- Counted total images per category
- Displayed sample images for each class
- Checked image dimensions and consistency
- Created a preprocessing function (resize + normalize)
- Created train-validation split for CNN training (to be done in Week 2)
- Documented all steps in a Jupyter Notebook

---

## 📂 Folder Structure
waste-classification/
│
├── garbage-dataset/ # Local dataset (NOT uploaded to GitHub)
│ ├── battery/
│ ├── biological/
│ ├── cardboard/
│ ├── clothes/
│ ├── glass/
│ ├── metal/
│ ├── paper/
│ ├── plastic/
│ ├── shoes/
│ └── trash/
│
├── week1_data_exploration.ipynb # Jupyter Notebook (Week 1 work)
└── README.md # Project documentation


> ⚠️ **Note:** The `garbage-dataset` folder should be kept locally — it should not be uploaded to GitHub (as it’s too large).

---

## 💻 How to Run This Project

### 1️⃣ Install Required Libraries
Use the following commands in your terminal or command prompt:
```bash
pip install numpy matplotlib opencv-python scikit-learn tensorflow keras
2️⃣ Run Jupyter Notebook
bash
Copy code
jupyter notebook
Then open and execute the file week1_data_exploration.ipynb.

🧰 Tools & Libraries Used
Python 3.10+

Jupyter Notebook

OpenCV (cv2)

NumPy

Matplotlib

Scikit-learn

TensorFlow / Keras (for CNN model)


✍️ Author
Sumitha A
Computer Science and Engineering Student