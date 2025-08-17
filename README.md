# 🛍️ Virtual Trial Room (Raspberry Pi + Python + MediaPipe)

A **Virtual Trial Room** built using **Raspberry Pi, OpenCV, MediaPipe, and CVZone** that allows users to try on shirts virtually in real-time using a webcam.  
This project uses **pose estimation** to detect body landmarks and overlays a shirt image onto the user.

---

## 🚀 Features
- 👕 Virtual shirt try-on in real-time  
- 🎥 Live video capture with OpenCV  
- 🧍 Pose estimation using MediaPipe  
- 🔄 Auto-resizing of shirts based on body proportions  
- 🐍 Built in Python for Raspberry Pi (can also run on any computer with a webcam)  

---

## 🛠️ Tech Stack
- **Raspberry Pi** (or any system with Python and webcam)
- **Python 3.x**
- [OpenCV](https://opencv.org/) – Image processing
- [MediaPipe](https://developers.google.com/mediapipe) – Pose detection
- [CVZone](https://github.com/cvzone/cvzone) – For overlaying transparent PNG shirts
- **OS module** – File handling

---

## 📂 Project Structure
```
VirtualTrialRoom/
│── main.py               # Main code (your provided script)
│── Resources/
│   └── Shirts/           # Shirt images (.png with transparency)
│── README.md             # Project documentation
│── requirements.txt      # Dependencies
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/stackqueen/VirtualTrialRoom.git
cd VirtualTrialRoom
```

### 2️⃣ Create a virtual environment (optional but recommended)
```bash
python3 -m venv venv
source venv/bin/activate    # On Windows: venv\Scripts\activate
```

### 3️⃣ Install dependencies
Create a `requirements.txt` file with:
```
opencv-python
mediapipe
cvzone
```
Then run:
```bash
pip install -r requirements.txt
```

### 4️⃣ Add shirt images
- Place PNG shirt images (with transparent background) inside:
```
Resources/Shirts/
```

---

## ▶️ Run the Project
```bash
python main.py
```

- The camera window will open.  
- A shirt will be overlaid on your body.  
- Press **`q`** to quit.

---

## 📸 Demo
(Add screenshots or GIFs here showing virtual try-on.)

---

## 🌟 Future Enhancements
- Support for multiple shirt selection  
- UI for choosing different clothes  
- Better landmark tracking & fitting  
- Integration with e-commerce websites  

---

## 📜 License
This project is licensed under the **MIT License** – feel free to use and modify it.

---

## 👨‍💻 Author
Developed by **stackqueen** ✨  
If you like this project, ⭐ star the repo and share!
