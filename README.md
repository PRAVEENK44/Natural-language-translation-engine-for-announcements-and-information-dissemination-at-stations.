# 🚉 Vaani: Real-Time Multilingual Translation Engine for Station Announcements

A **capstone project** under completion by **B.Tech Computer Science & Engineering (AI & ML)** students of **Presidency University, Bengaluru**.  
This system enables **real-time, multilingual voice and text translation of announcements** at Indian railway stations, ensuring inclusivity and accessibility for passengers from diverse linguistic backgrounds.  

---

## 📜 Problem Statement  
**Problem ID:** PSCS_51  
**Organization:** Ministry of Railways  

> *“Railway, bus, and airport stations in India serve passengers from diverse linguistic backgrounds, but announcements are usually restricted to 1–2 major languages like English and Hindi. This limitation creates confusion and inconvenience for non-native speakers, leading to missed trains or flights and an overall poor travel experience. There is a critical need for a real-time, accurate, and scalable multilingual translation system that can deliver announcements in multiple regional languages, ensuring inclusivity, accessibility, and improved passenger satisfaction.”*  

---

## ✨ Key Features  
- **Real-time Translation** – Instantly translates live or pre-recorded announcements.  
- **Multilingual Support** – Supports major Indian languages such as **Kannada, Hindi, Tamil, Telugu, and English**.  
- **Domain-Specific Accuracy** – Fine-tuned for railway/transport terminology like *arrival, departure, platform number*.  
- **Dual Output** – Provides both **text output** (for display screens) and **synthesized voice output** (for PA systems).  
- **Scalable Architecture** – Robust, modular, and user-friendly for deployment in busy station environments.  

---

## 🛠️ Technology Stack  

**Programming Language:** Python 🐍  
**AI/ML Frameworks:** TensorFlow / PyTorch, Hugging Face Transformers  
**Translation Models:** Fine-tuned MarianMT / IndicTrans / mBART  

**Speech & Voice Processing:**  
- STT: Whisper API, Google Speech Recognition  
- TTS: Google TTS / Coqui TTS  

**Backend:** Flask / FastAPI  
**Database:** MySQL / MongoDB  
**Deployment:** Docker, AWS / GCP  

---

## 🏗️ System Architecture  

**Pipeline Overview:**  
1. **Audio Input** → Spoken announcement captured via microphone  
2. **Speech-to-Text (STT)** → Converts audio into English text  
3. **Machine Translation** → Translates English into multiple target languages  
4. **Text-to-Speech (TTS)** → Synthesizes natural-sounding voice announcements  
5. **Output** → Broadcast to PA system & displayed on station screens  

---

## 🚀 Getting Started  

### Prerequisites  
- Python 3.9+  
- Anaconda or `venv`  

### Installation  
```bash
# Clone repository
git clone https://github.com/your-username/Vaani.git
cd Vaani

# Create & activate virtual environment
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

### Usage  
```bash
# Run the application
python app.py
```

Open your browser → [http://127.0.0.1:5000](http://127.0.0.1:5000)  

---

## 👥 Team Members (Presidency University, Bengaluru)  

| Roll Number   | Student Name        |  
|---------------|---------------------|  
| 20221CAI0072 | **PRAVEEN NANDAN K** |  
| 20221CAI0075 | SHAILESH K R        |  
| 20221CAI0083 | SYED AFRIDI         |  

---

## 🧑‍🏫 Project Supervisor  
**Dr. Swati Sharma**  
Professor, School of Computer Science and Engineering  
Presidency University, Bengaluru  

---

✨ *Vaani: Giving every passenger a voice they understand.*  
