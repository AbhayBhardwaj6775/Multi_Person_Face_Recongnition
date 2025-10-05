🧠 Multi-Person Face Recognition
📌 Overview

The Multi-Person Face Recognition (MPFR) project is a real-time system capable of identifying multiple individuals simultaneously using a live camera feed or pre-recorded video. It leverages OpenCV, Dlib, and Flask to build an accurate and efficient recognition pipeline.

⚙️ Features

✅ Real-time face detection and recognition
✅ Supports multiple people in a single frame
✅ Dataset management for custom training
✅ Flask-based web interface for easy access
✅ Logging and error handling for performance tracking

🧩 Tech Stack

Language: Python

Libraries: OpenCV, Dlib, NumPy, Flask

Backend: Flask (REST API)

Environment: Virtualenv

Version Control: Git & GitHub

🗂️ Project Structure
Multi_Person_Face_Recognition/
│
├── data/                  # Encoded face data
├── dataset/               # Training images for each person
├── logs/                  # Log files for error and activity tracking
├── src/                   # Main source code files
├── venv/                  # Virtual environment
├── requirements.txt       # Required dependencies
├── req.txt                # Alternative dependency list
├── .gitignore             # Git ignore rules
└── README.md              # Project documentation

🚀 How to Run the Project

1️⃣ Clone the repository

git clone https://github.com/AbhayBhardwaj6775/Multi_Person_Face_Recognition.git
cd Multi_Person_Face_Recognition


2️⃣ Create and activate virtual environment

python -m venv venv
venv\Scripts\activate     # for Windows
source venv/bin/activate  # for Linux/Mac


3️⃣ Install dependencies

pip install -r requirements.txt


4️⃣ Run the Flask application

python src/app.py


5️⃣ Open browser and visit:

http://127.0.0.1:5000/

📊 Working

Capture frames from webcam or video.

Detect faces using HOG + CNN-based models in Dlib.

Encode detected faces into 128-D embeddings.

Compare embeddings with the stored dataset to recognize individuals.

Display real-time recognition results in the browser.

🔐 Future Enhancements

Add face mask detection

Integrate cloud-based dataset storage

Implement attendance or access control system

Optimize model for faster inference
