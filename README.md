# Natural language translation engine for announcements and information dissemination at stations

![Python](https://img.shields.io/badge/python-3.9+-blue.svg)
![Framework](https://img.shields.io/badge/Framework-Flask/FastAPI-orange)
![License](https://img.shields.io/badge/License-MIT-green.svg)

A capstone project under completion by B.Tech Computer Science & Engineering (AI & ML) students of Presidency University, Bengaluru. This system provides real-time, multilingual voice and text translation of announcements for Indian railway stations.

## 📜 Problem Statement
**Problem ID:** PSCS_51
**Organization:** Ministry of Railways

> [cite_start]"Railway, bus, and airport stations in India serve passengers from diverse linguistic backgrounds, but announcements are usually restricted to 1–2 major languages like English and Hindi. This limitation creates confusion and inconvenience for non-native speakers, leading to missed trains or flights and an overall poor travel experience. There is a critical need for a real-time, accurate, and scalable multilingual translation system that can deliver announcements in multiple regional languages, ensuring inclusivity, accessibility, and improved passenger satisfaction." [cite: 393, 394, 395]

## ✨ Key Features
- **Real-time Translation:** Instantly translate live or pre-recorded announcements.
- [cite_start]**Multilingual Support:** Supports major Indian languages including Kannada, Hindi, Tamil, and Telugu, alongside English. [cite: 407]
- [cite_start]**Domain-Specific Accuracy:** Fine-tuned to accurately translate transport-specific terms like "arrival," "departure," and "platform number." [cite: 408]
- [cite_start]**Dual Output:** Provides both translated text on screens and synthesized voice announcements. [cite: 409]
- [cite_start]**Scalable Architecture:** Designed to be robust and user-friendly for real-world deployment in busy station environments. [cite: 410]

## 🛠️ Technology Stack
- [cite_start]**Programming Language:** Python [cite: 427]
- [cite_start]**AI/ML Frameworks:** TensorFlow / PyTorch, Hugging Face Transformers [cite: 428]
- [cite_start]**Translation Models:** Fine-tuned MarianMT / IndicTrans / mBART [cite: 429]
- **Speech & Voice:**
    - **Speech-to-Text (STT):** Whisper API, Google Speech Recognition
    - [cite_start]**Text-to-Speech (TTS):** Google TTS / Coqui TTS [cite: 430]
- [cite_start]**Backend:** Flask / FastAPI [cite: 432]
- [cite_start]**Database:** MySQL / MongoDB [cite: 431]
- [cite_start]**Deployment:** Docker, AWS / GCP [cite: 432]

## 🏗️ System Architecture



The system follows a simple pipeline:
1.  **Audio Input:** Captures spoken announcements via a microphone.
2.  **Speech-to-Text:** Converts the audio into English text.
3.  **Machine Translation:** Translates the English text into multiple target languages.
4.  **Text-to-Speech:** Synthesizes voice announcements from the translated text.
5.  **Output:** Delivers audio to the PA system and text to display screens.

## 🚀 Getting Started

### Prerequisites
- Python 3.9+
- Anaconda or a Python virtual environment manager (`venv`)

### Installation
1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/your-username/RailVani.git](https://github.com/your-username/RailVani.git)
    cd RailVani
    ```
2.  **Create and activate a virtual environment:**
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```
3.  **Install the required dependencies:**
    ```sh
    pip install -r requirements.txt
    ```

### Usage
1.  **Run the application:**
    ```sh
    python app.py
    ```
2.  Open your web browser and navigate to `http://127.0.0.1:5000`.

## 👥 Team Members (Students from Presidency University)

| Roll Number   | Student Name       |
|---------------|--------------------|
| 20221CAI0075  | SHAILESH K R       |
| 20221CAI0072  | PRAVEEN NANDAN K   |
| 20221CAI0083  | SYED AFRIDI        |

## 🧑‍🏫 Project Supervisor
- Dr.Swati Sharma, Professor, School of Computer Science and Engineering, Presidency University. 

