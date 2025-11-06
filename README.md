# 🌸 Flower Classification Web App

This project is a **Convolutional Neural Network (CNN)** based deep learning application that classifies images of flowers into five categories — **Daisy, Dandelion, Rose, Sunflower, and Tulip**.  
It includes both a **Jupyter Notebook** for model training (`Flower_recog_Model.ipynb`) and a **Streamlit web app** (`app.py`) for real-time image classification.

---

## 🚀 Project Overview

The goal of this project is to build and deploy a deep learning model capable of recognizing different types of flowers from images.  
The system uses **TensorFlow/Keras** to train a CNN on a labeled dataset and **Streamlit** to create an easy-to-use web interface for predictions.

---

## 🧠 Model Details

- **Model File:** `Flower_Recog_Model.h5`  
- **Model Type:** Convolutional Neural Network (CNN)  
- **Frameworks Used:** TensorFlow, Keras  
- **Target Classes:**  
  - Daisy  
  - Dandelion  
  - Rose  
  - Sunflower  
  - Tulip  

The notebook (`Flower_recog_Model.ipynb`) handles:
- Dataset loading and preprocessing  
- Model architecture design  
- Training, validation, and performance visualization  
- Model saving for deployment

---

## 💻 Streamlit Web App

The `app.py` file provides a user interface to test the trained model.  
Users can upload an image, and the app will predict which flower it belongs to, along with the confidence score.

### Features
- Simple drag-and-drop image upload  
- Real-time prediction results  
- Displays uploaded image and classification result  
- User-friendly web interface built using **Streamlit**

---

## 📂 Project Structure

📁 Flower_Classification/
│
├── Flower_recog_Model.ipynb # Model training notebook
├── Flower_Recog_Model.h5 # Trained CNN model
├── app.py # Streamlit web app for predictions
├── upload/ # Directory for uploaded images
└── README.md # Project documentation


---

## ⚙️ Installation and Setup

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/flower-classification.git
cd flower-classification
2. Install Dependencies
pip install -r requirements.txt


If you don’t have a requirements.txt, install these manually:

pip install tensorflow keras streamlit numpy pillow

3. Run the Web App
streamlit run app.py

4. Upload an Image

Upload a flower image from your device, and the model will display the predicted flower type and confidence score.

🧾 Example Output

Input:
An image of a sunflower 🌻

Output:

The Image belongs to sunflower with a score of 98.74

🧰 Tech Stack
Component	Technology
Framework	TensorFlow, Keras
Interface	Streamlit
Language	Python
Notebook	Jupyter
Model Type	CNN
📊 Future Improvements

Add more flower categories

Improve accuracy with deeper CNN architectures

Integrate Grad-CAM for visualizing model focus

Deploy the model using cloud platforms like AWS or Hugging Face Spaces
