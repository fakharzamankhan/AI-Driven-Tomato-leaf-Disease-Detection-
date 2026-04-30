# AI-Driven-Tomato-leaf-Disease-Detection-
AI-powered full-stack web application for tomato leaf disease detection using CNN, Flask, and OpenCV with real-time prediction and user dashboard.


---

## 🚀 Features

- 🔍 **CNN-based image classification** for disease detection  
- 📸 **Real-time image upload and prediction**  
- 🧪 **Image preprocessing & validation** using OpenCV  
- 🎯 **Confidence-based filtering** for reliable results  
- 👤 **User authentication system** (OTP verification & password reset)  
- 📊 **Dashboard with scan history and analytics**  
- 💬 **Feedback and contact system**  
- 🌐 **Responsive web interface**  

---

## 🧠 AI Model

- **Model Type:** Convolutional Neural Network (CNN)  
- **Framework:** TensorFlow / Keras  
- **Classes:**
  - Early Blight  
  - Late Blight  
  - Leaf Mold  
  - Healthy  

---

## 🛠 Tech Stack

**Frontend:**  
- HTML, CSS, Bootstrap, JavaScript  

**Backend:**  
- Flask (Python)  

**Database:**  
- PostgreSQL (SQLAlchemy ORM)  

**Libraries:**  
- OpenCV  
- NumPy  
- TensorFlow / Keras  

---

## ⚙️ System Architecture

1. User uploads leaf image  
2. Image is validated and preprocessed  
3. CNN model performs classification  
4. Prediction with confidence score is generated  
5. Results are displayed and stored in database  

---

## 📂 Project Structure
AI-Tomato-Care/
│
├── backend/               # Core Flask backend logic (routes, controllers)
│
├── models/                # Machine learning models and related files
│   ├── trained_model.h5
│
├── templates/             # HTML templates (frontend views)
│
├── static/                # Static files (CSS, JavaScript, images)
│
├── instance/              # Local database and instance-specific files
│
├── uploads/               # Uploaded images (runtime generated)
├── tmp_nonleaf/           # Temporary files for non-leaf detection
│
├── app.py                 # Main Flask application entry point
├── config.py              # Application configuration settings
│
├── requirements.txt       # Python dependencies
├── .gitignore             # Git ignored files
│
└── README.md              # Project documentation
