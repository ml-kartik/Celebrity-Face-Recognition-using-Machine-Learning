# 🌟 Celebrity Face Recognition using Machine Learning

A complete **Machine Learning Web Application** that identifies celebrity faces from uploaded images using **Computer Vision**, **Wavelet Transform**, and **Classification Algorithms**.
Built with **Python**, **Flask**, **OpenCV**, **Scikit-learn**, **HTML**, **CSS**, and **JavaScript**.

---

## 📌 Features

✅ Upload any celebrity image
✅ Detect face and eyes automatically
✅ Extract important facial features
✅ Predict celebrity name with confidence scores
✅ Interactive and responsive web interface
✅ Fast local deployment using Flask

---

## 🧠 Machine Learning Workflow

1. Collect dataset images
2. Detect faces using Haar Cascade
3. Crop facial region
4. Apply Wavelet Transform for feature extraction
5. Train ML model (SVM / Logistic Regression / Random Forest)
6. Save trained model using Pickle
7. Deploy using Flask API
8. Connect frontend UI with backend

---

## 🛠️ Tech Stack

### Backend

* Python 3.x
* Flask
* Flask-CORS

### Machine Learning

* Scikit-learn
* NumPy
* Pandas
* Joblib / Pickle

### Computer Vision

* OpenCV
* PyWavelets

### Frontend

* HTML5
* CSS3
* JavaScript
* jQuery
* Bootstrap
* Dropzone.js

---

# 📂 Project Structure

```bash
CelebrityFaceRecognition/
│── server/
│   ├── server.py
│   ├── util.py
│   └── artifacts/
│       ├── saved_model.pkl
│       └── class_dictionary.json
│
│── ui/
│   ├── app.html
│   ├── app.js
│   ├── app.css
│   └── images/
│
│── model/
│   ├── training.ipynb
│   └── dataset/
│
└── README.md
```

---

# ⚙️ Installation Guide

## 1️⃣ Clone Repository

```bash
git clone https://github.com/yourusername/celebrity-face-recognition.git
cd celebrity-face-recognition
```

---

## 2️⃣ Create Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Mac/Linux

```bash
source venv/bin/activate
```

---

## 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

If requirements.txt is missing:

```bash
pip install flask flask-cors numpy pandas scikit-learn opencv-python pywavelets matplotlib joblib
```

---

# 📦 Required Python Modules

```python
Flask
Flask-CORS
NumPy
Pandas
OpenCV
Scikit-learn
PyWavelets
Matplotlib
Pickle
Joblib
OS
JSON
Shutil
```

---

# 🚀 Run the Project

## Start Backend Server

```bash
cd server
python server.py
```

Runs on:

```bash
http://127.0.0.1:5000
```

---

## Start Frontend

Open new terminal:

```bash
cd ui
python -m http.server 8000
```

Open browser:

```bash
http://127.0.0.1:8000/app.html
```

---

# 🖼️ How It Works

1. Upload image
2. Click **Classify**
3. Model predicts celebrity name
4. Confidence scores displayed

---

# 🧪 Sample Predictions

| Image         | Prediction    |
| ------------- | ------------- |
| Messi Photo   | Lionel Messi  |
| Kohli Photo   | Virat Kohli   |
| Federer Photo | Roger Federer |

---

# 📈 Algorithms Used

* Support Vector Machine (SVM)
* Logistic Regression
* Random Forest Classifier
* GridSearchCV for Hyperparameter Tuning

---

# 🔍 Image Processing Techniques

* Haar Cascade Face Detection
* Eye Detection
* Image Cropping
* Wavelet Feature Extraction
* Feature Scaling

---

# 🧯 Common Errors & Fixes

## CORS Error

Install Flask-CORS:

```bash
pip install flask-cors
```

---

## File Not Found Error

Ensure:

```bash
server/artifacts/
```

contains:

* saved_model.pkl
* class_dictionary.json

---

## 405 Error

Check API route method is:

```python
POST
```

---

# 📌 Future Improvements

✨ Add more celebrities
✨ Deploy on Render / Heroku / AWS
✨ Improve UI Design
✨ Use Deep Learning (CNN)
✨ Real-time Webcam Prediction

---

# 🤝 Contributing

Contributions are welcome!
Fork this repository and submit a pull request.

---

# 📜 License

This project is open-source and available under the MIT License.

---

# 👨‍💻 Author

Developed with ❤️ by **Kartik Jadhav**

---

# ⭐ Support

If you like this project:

🌟 Star the repository
🍴 Fork it
📢 Share it

---
