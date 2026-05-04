# 🎥 Deepfake Detection System using Deep Learning

## 📌 Overview

This project presents a web-based Deepfake Detection System that analyzes uploaded videos and classifies them as **REAL** or **FAKE** using deep learning techniques.

The system uses a combination of CNN-based feature extraction and sequence modeling to detect manipulation in videos. It also provides a **confidence score**, **visual feedback**, and a **summary of prediction**, making it more interactive and user-friendly.

---

## 🚀 Key Features

* 🎯 Upload video and detect deepfake
* 🧠 Deep learning based classification
* 📊 Confidence score with progress bar
* 📈 Graph-based confidence visualization
* 🎥 Real-time face detection on video
* 📝 Automatic result summary
* 🌐 Clean and responsive UI (Django frontend)

---

## 🧠 Working Principle

1. Video is uploaded through the web interface
2. Frames are extracted from the video
3. Face detection is applied on frames
4. Extracted features are passed to trained model
5. Model predicts whether video is REAL or FAKE
6. Output is displayed with:

   * Result (REAL / FAKE)
   * Confidence score
   * Visual bounding box on faces
   * Summary explanation

---

## 🏗️ Tech Stack

* **Frontend:** HTML, CSS, JavaScript
* **Backend:** Django (Python)
* **Deep Learning:** CNN + LSTM
* **Libraries:** OpenCV, NumPy, PyTorch
* **Face Detection:** face-api.js

---

## 📂 Project Structure

```
project/
│
├── Django Application/
│   ├── templates/
│   ├── static/
│   ├── manage.py
│
├── Model Creation/
│   ├── training scripts
│   ├── preprocessing
│
├── README.md
├── LICENSE
```

---



## 📊 Output Example

* Result: REAL / FAKE
* Confidence Score: e.g. 78.6%
* Face bounding boxes with label
* Summary:

  * REAL → Video appears authentic
  * FAKE → Signs of manipulation detected

---

## 📈 Future Enhancements

* Improve model accuracy
* Real-time webcam detection
* API integration
* Cloud deployment
* Batch video processing

---

## 🎓 Academic Use

This project is developed for educational and demonstration purposes in the domain of Artificial Intelligence and Computer Vision.

---

## ⚠️ Disclaimer

This system provides predictions based on trained models and may not be 100% accurate. It should not be used as the sole evidence for critical decision-making.
This project is based on an open-source implementation of deepfake detection and has been enhanced with improvements in UI, confidence scoring, summary generation, and visualization.

## ⭐ Support

If you found this project useful, consider giving it a star ⭐ on GitHub.
