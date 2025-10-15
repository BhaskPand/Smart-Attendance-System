🧠 Smart Attendance System
An AI-powered attendance management application that automatically marks student attendance using facial recognition through a live camera feed. This project is built using Python, Flask, OpenCV, and MediaPipe, offering a seamless, contactless attendance solution.

🚀 Features
Real-time face detection and recognition

Automatic attendance entry with timestamps

Flask-based web interface for monitoring

CSV file export of attendance records

Multiperson detection support

Works with live webcam or CCTV input

🛠️ Tech Stack
Technology	Purpose
Python	Core programming language
Flask	Web framework
OpenCV	Face detection and video processing
MediaPipe	Facial landmark recognition
NumPy	Image array manipulation
HTML, CSS, JS	Frontend interface

⚙️ Installation and Setup
Clone the Repository

bash
git clone https://github.com/BhaskPand/Smart-Attendance-System.git
cd Smart-Attendance-System
Create Virtual Environment

bash
python -m venv venv
source venv/bin/activate    # For macOS/Linux
venv\Scripts\activate       # For Windows
Install Dependencies

bash
pip install -r requirements.txt
Run the Application

bash
python app.py
Access in Browser

text
http://localhost:5000
👁️ How It Works
The camera captures live video feed.

OpenCV detects faces and MediaPipe identifies key landmarks.

Matched faces are logged into a CSV file with attendance timestamp.

Admin can view attendance records from the web dashboard.

🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss proposed modifications.

📜 License
This project is open-source under the MIT License.
