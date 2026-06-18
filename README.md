# 🛡️ DeepShield: AI-Powered Voice Deepfake Detection System

![Python](https://img.shields.io/badge/Python-3.10-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![Flask](https://img.shields.io/badge/Flask-Web%20Framework-black)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Active-success)

DeepShield is an AI-powered voice deepfake detection system that identifies whether an uploaded audio sample is **Real** or **Deepfake** using deep learning techniques. The application extracts acoustic features from voice recordings and leverages neural network models to detect synthetic speech artifacts that are difficult for humans to recognize.

As voice cloning and AI-generated speech technologies continue to advance, DeepShield helps mitigate risks associated with voice phishing (vishing), identity theft, impersonation attacks, misinformation, and social engineering.

---

## 📌 Problem Statement

Modern generative AI models can create highly realistic synthetic voices that closely mimic human speech. These voice deepfakes pose serious security and privacy threats across industries.

Common risks include:

* Voice phishing (vishing) attacks
* Financial fraud and identity theft
* Unauthorized voice impersonation
* Fake media and misinformation
* Social engineering attacks
* Bypassing voice-based authentication systems

DeepShield addresses these challenges by automatically identifying anomalies and hidden patterns present in AI-generated speech.

---

## ✨ Features

* 🎙️ Upload audio files for authenticity analysis
* 🧠 Deep learning-based voice classification
* 📊 Confidence score prediction
* 🔍 Automatic audio feature extraction
* 📁 Detection history and result logging
* 🌐 User-friendly web interface
* 🔐 Secure file handling and processing
* ⚡ Fast prediction and inference

---
## 🎥 Demo Video

Watch the project demo here:

```text[
Youtube Demo LINK: https://youtu.be/DlS9fFVnLtw
```

---

## 🏗️ System Architecture

```text
Audio Input
     │
     ▼
Audio Preprocessing
     │
     ▼
Feature Extraction
(MFCC, Chroma, Spectral Features, ZCR)
     │
     ▼
Deep Learning Model
(CNN + BiLSTM)
     │
     ▼
Prediction Engine
     │
     ▼
Real / Deepfake Classification
```

> Replace **CNN + BiLSTM** with your actual model architecture if different.

---

## 🔄 Application Workflow

1. User uploads an audio file.
2. The system preprocesses the audio.
3. Acoustic features are extracted.
4. The deep learning model performs inference.
5. Prediction confidence is generated.
6. Results are displayed and logged.

---

## 🧪 Methodology

### Audio Preprocessing

* Noise reduction
* Resampling
* Silence trimming
* Audio normalization

### Feature Extraction

The system extracts various acoustic features using Python audio processing libraries:

* Mel-Frequency Cepstral Coefficients (MFCCs)
* Chroma Features
* Spectral Centroid
* Spectral Bandwidth
* Spectral Contrast
* Zero Crossing Rate (ZCR)
* Root Mean Square (RMS) Energy

These temporal and spectral characteristics help identify artifacts commonly found in synthetic speech.

### Model Training

DeepShield utilizes deep learning techniques such as:

* Convolutional Neural Networks (CNN)
* Bidirectional Long Short-Term Memory (BiLSTM)

The model learns hidden patterns from real and AI-generated audio samples to improve detection performance.

---

## 🛠️ Tech Stack

### Programming Language

* Python

### Deep Learning Frameworks

* TensorFlow
* Keras

### Audio Processing

* Librosa
* NumPy
* Pandas

### Backend

* Flask

### Frontend

* HTML5
* CSS3
* JavaScript

### Database

* SQLite

### Tools

* Git
* GitHub
* Visual Studio Code
* Jupyter Notebook

---

## 🎵 Supported Audio Formats

* WAV
* MP3
* FLAC
* M4A

> Remove unsupported formats if necessary.

---

## 📂 Project Structure

```text
DeepShield-AI-Voice-Detection/
│
├── backend/
│   ├── app.py
│   ├── auth.py
│   ├── detect.py
│   ├── extract_features.py
│   ├── db.py
│   ├── model/
│   │   └── deepfake_lstm_model.h5
│   ├── uploads/
│   └── logs/
│
├── frontend/
│   ├── static/
│   └── templates/
│
├── training/
│   ├── model_training.py
│   ├── process_dataset.py
│   └── audio_features.csv
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

## 🚀 Installation and Setup

### Clone the Repository

```bash
git clone https://github.com/sahanashreeg/DeepShield-AI-Voice-Detection.git

cd DeepShield-AI-Voice-Detection
```

### Create a Virtual Environment

```bash
python -m venv venv
```

### Activate the Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Linux / macOS

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
cd backend

python app.py
```

Open your browser and navigate to:

```text
http://127.0.0.1:5000
```

---

## 📊 Dataset

The model is trained using labeled datasets containing:

* Real human speech samples
* AI-generated voice samples
* Voice conversion recordings
* Synthetic speech generated by text-to-speech systems

Example datasets:

* LJSpeech  
* WaveFake
* Fake-or-Real Audio Dataset

Ensure proper licensing and ethical usage before using external datasets.

---

## 🎯 Project Outcomes

* Built an end-to-end AI-powered deepfake audio detection pipeline.
* Developed a Flask-based web application for audio analysis.
* Implemented secure audio upload and prediction workflows.
* Applied audio signal processing techniques for feature extraction.
* Improved understanding of deep learning and cybersecurity applications.

---

## 🔮 Future Enhancements

* Real-time microphone analysis
* Live audio stream detection
* Transformer-based architectures
* Multilingual support
* REST API integration
* Docker containerization
* Kubernetes deployment
* Explainable AI visualizations

---

## ⚠️ Disclaimer

DeepShield is intended for educational, research, and cybersecurity awareness purposes only.

No deepfake detection system guarantees 100% accuracy because synthetic voice generation technologies evolve rapidly and require continuous model updates.

Always combine automated detection results with human verification.

---

## 🤝 Contributing

Contributions, feature requests, and suggestions are welcome.

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push to your branch

```bash
git push origin feature-name
```

5. Open a Pull Request

---

## 📜 License

This project is licensed under the MIT License.

---

## 👩‍💻 Author

**Sahanashree G**

* GitHub: https://github.com/sahanashreeg
* LinkedIn: https://www.linkedin.com/in/YOUR-LINKEDIN-USERNAME/

If you found this project helpful, please consider giving it a ⭐ on GitHub.
