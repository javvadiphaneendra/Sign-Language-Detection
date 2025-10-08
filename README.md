Realtime Sign Language Detection Using LSTM Model

The Realtime Sign Language Detection Using LSTM Model is an AI-powered system developed by Phaneendra Javvadi that recognizes and interprets sign language gestures in real time. Using a Long Short-Term Memory (LSTM) neural network, it processes video input from a camera and accurately classifies gestures.

The project aims to help individuals with hearing or speech impairments communicate more effectively by bridging the communication gap through deep learning and computer vision. It combines Python, TensorFlow, OpenCV, and Mediapipe to deliver fast, accurate, and reliable results.

📑 Table of Contents

About the Project

Demo

Features

Getting Started

Usage

Contributing

License

Contact

🧠 About the Project

This project focuses on building a real-time gesture recognition system using deep learning.
The LSTM model learns from sequences of key points (captured via Mediapipe) to classify hand signs accurately.
It supports custom training, enabling users to expand the gesture dataset for new signs or languages.

This system contributes toward making AI-driven assistive technologies more accessible to the deaf and hard-of-hearing community.

The demo shows how the system captures real-time gestures and classifies them instantly using an LSTM neural network.

⚙️ Features

🖐️ Real-Time Detection: Recognizes sign gestures instantly from camera input.

🤖 Deep Learning with LSTM: Uses temporal sequence learning for high-accuracy recognition.

🌍 Multi-Language Support: Can be trained for sign gestures from various sign languages.

🧩 Customizable Dataset: Users can add new gestures and retrain easily.

🧠 Mediapipe Integration: Efficient hand landmark tracking with minimal computation.

💬 Assistive Communication: Designed to enhance accessibility for hearing-impaired individuals.

🖥️ User-Friendly Interface: Simple and interactive Jupyter-based UI.

🔓 Open Source: Contributions and community improvements are welcome!

🚀 Getting Started

Follow these steps to set up the project on your system 👇

🧩 Prerequisites

Make sure you have the following installed:

Python

TensorFlow

OpenCV

NumPy

Mediapipe

⚙️ Installation

1️⃣ Clone the repository:

git clone https://github.com/PhaneendraJavvadi/Realtime-Sign-Language-Detection-Using-LSTM-Model.git
cd Realtime-Sign-Language-Detection-Using-LSTM-Model


2️⃣ Install required dependencies:

pip install -r requirements.txt


(If you don’t have a requirements file, you can manually install:)

pip install tensorflow opencv-python mediapipe numpy notebook


3️⃣ Run the notebook:

jupyter notebook


Then open and run all the cells in RealTimeSignLanguageDetection.ipynb.

🧪 Usage

Launch the notebook.

Run all cells to start the detection model.

Show your hand gestures in front of the webcam.

The system will detect and display the recognized sign in real time.

🤝 Contributing

Contributions are welcome!
If you’d like to improve performance, add new gestures, or fix bugs:

Fork the repository

Create a new branch (feature-name)

Commit your changes

Submit a pull request

📜 License

This project is licensed under the MIT License — you are free to use, modify, and distribute it with proper attribution.

📬 Contact

👤 Phaneendra Javvadi
📧 Email: javvadiphani71805@gmail.com

🌐 GitHub: PhaneendraJavvadi
