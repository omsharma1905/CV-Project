# 😷 Face Mask Detector using OpenCV

A real-time **Face Mask Detection System** built using **Python**, **OpenCV**, and **NumPy**.  
This project uses a webcam to detect human faces and classify whether a person is wearing a **mask** or **not wearing a mask**.

---

# 📌 Project Overview

The system captures live video from the webcam, detects faces using OpenCV's **Haar Cascade Classifier**, and applies a simple brightness-based heuristic to determine mask presence.

This project is lightweight, beginner-friendly, and easy to run on any system with Python installed.

---

# 🚀 Features

✅ Real-time webcam face detection  
✅ Detects Mask / No Mask  
✅ Lightweight and fast execution  
✅ Simple OpenCV implementation  
✅ Beginner-friendly project structure  

---

# 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| OpenCV | Computer Vision & Face Detection |
| NumPy | Array and Image Processing |

---

# 📂 Project Structure

```bash
Face-Mask-Detector/
│
├── mask_detector.py
├── haarcascade_frontalface_default.xml
├── README.md
```

---

# ⚙️ Installation

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/omsharma1905/CV-Project.git
```

## 2️⃣ Navigate to Project Folder

```bash
cd CV-Project
```

## 3️⃣ Install Required Libraries

```bash
pip install opencv-python numpy
```

---

# ▶️ How to Run

Run the following command:

```bash
python mask_detector.py
```

The webcam will open automatically.

---

# 🎮 Controls

| Key | Action |
|-----|--------|
| `q` | Quit Application |
| `ESC` | Close Webcam |

---

# 🧠 Working Principle

1. Webcam captures live video feed  
2. Haar Cascade detects faces in each frame  
3. Region of Interest (ROI) is extracted  
4. Brightness-based heuristic checks mask presence  
5. Label is displayed:
   - ✅ Mask
   - ❌ No Mask

---

# ⚠️ Limitations

- Detection is not highly accurate
- Uses simple brightness heuristic instead of AI
- Sensitive to lighting conditions
- Performance may vary with camera quality

---

# 🔮 Future Improvements

- Implement Deep Learning / CNN model
- Improve accuracy using TensorFlow or PyTorch
- Add sound alert system
- Add dataset training support
- Deploy as web application

---

# 📸 Output

- Green Box → Mask Detected  
- Red Box → No Mask Detected  

---

# 👨‍💻 Author

## OM SHARMA

---

# 📜 License

This project is created for educational and learning purposes.
