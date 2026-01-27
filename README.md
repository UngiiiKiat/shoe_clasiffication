# ShoeVision: Automated E-Commerce Category Classifier

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white)

## 🎯 Problem Statement
In the fashion e-commerce industry, manual product tagging is time-consuming and prone to human error. Inaccurate classification (e.g., mislabeling Sneakers as Formal Shoes) leads to poor customer experience and inventory mismanagement.

**ShoeVision** solves this by providing an AI-driven classification model that instantly identifies shoe categories, accelerating the listing process by up to 70%.

## 📊 Dataset Detail
* **Source:** [Kaggle - Shoe Classification Dataset (13k Images)](https://www.kaggle.com/datasets/utkarshsaxenadn/shoes-classification-dataset-13k-images)
* **Target Classes:** 
  1. Sneakers
  2. Boots
  3. Formal Shoes
  4. Casual Shoes
  5. Sports Shoes

## 🛠️ Technical Workflow
### 1. Preprocessing & Augmentation
Implemented an image processing pipeline including resizing, normalization, and **Data Augmentation** (rotation, zoom, horizontal flip) to prevent overfitting and improve model robustness.

### 2. Modeling Strategy
I conducted a comparative analysis between two architectures:
* **Baseline Model:** A custom-built Artificial Neural Network (ANN/CNN) trained from scratch.
* **Improvement Model:** Leveraging **Transfer Learning** (e.g., MobileNet/ResNet) to achieve superior feature extraction and higher accuracy.



### 3. Deployment
The best-performing model is deployed as a web-based **Early Warning & Tagging System** using Streamlit, designed for:
* **Warehouse Operators:** To verify categories during the putaway process.
* **QC Teams:** To ensure correct metadata before product launch.

## 🚀 Results
* Successfully compared performance metrics (Accuracy, Precision, Recall).
* Achieved a robust model capable of real-time inference for high-volume inventory.

## 💻 Installation & Usage
1. Clone the repo: `git clone https://github.com/[YOUR_USERNAME]/shoe-classification.git`
2. Install requirements: `pip install -r requirements.txt`
3. Run App: `streamlit run app.py`
