# 🧠 Face Recognition System

A powerful and efficient Face Recognition System using computer vision and deep learning. This project detects and recognizes human faces in real-time from images or webcam streams using Python and OpenCV, with face encodings powered by `face_recognition` (built on top of `dlib`).

---

## 📌 Features

- 🔍 Real-time face detection using Haar cascades or HOG
- 🧬 Face recognition using 128-dimensional face encodings
- 🗂️ Support for multiple known faces (image dataset or live capture)
- ✅ Accuracy optimized using distance thresholding
- 🖼️ Image input or live webcam support
- 📝 Log recognized faces with timestamps (optional)
- 🔐 Useful for attendance systems, security apps, or smart surveillance

---

## 🛠️ Tech Stack

- **Language:** Python
- **Libraries:** `face_recognition`, `OpenCV`, `NumPy`, `os`
- **Model:** dlib’s ResNet face encoder (pre-trained)
- **Optional UI:** Tkinter (for simple GUI)

---

## 🚀 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/face-recognition-system.git
cd face-recognition-system
