# Authentix-ai_project

# 🔐 Authentix – The Trust Layer

🚀 An AI-powered system to detect deepfakes, AI-generated media, fake news, and suspicious human behavior.

Authentix is not just a detection tool — it is a **multi-modal trust verification system** combining **computer vision, behavioral analysis, and NLP**.

---

## 📌 Features

### 🧠 1. Deepfake & AI Image Detection
- Detects face swaps and manipulated media
- Identifies GAN & diffusion-generated images
- Uses deep learning (EfficientNet / CNN models)

### 👁️ 2. Gaze Detection (Behavior Analysis)
- Tracks eye movement and head pose
- Detects unnatural gaze patterns
- Flags suspicious behavior (useful in exams/interviews)
- Outputs a **Gaze Manipulation Score**

### 📰 3. Fake News Detection
- NLP-based classification (Real / Fake / Suspicious)
- Uses TF-IDF / BERT embeddings

### ✅ 4. Fact Verification System
- Cross-checks claims using APIs + LLM reasoning
- Provides explainable results

### 🌐 5. Chrome Extension
- Real-time detection on websites
- Works on images, text, and video frames

### 📊 6. Explainable AI Output
- Confidence score
- Face-level analysis
- Final classification:
  - REAL
  - FAKE
  - SUSPICIOUS

---

## 🏗️ System Architecture

### 📷 Media Pipeline
Image Input → Face Detection (MTCNN) → Deepfake Model → AI Detection Model → Decision Engine

### 👁️ Gaze Pipeline
Webcam Frames → Face + Iris Tracking → Eye Data Extraction → Behavior Analysis → Gaze Score

### 📰 Text Pipeline
Text Input → Preprocessing → Feature Extraction → Fake News Model → Fact Verification → Output

---

## ⚙️ Tech Stack

### 🧑‍💻 Backend
- Python
- FastAPI

### 🤖 AI / ML
- PyTorch
- OpenCV
- Albumentations
- Facenet-PyTorch (MTCNN)
- Transformers (BERT)

### 🌐 Frontend
- MERN Stack

### 🧩 Extension
- Chrome Extension API

### ☁️ Tools
- Google Colab (training)
- Kaggle (datasets)

---

## 📂 Datasets Used

- FaceForensics++ (Deepfake detection)
- CIFAKE Dataset
- 140K Real vs Fake Faces Dataset

---

## 🚀 How It Works

1. User uploads image / enters text / runs extension  
2. System processes input using multiple AI models  
3. Behavior + media + text are analyzed  
4. Outputs:
   - Classification (Real/Fake/Suspicious)
   - Confidence Score
   - Explanation  

---

## 📸 Applications

- Social Media Verification  
- Cybersecurity & Fraud Detection  
- Digital Forensics  
- Journalism & Fact Checking  
- Online Exams & Interviews (Proctoring)  
- Browser-based Real-time Verification  

---

## 🔮 Future Scope

- Real-time deepfake detection in video calls  
- Voice clone detection  
- Mobile app deployment  
- Multi-source fact verification  
- Full behavioral analytics system  

---

## 👩‍💻 Authors

**Aanchal Jagga**  
B.Tech CSE (DSAI)  

---

## ⭐ Why Authentix?

> “In a world full of synthetic truth, Authentix brings real trust.”

Authentix goes beyond detection — it builds a **complete trust layer for the internet**.
