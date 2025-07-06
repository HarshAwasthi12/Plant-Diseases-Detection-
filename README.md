# 🌿 Plant Disease Detection System

A deep learning-based web application to detect diseases in plant leaves. This project leverages the **Plant Village Dataset** and a **Convolutional Neural Network (CNN)** model trained using **TensorFlow/Keras**. The system provides accurate disease predictions through a clean, user-friendly interface built using **Streamlit**.

---

## 🚀 Features

- 📸 Upload plant leaf images for diagnosis
- 🧠 CNN model trained on 50,000+ images from PlantVillage
- 📊 Prediction with confidence percentage
- 🌐 Web-based UI using Streamlit
- 💾 Saves and loads model (`.keras` or `.h5`)
- 📁 Accepts JPG, PNG formats
- 🧪 Test on real leaf images instantly

---

## 📂 Dataset

We used the **Plant Village Dataset** for training, which includes thousands of images across multiple crop types and diseases.

- 🧬 38 classes (healthy + diseased plant leaves)
- 🖼️ 50,000+ labeled images

📥 **Download Link:**  
[Kaggle - Plant Village Dataset](https://www.kaggle.com/datasets/emmarex/plantdisease)

> After downloading, extract it into a folder named `plant_dataset/` and use it in your training script.

---

## 🧠 Model Info

- Architecture: **Convolutional Neural Network (CNN)**
- Framework: **TensorFlow/Keras**
- Layers: Conv2D, MaxPooling, Flatten, Dense, Dropout
- Accuracy: ~98% on validation data
- File: `trained_model.keras`

You can retrain the model using `train_model.py` (if available) or modify it as per your dataset.

---

## 🛠️ Tech Stack

| Layer        | Tools/Frameworks            |
|--------------|-----------------------------|
| Frontend     | Streamlit                   |
| Backend      | Python                      |
| ML Framework | TensorFlow / Keras          |
| Data Handling| Pandas, NumPy               |
| Visualization| Matplotlib, Seaborn         |
| Image Proc.  | OpenCV                      |
| Deployment   | (Optional) Streamlit Cloud / Hugging Face / Render |



├── test_plant_disease.jpg # Sample leaf image
├── AppleCedarRust.jpeg # Another test image
├── .gitignore # Ignored files and folders
├── README.md # Project documentation

