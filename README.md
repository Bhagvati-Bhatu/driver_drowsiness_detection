# 🚗 Driver Drowsiness Detection System

A computer vision–based system that detects driver drowsiness in real time using facial landmarks and eye aspect ratio (EAR). The goal is to reduce road accidents by alerting drivers when signs of fatigue are detected.

---

## 📌 Features

* Real-time face and eye detection
* Eye Aspect Ratio (EAR)–based drowsiness detection
* Alarm/alert when drowsiness threshold is exceeded
* Works with webcam or video input
* Lightweight and efficient

---

## 🧠 How It Works

1. **Face Detection** – Detects the driver’s face using Haar Cascades or Dlib
2. **Eye Landmark Extraction** – Identifies eye landmarks
3. **EAR Calculation** – Computes Eye Aspect Ratio
4. **Drowsiness Detection** – If EAR falls below a threshold for a set time, drowsiness is detected
5. **Alert System** – Triggers an alarm to warn the driver

---

## 🛠️ Tech Stack

* **Programming Language:** Python
* **Libraries Used:**

  * OpenCV
  * Dlib
  * NumPy
  * imutils
  * SciPy

---

## 📂 Project Structure

```
📁 Driver-Drowsiness-Detection
│
├── driver_drowsiness_detection.ipynb
├── README.md
├── requirements.txt
└── assets/
```

---

## ⚙️ Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/driver-drowsiness-detection.git
   ```

2. Navigate to the project directory:

   ```bash
   cd driver-drowsiness-detection
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

---

## ▶️ Usage

* Open the Jupyter Notebook:

  ```bash
  jupyter notebook driver_drowsiness_detection.ipynb
  ```
* Run all cells
* Ensure your webcam is connected
* The system will start detecting drowsiness in real time

---

## 📊 Results

* Accurately detects prolonged eye closure
* Works effectively under normal lighting conditions
* Provides timely alerts to prevent accidents

---

## 🚀 Future Improvements

* Head pose estimation
* Yawn detection
* Deep learning–based fatigue classification
* Mobile or embedded system deployment

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork the repository, create a new branch, and submit a pull request.

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 👤 Author

**Bhagvati Kanabhai Bhatu**
**Tanvi Gandhotra**
---
