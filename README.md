# 🌱 Crop Disease Classification Web App

A deep learning-based web application that detects crop diseases from leaf images using a trained CNN model (VGG16-based).
Built with **Flask**, **TensorFlow**, and deployed on **Render**.

---

## 🚀 Live Demo

👉 https://disease-classification-t6o3.onrender.com

---

## 📌 DEEP LEARNING MODEL :- https://drive.google.com/file/d/1pfJ0FnBK4jcWIeHYs1u0JxpIRGGbzUCq/view?usp=share_link

## 📌 Features

* 📷 Upload crop leaf images
* 🧠 Deep learning model for disease prediction
* ⚡ Real-time prediction results
* 🌐 Fully deployed web application
* ☁️ Model auto-download from Google Drive
* 🧪 Handles invalid inputs and errors

---

## 🛠️ Tech Stack

* **Frontend:** HTML, CSS
* **Backend:** Flask (Python)
* **Machine Learning:** TensorFlow / Keras
* **Deployment:** Render
* **Model:** VGG16-based CNN

---

## 📁 Project Structure

```
Disease-Classification/
│
├── app.py
├── requirements.txt
├── runtime.txt
├── Procfile
├── templates/
│   └── index.html
├── static/
│   ├── styles.css
│   └── uploads/
```

---

## ⚙️ Installation (Local Setup)

### 1. Clone the repository

```bash
git clone https://github.com/rajsirohi23/Disease-Classification.git
cd Disease-Classification
```

### 2. Create virtual environment

```bash
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the app

```bash
python app.py
```

---

## 🌐 Deployment (Render)

1. Push code to GitHub
2. Go to Render → New Web Service
3. Connect your repo
4. Add:

   * Build Command: `pip install -r requirements.txt`
   * Start Command: `gunicorn app:app`

---

## 📦 Model Handling

* Model file (`.h5`) is **not stored in GitHub**
* It is downloaded dynamically from Google Drive using `gdown`

---

## ⚠️ Challenges Faced

* TensorFlow compatibility issues
* Memory limits on Render free tier
* Model loading errors
* Deployment debugging

---

## 💡 Future Improvements

* 🎨 Improved UI/UX
* ⚡ Faster inference using TensorFlow Lite
* 📊 Show disease details & treatment
* 📱 Mobile responsiveness
* 🔍 Better image validation

---

## 👨‍💻 Author

**Raj Sirohi**
📧 Aspiring AI & Data Engineer
🔗 GitHub: https://github.com/rajsirohi23

---

## ⭐ If you like this project

Give it a ⭐ on GitHub and share it!

---
