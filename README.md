# 🎯 Smart Attendance System with Face Recognition (LBPH)

![Python](https://img.shields.io/badge/Python-3.x-blue)
![OpenCV](https://img.shields.io/badge/OpenCV-Face%20Recognition-green)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## 📌 Overview

Smart Attendance System adalah aplikasi absensi otomatis berbasis **face recognition** yang menggunakan algoritma **Local Binary Patterns Histogram (LBPH)**.

Sistem ini memungkinkan pencatatan kehadiran secara **real-time** menggunakan kamera komputer tanpa input manual, sehingga meningkatkan efisiensi dan akurasi data absensi.

---

## 🧠 Background

Proses absensi manual memiliki beberapa kelemahan:

* Rentan manipulasi (titip absen)
* Membutuhkan waktu lebih lama
* Kurang efisien dalam pengolahan data

Dengan memanfaatkan teknologi **Computer Vision**, sistem ini dirancang untuk:

* Mengidentifikasi wajah pengguna
* Mencatat kehadiran secara otomatis
* Menyimpan data secara terstruktur

---

## ✨ Features

* 🎥 Face detection (real-time)
* 🧠 Face recognition menggunakan metode LBPH
* 📸 Capture dataset wajah
* ⚙️ Training model wajah
* ✅ Absensi otomatis
* 💾 Export data ke CSV / Excel
* 🖥️ GUI berbasis Tkinter

---

## 🛠️ Tech Stack

* Python
* OpenCV
* NumPy
* Pandas
* Tkinter (GUI)
* CSV / Excel

---

## 📂 Project Structure

Smart-Absensi/
│
├── dataset/          # Data wajah
├── trainer/          # Model hasil training
├── images/           # Screenshot / dokumentasi
├── main.py           # Program utama
├── requirements.txt  # Dependency
└── README.md

---

## ⚙️ Installation

### 1. Install Python

Download Python di:
https://www.python.org

Saat instalasi, pastikan mencentang:
✔ Add Python to PATH

---

### 2. Clone Repository

git clone https://github.com/imammularif/SMART-ABSENSI-WITH-FACE-RECOGNITION-LBPH-USING-PYTHON.git
cd SMART-ABSENSI-WITH-FACE-RECOGNITION-LBPH-USING-PYTHON

---

### 3. Install Dependencies

pip install -r requirements.txt

Jika file `requirements.txt` belum tersedia:

pip install opencv-python numpy pandas

---

## ▶️ How to Run

python main.py

---

## 🖥️ Application Preview

### 🎨 GUI Interface

<img src="https://github.com/imammularif/TA/blob/main/Source/SS%20DEMO.png" width="600">

---

## 🔄 Workflow System

1. Input data user (Nama, NIM, Kelas)
2. Capture wajah (dataset)
3. Training model menggunakan LBPH
4. Sistem mengenali wajah melalui kamera
5. Data absensi otomatis tersimpan

---

## 📊 Output

Data absensi akan tersimpan dalam format:

* CSV
* Excel

### 📁 Contoh Output

<img src="https://github.com/imammularif/SMART-ABSENSI-WITH-FACE-RECOGNITION-LBPH-USING-PYTHON/blob/main/Source/Screenshot%202026-04-20%20155518.png" width="600">

---

## ⚠️ Requirements

* Kamera aktif
* Pencahayaan cukup
* Wajah terlihat jelas saat proses training

---

## 📈 Future Improvements

* Upgrade tampilan GUI agar lebih modern
* Integrasi database (MySQL / PostgreSQL)
* Pengembangan ke versi web (Flask / Django)
* Dashboard monitoring absensi
* Sistem multi-user

---

## 👨‍💻 Author

**Imammul Arif**
Email: (isi email kamu)
LinkedIn: (isi LinkedIn kamu)

---

## ⭐ Notes

Project ini dibuat sebagai:

* Tugas Akhir
* Portfolio
* Pembelajaran Computer Vision dan Face Recognition

---

## 📢 License

Project ini bersifat open-source dan dapat digunakan untuk tujuan pembelajaran.
