# Vehicle Image Classification with MobileNetV2 using Streamlit  
### (Klasifikasi Gambar Kendaraan dengan MobileNetV2 menggunakan Streamlit)

## 🌍 Overview | Gambaran Umum
This project classifies vehicle images into **10 categories** using **transfer learning with MobileNetV2**, and provides an interactive interface through Streamlit.

Proyek ini mengklasifikasikan gambar kendaraan ke dalam **10 kategori** menggunakan **transfer learning MobileNetV2**, serta menyediakan antarmuka interaktif melalui Streamlit.

---

## 🧠 Model Architecture | Arsitektur Model
- Base model: **MobileNetV2 pretrained on ImageNet**
- Frozen base layers (all except last 20)
- Custom classification head with:
  - GlobalAveragePooling2D  
  - Dropout 0.5  
  - Dense softmax output (10 classes)
- Optimizer: **Adam (1e-4)**
- Loss: **categorical crossentropy**

---

## 📊 Dataset Details | Detail Dataset
- Source | Sumber: Kaggle  
  https://www.kaggle.com/datasets/marquis03/vehicle-classification
- 10 vehicle classes | 10 kelas kendaraan:
  - Bus, SUV, Family Sedan, Fire Engine, Heavy Truck,
    Jeep, Truck, Taxi, Racing Car, Minibus
- Training images: **1,400**
- Validation images: **200**
- Preprocessing & augmentation applied

---

## ✅ Model Performance | Performa Model
| Metric | Value |
|--------|-------|
| **Highest Training Accuracy** | **98.66%** |
| **Highest Validation Accuracy** | **92.00%** |

**EN:** The model generalizes well across 10 classes, demonstrating effective feature transfer and stable validation performance.  
**ID:** Model menunjukkan generalisasi yang baik pada 10 kelas, dengan transfer fitur yang efektif dan performa validasi stabil.

---

## 🖥 Demo Preview | Tampilan Demo
Access the deployed Streamlit app here:
Akses aplikasi Streamlit di sini:
👉 https://kelompok7pengolahancitra.streamlit.app/
<img width="1919" height="954" alt="Screenshot 2025-11-23 180512" src="https://github.com/user-attachments/assets/e4d6f58e-ef52-409b-80c8-476f5e53e233" />
<img width="1919" height="942" alt="Screenshot 2025-11-23 180607" src="https://github.com/user-attachments/assets/dd434109-37fd-4ae3-b0ff-00b800bf8944" />

---

(Optional additional images):
- top-3 predictions
- confidence bar chart
- confusion matrix (recommended)

---

## ▶️ How to Run | Cara Menjalankan
pip install -r requirements.txt
streamlit run app.py

---

## 🧰 Tech Stack | Teknologi
- Python  
- TensorFlow / Keras  
- MobileNetV2  
- Streamlit  
- NumPy / Pandas  

---

## 📌 What This Demonstrates | Nilai Proyek Ini
**EN**
- Understanding of transfer learning
- Ability to work end-to-end (data → model → evaluation → UI)
- Deployment-oriented thinking
- Relevant foundation for a Data Scientist internship

**ID**
- Pemahaman transfer learning
- Mampu bekerja end-to-end (data → model → evaluasi → UI)
- Pemikiran siap-deploy
- Fondasi relevan untuk magang Data Scientist

---

## 🔗 Project Context | Konteks
This project was developed as part of academic and personal learning in Machine Learning, Computer Vision, and Python development.

Proyek ini dikembangkan sebagai bagian dari pembelajaran akademik dan personal dalam Machine Learning, Computer Vision, dan pengembangan Python.



