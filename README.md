# AI-HandGestureDetector & AirCanvas
Designed and developed an AI-powered hand gesture recognition system capable of identifying multiple hand postures in real time.

------------------------------------------
AI-Hand-Gesture-and-Air-Canvas/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── hand_gesture_recognition/
│   ├── app.py
│   ├── collect_data.py
│   ├── train_model.py
│   ├── predict.py
│   ├── hand_detector.py
│   │
│   ├── dataset/
│   │   └── hand_landmarks.csv
│   │
│   └── models/
│       └── hand_posture_model.pkl
│
└── air_canvas/
    ├── air_canvas.py
    └── README.md

------------------------------------------------
🤖 AI Hand Gesture Recognition & Air Canvas
------------------------------------------------

A computer vision project that uses Python, OpenCV and MediaPipe to detect hand gestures and create an interactive virtual drawing canvas using hand movements.

🚀 Projects Included

1. AI Hand Gesture Recognition

The system detects hand landmarks using MediaPipe and uses machine learning to recognize different hand postures.

Features

- ✋ Real-time hand detection
- 📍 Hand landmark extraction
- 🤖 Machine learning based gesture recognition
- 📊 Dataset collection
- 🧠 Model training
- 🎯 Real-time prediction
- 📈 High classification accuracy

The trained model achieved approximately 98.51% accuracy on the test data.

------------------------------------
2. Air Canvas
------------------------------------
Air Canvas allows users to draw in the air using their hand.

The camera tracks the user's hand and converts hand movement into drawing actions on a virtual canvas.

Features

- ✋ Real-time hand tracking
- 🖌️ Air drawing
- 🧹 Eraser mode
- 🎨 Multiple colors
- 👆 Gesture-based drawing control
- 🤏 Thumb-index gesture for stopping/starting drawing
- 🖥️ Real-time OpenCV interface

🛠️ Technologies Used

- Python
- OpenCV
- MediaPipe
- NumPy
- Machine Learning
- Computer Vision
- Pickle

📂 Project Structure

AI-Hand-Gesture-and-Air-Canvas/
│
├── hand_gesture_recognition/
│   ├── app.py
│   ├── collect_data.py
│   ├── train_model.py
│   ├── predict.py
│   ├── hand_detector.py
│   ├── dataset/
│   │   └── hand_landmarks.csv
│   └── models/
│       └── hand_posture_model.pkl
│
├── air_canvas/
│   └── air_canvas.py
│
├── requirements.txt
├── .gitignore
└── README.md

⚙️ Installation

Clone the repository:

git clone https://github.com/YOUR_USERNAME/AI-Hand-Gesture-and-Air-Canvas.git

Go into the project folder:

cd AI-Hand-Gesture-and-Air-Canvas

Create a virtual environment:

python -m venv .venv

Activate it on Windows:

.venv\Scripts\activate

Install dependencies:

pip install -r requirements.txt

▶️ Running Hand Gesture Recognition

Go to the gesture recognition folder:

cd hand_gesture_recognition

To collect hand landmark data:

python collect_data.py

To train the model:

python train_model.py

To run prediction:

python predict.py

🎨 Running Air Canvas

Go to the Air Canvas folder:

cd air_canvas

Run:

python air_canvas.py

Make sure your webcam is connected and accessible.

📸 How It Works

The basic workflow is:

Webcam
   ↓
Hand Detection
   ↓
Hand Landmarks
   ↓
Feature Extraction
   ↓
Machine Learning Model
   ↓
Gesture Prediction

For Air Canvas:

Webcam
   ↓
Hand Tracking
   ↓
Finger Position Detection
   ↓
Gesture Recognition
   ↓
Virtual Drawing

🎯 Applications

- Human-computer interaction
- Touchless interfaces
- Gesture-controlled applications
- Virtual drawing
- Educational applications
- Computer vision projects
- AI/ML portfolio projects

🔮 Future Improvements

- Add more hand gestures
- Improve gesture stability
- Add gesture-controlled games
- Add image manipulation using hand gestures
- Add gesture-controlled presentations
- Add voice commands
- Improve UI
- Deploy as a desktop application

👨‍💻 Author

Himansu Dhal

B.Tech Computer Science & Engineering

------------------------
3. requirements.txt
------------------------
opencv-python
mediapipe
numpy
scikit-learn
