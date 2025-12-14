# [BanglaTaka 🇧🇩💴](https://colab.research.google.com/github/hossainsiam133/BanglaTaka/blob/main/Code/BanglaTaka_Siam.ipynb)

<p style="text-align: justify;">BanglaTaka is a deep learning–based image classification project designed to recognize Bangladeshi banknotes across multiple denominations.  
The project focuses on building a robust pipeline using **image augmentation** and **Convolutional Neural Networks (CNNs)** to handle real-world variations in banknote images.</p>

---

**Authors:**  
- Md. Talha Mahmud (23100069)  
- Md. Siam Hossain (23100084)  
- Asif Manowar (23100016)  

**Department:** CSE, R.P. Shaha University, Narayanganj  
**Batch:** 26  
**Course Code:** 0613-CSE-4316  
**Course Title:** Machine Learning Lab  
**Course Instructor:** Md Safaet Ullah, Lecturer, CSE  
**Semester:** Fall - 2025

---

## 📌 Supported Denominations
- 2 taka
- 5 taka
- 10 taka
- 20 taka
- 50 taka
- 100 taka
- 200 taka
- 500 taka
- 1000 taka

---

## 🎯 Project Objectives
- Classify Bangladeshi banknotes by denomination
- Handle limited datasets using data augmentation
- Improve robustness against rotation, lighting, and scale variations
- Build a scalable CNN-based classification pipeline

---

## [🗂 Dataset Structure](https://drive.google.com/drive/folders/13P5Soos4thSeu9Su62lHVENzrSF3kxCA?brid=_lZkcYae4gXRQ2ufJUg74w)

drive/MyDrive/dataset  <br>
│── 2/ <br>
│── 5/  <br>
│── 10/  <br>
│── 20/  <br>
│── 50/  <br>
│── 100/  <br>
│── 200/  <br>
│── 500/  <br>
│── 1000/  <br>

Each denomination initially contains a limited number of images, which are expanded using augmentation techniques.

---

## 🔄 Data Augmentation

Image augmentation is performed using **TensorFlow's `ImageDataGenerator`**, applying:

- Rotation
- Width and height shifting
- Zoom
- Brightness adjustment
- Shear transformation

This increases dataset size and improves model generalization.

---

## 🧠 Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/<hossainsiam133>/BanglaTaka.git
```
---

## 📈 Future Work

Train and evaluate CNN models for all denominations

Add real vs fake banknote classification

Improve performance with transfer learning

Deploy the model as a web or mobile application

---

## 👨‍🎓 Academic Context

This project was developed as part of a Machine Learning Lab course and
demonstrates practical implementation of image preprocessing and deep learning–based classification.
---

## 📜 License

This project is intended for academic and research purposes.
