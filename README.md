🌟 Waste Classification using CNN + Streamlit

A Deep Learning–based waste classification system that identifies images of waste into 10 categories using a trained Convolutional Neural Network (CNN) and provides a web-based interface using Streamlit.

This project aims to support sustainable waste management by automating waste segregation, making recycling more efficient and accurate.

📌 Project Goals

Build a CNN to classify types of waste

Improve accuracy using data augmentation & deeper model

Deploy the trained model using Streamlit

Provide an easy-to-use UI for real-world testing

Support sustainability through AI-driven waste management

🗂️ Waste Categories

The system classifies images into the following 10 classes:

battery

biological

cardboard

clothes

glass

metal

paper

plastic

shoes

trash

🗓️ Week-Wise Progress
🗓️ Week 1 — Data Exploration & Preprocessing
✅ Tasks Completed

Loaded the local dataset garbage-dataset

Verified folder structure and class names

Counted number of images in each class

Displayed sample images

Resized all images to 64×64 for memory efficiency

Normalized image pixel values

Created train-validation split

Documented all analysis in week1_data_exploration.ipynb

🗓️ Week 2 — Base CNN Model Building & Training
✅ Tasks Completed

Built a simple CNN using TensorFlow/Keras

Trained on 10 image classes

Achieved ~58% validation accuracy

Plotted accuracy & loss graphs

Saved the trained model

Notebook updated: week2_cnn_training.ipynb

🔧 Improvements (Week 2)

Added dropout layer to prevent overfitting

Cleaned the data pipeline

Better visualization of training curves

Improved model structuring and documentation

🗓️ Week 3 — Model Improvement + Deployment
🎯 Improvements Applied

Added data augmentation

Built a deeper CNN with BatchNormalization

Trained for more epochs with callbacks

Saved the best model as waste_classifier_model.h5

Created a full Streamlit web app to classify waste

Designed a clean UI for professional usage

Documented everything in week3_model_improvement.ipynb

🖥️ Streamlit App Features

Upload any waste image (JPG/PNG)

App predicts the waste category

Displays confidence percentage

Runs locally using Streamlit

🧪 How to Run This Project
1️⃣ Clone the Repository
git clone https://github.com/<your-username>/waste-classification.git
cd waste-classification

2️⃣ Create and Activate Virtual Environment (Recommended)
Windows
python -m venv venv
.\venv\Scripts\activate

Mac/Linux
python3 -m venv venv
source venv/bin/activate

3️⃣ Install Required Libraries
pip install -r requirements.txt

4️⃣ Run Streamlit App
streamlit run streamlit_app/app.py


Streamlit will open in your browser at:

http://localhost:8501

📁 Project Folder Structure
waste-classification/
│
├── model/
│   └── waste_classifier_model.h5
│
├── streamlit_app/
│   └── app.py
│
├── notebooks/
│   ├── week1_data_exploration.ipynb
│   ├── week2_cnn_training.ipynb
│   └── week3_model_improvement.ipynb
│
├── requirements.txt
├── README.md
└── .gitignore


⚠️ The dataset folder garbage-dataset/ is NOT uploaded to GitHub because it is too large.

🧰 Tools & Technologies Used

Python 3.10+

TensorFlow / Keras

OpenCV (cv2)

NumPy

Matplotlib

Scikit-learn

Streamlit

Jupyter Notebook

📊 Results

✔ Working CNN waste classifier
✔ Deployed using Streamlit
✔ Improved accuracy using augmentation
✔ Clean, simple UI for final presentation

✍️ Author

Sumitha A
CSE Student — AI/ML Virtual Internship