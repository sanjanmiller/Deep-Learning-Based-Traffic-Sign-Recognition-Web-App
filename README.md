# 🚦 Deep Learning-Based Traffic Sign Recognition Web App  

This project is a **Deep Learning-based Traffic Sign Classifier** built with **TensorFlow/Keras** and deployed as a **Streamlit web app**. Users can upload an image of a traffic sign, and the model will predict its category.  

## 📌 Features  
✔️ **Trained CNN model** for accurate traffic sign classification.  
✔️ **Streamlit-based web interface** for easy image upload and prediction.  
✔️ **Supports 43 traffic sign classes** from the German Traffic Sign Dataset.  
✔️ **Pre-trained model (traffic_sign.h5)** included for instant predictions.  


<img src="https://raw.githubusercontent.com/sanjanmiller/Deep-Learning-Based-Traffic-Sign-Recognition-Web-App/refs/heads/main/Traffic%20SS_1.JPG" width="600">

<img src="https://raw.githubusercontent.com/sanjanmiller/Deep-Learning-Based-Traffic-Sign-Recognition-Web-App/refs/heads/main/Traffic%20SS_2.jpg" width="600">

## ⚙️ Installation & Setup  

```bash
# 1️⃣ Clone the Repository
git clone https://github.com/sanjanmiller/Deep-Learning-Based-Traffic-Sign-Recognition-Web-App.git
cd Deep-Learning-Based-Traffic-Sign-Recognition-Web-App

# 2️⃣ Install Dependencies
pip install -r requirements.txt

# 3️⃣ Run the Web App
streamlit run traffic_sign_streamlit.py
