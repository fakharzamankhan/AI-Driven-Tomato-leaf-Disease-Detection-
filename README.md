# 🍅 AI Tomato Care – AI-Driven Tomato Leaf Disease Detection System

An AI-powered full-stack web application for early detection of tomato leaf diseases using deep learning and computer vision. The system enables users to upload leaf images and receive accurate disease predictions along with a user-friendly interface and analytics.

---

## 🚀 Features

- 🔍 CNN-based image classification for disease detection  
- 📸 Real-time image upload and prediction  
- 🧪 Image preprocessing & validation using OpenCV  
- 🎯 Confidence-based filtering for reliable predictions  
- 👤 Secure user authentication (OTP verification, password reset)  
- 📊 Dashboard with scan history and analytics  
- 💬 Feedback and contact system  
- 🌐 Responsive web interface  

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
- TensorFlow / Keras  
- OpenCV  
- NumPy  
- scikit-learn  

## ⚙️ System Workflow

1. User uploads a tomato leaf image  
2. Image is validated and preprocessed  
3. CNN model performs classification  
4. Prediction with confidence score is generated  
5. Result is displayed and stored in the database  

## 📂 Project Structure
AI-Tomato-Care/
│
├── backend/ # Flask backend logic (routes, controllers)
├── models/ # ML model files
├── templates/ # HTML templates
├── static/ # CSS, JS, images
├── instance/ # Local database files
│
├── uploads/ # Uploaded images (runtime generated)
├── tmp_nonleaf/ # Temporary files
│
├── app.py # Main Flask application
├── config.py # Configuration settings
├── requirements.txt # Dependencies
├── .gitignore # Ignored files
└── README.md # Documentation


## ⚙️ Installation & Setup

bash
# Clone repository
git clone https://github.com/fakharzamankhan/AI-Tomato-Care.git

# Navigate to project folder
cd AI-Tomato-Care

# Install dependencies
pip install -r requirements.txt

# Run the application
python app.py

🔐 Environment Variables
Create a .env file (not included in repo) and add:
SECRET_KEY=your_secret_key
DATABASE_URL=your_database_url
EMAIL_USER=your_email
EMAIL_PASS=your_password

⚠️ Notes
Runtime folders such as uploads/ and tmp_nonleaf/ are generated during execution
These folders may not be included in the repository
Ensure PostgreSQL is properly configured before running
📊 Future Improvements
📱 Mobile application integration
☁️ Cloud deployment (AWS / Azure)
🌿 Support for more plant diseases
📈 Model accuracy improvement

👨‍💻 Author
Fakhar Zaman
📍 Pakistan
📧 fakharzamandaha@yahoo.com
💼 LinkedIn: www.linkedin.com/in/fakhar-zaman-07b565348
