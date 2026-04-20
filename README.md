# Facial Emotion Recognition using Fuzzy Logic  
A fuzzy-logic–based facial emotion recognition system using computer vision and geometric facial features.

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![OpenCV](https://img.shields.io/badge/OpenCV-ComputerVision-green.svg)
![dlib](https://img.shields.io/badge/dlib-FaceLandmark-orange.svg)
![FuzzyLogic](https://img.shields.io/badge/Fuzzy-Logic-yellow.svg)
![Status](https://img.shields.io/badge/Status-Active-success.svg)

---

## 📌 Project Overview
This project implements a **Facial Emotion Recognition System** based on:

- Fuzzy Logic  
- Computer Vision  
- Geometric Facial Landmark Features  

The model extracts 68 facial landmarks using **dlib** and computes:

- Smile Intensity (SI)  
- Mouth Opening (MO)  
- Eye Opening (EO)  
- Eyebrow Height  
- Eyebrow Distance  

These features feed into a fuzzy inference system to estimate emotional states.

---

## 🎯 Project Title
**Design and Implementation of a Fuzzy-Logic–Based Facial Emotion Recognition System**

---

## 👨‍🏫 Instructor  
Dr. Shahrzad Sedaghat

## 👨‍💻 Author  
**Alireza Mehraban**

---

## 📄 Abstract
This project proposes a fuzzy‑logic–based system for classifying human emotions from facial images.  
Using geometric cues extracted from 68 facial landmarks, fuzzy membership values are calculated for various emotional expressions.  
A rule base inspired by psychological studies is then used to infer emotional states.

The system was evaluated on **1000 images** from a Kaggle dataset and demonstrated acceptable classification accuracy while maintaining interpretability — an advantage over deep learning–based methods.

---

## 🧠 Why Fuzzy Logic for Emotion Recognition?
- 🌫 Handles ambiguity and uncertainty in emotional expressions  
- 🔍 Highly interpretable decision-making  
- 📉 Works with fewer labeled samples  
- 🔄 Smooth transitions between emotional states  

---

## 🛠 Technologies Used
- Python 3.8+
- OpenCV
- dlib (68-point facial landmark detection)
- NumPy / SciPy
- Fuzzy Logic System
- Kaggle dataset (1000 images)

---

## 🚀 Features
✔ 68-point facial landmark detection  
✔ Extraction of geometric features  
✔ Fuzzy membership calculation  
✔ Fuzzy rule-based emotional inference  
✔ Interpretable outputs  
✔ Works with small datasets  


---

## 📊 Example Output (Pseudo)
```text
Smile Intensity: 0.73
Eye Opening: 0.41
Mouth Opening: 0.62

Fuzzy Output:
  Happiness: 0.82
  Surprise: 0.37
  Neutral: 0.11

Final Emotion: Happiness
```

---

## 📦 Installation
git clone https://github.com/mehrKind/Facial-Emotion-Recognition.git
cd Facial-Emotion-Recognition
pip install -r requirements.txt

---

## ▶️ Run the Project
```
python src/inference.py --image path/to/image.jpg
```

---

## ❤️ Credits
Made By Love Alireza Mehraban

---

## 📬 Contact
Email: mr.kind1382@gmail.com
