# 🎨 AIR PAINT BASE

**AIR_PAINT_BASE** is a computer vision project that enables users to draw in the air using hand gestures.  
The system captures real-time video from a webcam and tracks hand movements to simulate digital painting without touching any physical device.

This project demonstrates how **AI, computer vision, and gesture recognition** can be used to create an interactive virtual drawing system.

---

# 🚀 Features

- ✋ Draw in the air using hand gestures  
- 🎥 Real-time webcam tracking  
- 🎨 Virtual paint interface  
- 🖌 Multiple color options  
- 🧹 Clear canvas functionality  
- ⚡ Lightweight and easy to run  

---

# 🧠 How It Works

1. The webcam captures live video input.
2. Computer vision algorithms detect the user's hand or fingertip.
3. The movement of the fingertip is tracked frame by frame.
4. The tracked motion is converted into drawing strokes on a virtual canvas.

---

# 🏗 Project Structure

```
AIR_PAINT_BASE/
│
├── air_paint.py        # Main application script
├── requirements.txt    # Project dependencies
├── assets/             # Images or UI assets (if used)
└── README.md           # Project documentation
```

---

# 🛠 Tech Stack

This project uses the following technologies:

- **Python**
- **OpenCV**
- **NumPy**
- **Computer Vision**
- **Webcam Video Processing**

---

# ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/RAJ-MANE/AIR_PAINT_BASE.git
cd AIR_PAINT_BASE
```

---

### 2️⃣ Create Virtual Environment (Optional but Recommended)

```bash
python -m venv venv
```

Activate environment

**Windows**

```bash
venv\Scripts\activate
```

**Mac / Linux**

```bash
source venv/bin/activate
```

---

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

If requirements file is not present:

```bash
pip install opencv-python numpy
```

---

# ▶️ Run the Project

```bash
python air_paint.py
```

Your webcam will open and you can start drawing in the air.

---

# 🎮 Controls

| Gesture / Action | Function |
|-----------------|----------|
| Finger movement | Draw on canvas |
| Move hand to color area | Change drawing color |
| Clear area selection | Clear the canvas |

---

# 📊 Future Improvements

- Hand tracking with **MediaPipe**
- More drawing tools (brush size, shapes)
- Save drawings as images
- Gesture-based undo / redo
- GUI interface

---

# 🤝 Contributing

Contributions are welcome!

Steps to contribute:

1. Fork the repository

2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit changes

```bash
git commit -m "Add new feature"
```

4. Push to branch

```bash
git push origin feature-name
```

5. Open a Pull Request

---

# 📜 License

This project is licensed under the **MIT License**.

---

# ⭐ Support

If you like this project:

⭐ Star the repository  
🍴 Fork it  
📢 Share it with others  

---

# 👨‍💻 Author

**Raj Mane**

GitHub:  
https://github.com/RAJ-MANE
