# Pancreatic_cancer_detection

# 🧠 Pancreatic Cancer Detection using Deep Learning

An AI-powered web application for early detection of pancreatic cancer using medical imaging. Built with Flask and powered by a pretrained VGG16 model, this system utilizes Grad-CAM for interpretability and provides real-time analysis with healthcare recommendations.

Dataset Source: [Mendeley Data – Pancreas CT Scans](https://data.mendeley.com/datasets/wm8j6j2mph/1)

---

## 🚀 Features

- ✅ **Deep Learning-Based Detection** using pretrained **VGG16**
- ✅ **Visual Explainability** with **Grad-CAM heatmaps**
- ✅ **Secure User Authentication** (Signup & Login)
- ✅ **Real-Time Image Processing** & Prediction
- ✅ **Precautionary Healthcare Measures** based on results

---

## 🧰 Tech Stack

**Backend:** Flask  
**Frontend:** HTML, CSS, JavaScript  
**Machine Learning:** TensorFlow, Keras (VGG16)  
**Explainability:** Grad-CAM  
**Database:** SQLite (for managing user accounts)

---

## 🖼️ How It Works

1. **Sign Up / Log In** to securely access the system.
2. **Upload** a medical image (CT or MRI scan).
3. The system **classifies** the image as **cancerous** or **non-cancerous**.
4. A **Grad-CAM heatmap** highlights critical regions in the scan.
5. The system provides **precautionary recommendations** based on the prediction.

---

## 📦 Installation

```bash
git clone https://github.com/your-username/pancreatic_cancer_detection.git
cd pancreatic_cancer_detection
pip install -r requirements.txt
python app.py
