# 👁️‍🗨️ Face Recognition Suite (Colab Projects)

This project contains two interactive and educational computer vision mini-projects built in Google Colab:

---

## 📸 1. Face Detection

A lightweight pipeline using [InsightFace](https://github.com/deepinsight/insightface) to:

- Upload or capture images (supports HEIC, JPG, PNG)
- Detect and align faces from images
- Crop and display detected faces
- Count the number of detected faces

👉 **Use case:** image preprocessing or surveillance detection setups.

---

## 🧠 2. Face Match & Access Control

A more advanced face recognition system that:

- Embeds two face images and compares similarity using cosine distance
- Optionally crops & compares left and right eyes
- Adds real-time webcam support in Google Colab
- Detects if the input face matches a known user and prints “Door Open” mock access logs

### ✅ Features:
- Uses InsightFace’s `buffalo_l` model
- Fast face embedding comparison
- Easily extendable with more faces
- Modular, clear code (ideal for real-world adaptation)

---

## 💡 How to Run

1. Open the notebook in [Google Colab](https://colab.research.google.com/)
2. Run the first setup cell to install dependencies
3. Upload your images or use your webcam
4. Follow the guided steps to detect, align, and compare faces

---

## 📦 Dependencies

- `insightface`
- `opencv-python`
- `matplotlib`
- `scikit-learn`
- `Pillow`
- `google.colab` APIs (for webcam)

---


## 🔐 Future Plans

- Extend to face clustering & database management
- Use YOLOv8 for multi-face real-time detection
- Integrate with ComfyUI or DeepSort for face tracking

---

## ✨ Author

**Amir Tabatabaei** – [LinkedIn](https://www.linkedin.com/in/amirtabatabaei10/)  
Junior Python Developer & ML Engineer | Specializing in Computer Vision

