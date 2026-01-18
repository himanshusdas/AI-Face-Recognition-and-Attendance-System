# AI Face Recognition & Attendance System

An **AI-powered Face Recognition and Attendance System** that automatically detects, recognizes faces, and marks attendance in real time. This project demonstrates the practical use of **computer vision**, **machine learning**, and **backend integration** for building a smart attendance solution suitable for classrooms, offices, and institutions.

---

## 🚀 Features

* 🎯 **Face Detection & Recognition** using deep learning / OpenCV
* 🧠 **Automatic Attendance Marking** with date & time
* 📸 **Real-time Camera Support** (webcam / CCTV)
* 🗂 **Student/User Face Dataset Management**
* 📊 **Attendance Records Storage** (CSV / Database)
* 🔐 **Accurate & Contactless System**
* 🖥 **Beginner-friendly & Modular Codebase**

---

## 🛠 Tech Stack

### Core Technologies

* **Python 3.x**
* **OpenCV** – face detection & image processing
* **face_recognition / Dlib** – facial feature encoding
* **NumPy & Pandas** – data handling

### Optional / Extended

* **Django / Flask** – backend & UI (if enabled)
* **SQLite / MySQL** – database storage
* **HTML, CSS, JavaScript** – frontend UI

---

## 📂 Project Structure

```
AI-Face-Recognition-Attendance/
│
├── dataset/                 # Training images (person-wise folders)
├── encodings/               # Stored face encodings
├── attendance/              # Attendance CSV / DB files
├── models/                  # Trained models (if any)
│
├── train_faces.py            # Train face encodings
├── recognize_attendance.py  # Face recognition & attendance marking
├── camera.py                 # Webcam handling
├── utils.py                  # Helper functions
├── requirements.txt          # Python dependencies
└── README.md                 # Project documentation
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/ai-face-recognition-attendance.git
cd ai-face-recognition-attendance
```

### 2️⃣ Create Virtual Environment (Recommended)

```bash
python -m venv venv
source venv/bin/activate   # Linux / Mac
venv\Scripts\activate      # Windows
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

> ⚠️ **Note:** `dlib` may require CMake and Visual Studio Build Tools on Windows.

---

## 📸 Dataset Preparation

1. Create a folder inside `dataset/` with the **person's name**.
2. Add **10–20 clear face images** per person.

Example:

```
dataset/
├── Himanshu/
│   ├── img1.jpg
│   ├── img2.jpg
├── Sahil/
│   ├── img1.jpg
```

---

## 🧠 Train the Model

Run the training script to generate face encodings:

```bash
python train_faces.py
```

This will extract facial features and store them for recognition.

---

## 🎥 Run Face Recognition & Attendance

```bash
python recognize_attendance.py
```

* Opens webcam
* Detects and recognizes faces
* Marks attendance automatically

Attendance is saved with **Name, Date, and Time**.

---

## 📊 Attendance Output

* Stored in `attendance/attendance.csv`
* Format:

```
Name, Date, Time
Himanshu, 2026-01-18, 10:32:45
```

---

## 📈 Use Cases

* 🏫 College / School Attendance
* 🏢 Office Employee Tracking
* 🧪 Research & Learning Projects
* 🤖 AI & Computer Vision Practice

---

## ⚠️ Limitations

* Performance depends on **lighting conditions**
* Accuracy decreases with **low-quality cameras**
* Not recommended for high-security applications

---

## 🔮 Future Enhancements

* Web-based dashboard (Django)
* Admin login & role management
* Cloud database integration
* Masked face detection
* Mobile app support

---

## 🤝 Contributors

* **Himanshu Shekhar Das**
* Sahil Kumar Singh
* Hrishikesh Deka

**Institution:** Assam down town University

---

## 📜 License

This project is licensed under the **MIT License**.

---

## ⭐ Acknowledgements

* OpenCV Community
* face_recognition library
* Python Open Source Ecosystem

---

If you find this project useful, **please ⭐ star the repository** and contribute! 😊
