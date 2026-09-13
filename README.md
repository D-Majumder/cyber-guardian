# CyberGuardian

A speech-based chatbot assistant that provides guidance and awareness on digital threats and online safety.

## Overview

This repository contains the final project for an AI/ML internship. CyberGuardian AI is a voice-interactive chatbot built to answer questions about digital safety — phishing, malware, passwords, and online privacy — using a custom knowledge base and a machine learning intent classifier.

## Features

- **Voice-enabled interaction** — listens for user queries through the microphone and responds with synthesized speech.
- **AI-powered intent classification** — uses a Logistic Regression model to understand the user's intent from natural language.
- **Custom knowledge base** — responses are fetched from a custom-built JSON dataset (`dataset.json`) focused on digital safety and cyber awareness.
- **Broad query handling** — designed to handle a range of queries related to phishing, malware, passwords, online privacy, and more.

## Tech stack

- Python
- Jupyter Notebook (`chatbot.ipynb`)
- scikit-learn (`TfidfVectorizer`, `LogisticRegression`)
- `speech_recognition` — transcribes voice input to text
- `pyttsx3` — converts text responses back to speech
- `json` — knowledge base storage

## Setup

```bash
git clone https://github.com/D-Majumder/cyber-guardian
cd cyber-guardian
pip install speechrecognition pyttsx3 scikit-learn numpy pandas pyaudio
jupyter notebook
```

Open `chatbot.ipynb` and execute the cells in order:
1. Loads the data and prepares training sentences.
2. Trains the Logistic Regression model.
3. Runs the main conversational loop, which starts the speech-based dialogue.

## License

No license file is currently present in this repository. Without one, all rights to the code are reserved by the author by default.
