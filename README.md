# 🧠 Nail Disease Detection using Deep Learning

A **deep learning-based web application** that classifies nail disease images with high accuracy.  
This system assists **dermatologists and individuals** in detecting nail diseases by simply uploading an image.

---

## 📖 Overview

This project classifies nail images into **six categories** using a **Convolutional Neural Network (CNN)** built on the **MobileNetV2** architecture.  
The goal is to help detect and monitor nail diseases efficiently and accurately.

---

## 🔬 Classes Detected
- Acral Lentiginous Melanoma  
- Blue Finger  
- Clubbing  
- Healthy Nail  
- Onychogryphosis  
- Pitting  

---

## 📂 Dataset & Preprocessing

The dataset includes labeled nail images across six disease categories.  
Preprocessing and augmentation were applied for better feature extraction and generalization.

**Data Augmentation Techniques:**
- Rotation  
- Scaling  
- Shearing  
- Zooming  
- Horizontal Flipping  

---

## 🧠 Model Architecture

**Base Model:** MobileNetV2 (Pretrained on ImageNet)  

**Added Layers:**
- Global Average Pooling  
- Fully Connected Layers  
- Softmax Activation (for multiclass classification)

**Loss Function:** Categorical Cross-Entropy  
**Optimizer:** Adam  

---

## 🏋️ Training Details
- **Epochs:** 10  
- **Batch Size:** 32  
- **Validation Accuracy:** 91.6%  
- **Validation Loss:** 0.27  

---

## 🚀 Deployment

**Backend:** Flask  
**Frontend:** HTML/CSS with Bootstrap  
**AI Model:** MobileNetV2 (Pretrained on ImageNet)

---

## 💡 Core Features

### 🔍 Real-Time Disease Detection
- Upload nail images directly via the web interface  
- Model predicts disease class with confidence score  
- Fast and responsive UI for real-time feedback  

---

### 🤖 Diagnail AI Chatbot *(Powered by Chatbase)*
- Personalized AI assistant for nail care queries  
- Offers health tips, reminders, and product suggestions  
- Learns from user interaction for improved advice  

---

### 👩‍⚕️ Expert Consultation
- Schedule appointments with certified dermatologists  
- View available slots and confirm instantly  
- Integrated with user profile for appointment tracking  

---

### 📊 Insights Section
- **Nail Health Progress Graph:** Monitors health improvements  
- **Heatmap Tracker:** Highlights affected areas  
- **Health Timeline:** Chronological report view  
- **Trend Analysis:** Predicts possible risks based on history  

---

### 💬 User Forum
- Safe and supportive community space  
- Share experiences, ask questions, and get answers  
- Moderated for privacy and respectful discussions  

---

### 🧠 Blog Section
- Curated educational posts about nail health and treatment  
- Expert dermatologist insights and self-care routines  
- Updated regularly with verified medical resources  

---

### 👤 Profile Management
- Manage personal and health details  
- View past chatbot conversations and appointments  
- Secure user dashboard with authentication  

---

## 🔒 Data Security & Privacy
- All personal data securely encrypted  
- Health-related data stored with confidentiality  
- Authentication and session handling for safety  

---
## 👩‍💻 Authors
## 🧑‍🔬 Sarah Shaikh

- Aspiring Data Analyst | Blending Data, Strategy & AI to Drive Meaningful Change
- https://www.linkedin.com/in/sarah-shaikh-07a3b3289/

## 👩‍💻 Dharmika Gajera

- Aspiring AI & Software Developer | Passionate about Innovation, Problem Solving & Emerging Technologies
- https://www.linkedin.com/in/dharmika-gajera-47b572323
