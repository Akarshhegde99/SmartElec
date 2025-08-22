# 🗳️ Face Recognition Voting System

A Python-based real-time face recognition voting system using OpenCV and KNN, designed for secure and automated digital elections. Voters are identified via webcam, authenticated using face data, and allowed to vote only once.

[🎥Watch the demo video](https://drive.google.com/file/d/1wem4cKyc_Bi9xwHK6Oq15UGAXCmAezp2/view?usp=sharing)

## 🔍 Features

- 🧠 Facial recognition with **OpenCV + KNN**
- 📦 Persistent voter data with **pickle**
- 📄 Records votes in **CSV format**
- 🎤 Audio feedback using **Text-to-Speech (SAPI)**
- 🖼️ GUI overlay with a custom background frame
- 🛑 Prevents double voting
- 🔘 Key-based party voting (`1`, `2`, `3`, `4`)

## 🛠️ Requirements

- Python 3.x
- OpenCV
- NumPy
- scikit-learn
- pywin32 (for TTS on Windows)

Install dependencies:
pip install opencv-python numpy scikit-learn pywin32


🚀 How to Run
Command in Terminal: python add_faces.py
Ensure your webcam is connected.

Stand in front of the camera for face recognition.
After registering the face, run the give_vote file
Command in Terminal: python give_vote.py

Press:

1 for United Congress Party

2 for United Republican Front

3 for United Left Front

4 for New Independent Party


🔒 Voting Rules
One vote per registered face.

Duplicate voting is automatically blocked.

All voting timestamps are saved in Votes.csv.


✨ Inspired by real-world voting systems & biometric authentication.

