# 💤 Drowsiness Detection using OpenCV  
Modern real-time eye-tracking system that detects signs of drowsiness using **OpenCV**, **dlib**, and **facial landmark analysis**.

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.9+-blue" />
  <img src="https://img.shields.io/badge/OpenCV-Real--Time-green" />
  <img src="https://img.shields.io/badge/Computer%20Vision-Active-orange" />
  <img src="https://img.shields.io/badge/Status-Stable-brightgreen" />
</p>

A modern, lightweight project built to monitor eye state in live video and alert the user if they are becoming drowsy.

---

## ⭐ Overview  
This project continuously tracks **eye landmarks** and calculates the **Eye Aspect Ratio (EAR)**.  
If your eyes remain closed beyond a threshold, an **alert is triggered**.

This is widely used in:
- Driver fatigue detection  
- Long work-session monitoring  
- Safety-critical environments  

---

## 🚀 Features  
- Real-time face and eye detection  
- EAR-based drowsiness calculation  
- Alarm trigger when drowsiness is detected  
- Fast and efficient OpenCV pipeline  
- Works on any machine with a webcam  

---

## 🧠 Technical Highlights  
- **68-point facial landmark detection** via dlib  
- EAR computed through vertical/horizontal eye distance ratios  
- Continuous frame-based monitoring  
- Threshold-based sleep detection  
- Small, high-performance codebase  

---

## 📂 Project Structure  
```
📦 Drowsiness-Detection-OpenCV
 ┣ 📜 main.py
 ┣ 📜 detector.py
 ┣ 📜 utils.py
 ┣ 📁 models/
 ┣ 📁 assets/
 ┗ 📜 README.md
```

---

## 🛠 Installation  

### 1. Install dependencies  
```bash
pip install opencv-python dlib numpy scipy imutils playsound
```

You may also need **cmake** installed for dlib depending on OS.

### 2. Run the application  
```bash
python main.py
```

Make sure your webcam is active.

---

## 📸 Output Screenshots  
Place your screenshots inside a folder like:

```
📁 output/
   ┣ output1.png
   ┗ output2.png
```

Then reference them:

```markdown
![Detection Screenshot](./output/output1.png)
![Alert Trigger Screenshot](./output/output2.png)
```

---

## 🎯 Use Cases  
- Driver assistance systems  
- Monitoring during long study/work sessions  
- Smart fatigue-aware automation  

---

## 🧩 Tech Stack  
| Component | Technology |
|----------|------------|
| Video Processing | OpenCV |
| Landmark Detection | dlib |
| Math Utils | NumPy, SciPy |
| Audio Alert | playsound |
| App Logic | Python |

---

## 🤝 Contributing  
Pull requests and improvements are welcome.  
Let’s build better fatigue detection systems together.

---

## 📜 License  
MIT License

