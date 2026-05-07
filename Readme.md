# Sign Language Detection using LSTM Model

## 📌 Overview
A deep learning-based system that detects and recognizes sign language gestures in real-time using Long Short-Term Memory (LSTM) networks. The model analyzes gesture sequences and predicts corresponding signs, enabling communication support for the hearing and speech impaired.

## 🚀 Features
- Real-time hand gesture recognition
- Dynamic sign sequence prediction using LSTM
- MediaPipe-based landmark extraction
- High accuracy on trained sign vocabulary

## 🛠️ Technologies Used
- Python
- TensorFlow / Keras
- LSTM (Long Short-Term Memory)
- OpenCV
- MediaPipe
- NumPy

## 📂 Project Structure

Sign-Language-Detection/
│
├── sign_language_detection.ipynb   # Main notebook
└── README.md                       # Project documentation

## 🧠 How It Works
1. **Landmark Extraction** – MediaPipe detects hand/body keypoints from video frames
2. **Sequence Collection** – Keypoint sequences are collected for each gesture
3. **LSTM Model** – Trained on gesture sequences to learn temporal patterns
4. **Prediction** – Model predicts the sign in real-time with confidence score

## 📊 Model Architecture
- Input: Sequence of keypoint landmarks
- LSTM Layers for temporal feature learning
- Dense + Softmax output layer for classification

## 🔧 How to Run
1. Open the notebook in Google Colab or Jupyter
2. Install dependencies:
   pip install tensorflow opencv-python mediapipe numpy

3. Run all cells in `sign_language_detection.ipynb`

## 👩‍💻 Author
**Zara Fatima**  
Department of Computer Science  
Aligarh Muslim University
