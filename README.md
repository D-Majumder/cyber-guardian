<h1 align="center" id="title">Cyber Guardian</h1>

<p align="center"><img src="https://socialify.git.ci/D-Majumder/CyberGuardian/image?font=Bitter&amp;forks=1&amp;issues=1&amp;language=1&amp;name=1&amp;owner=1&amp;pattern=Brick+Wall&amp;pulls=1&amp;stargazers=1&amp;theme=Auto" alt="project-image"></p>

<p id="description">This repository contains the final project for an AI/ML internship. The project titled "CyberGuardian AI" is a speech-based chatbot assistant built to provide guidance and awareness on digital threats and online safety. The chatbot uses a custom-built knowledge base and a machine learning model to classify user intent and deliver relevant spoken responses.</p>

<p align="center"><img src="https://img.shields.io/badge/Cyber-Guardian-blue" alt="shields"><img src="https://img.shields.io/badge/D-Majumder-red" alt="shields"><img src="https://img.shields.io/badge/Jupyter-Lab-orange" alt="shields"></p>

  
  
<h2>🧐 Features</h2>

Here're some of the project's best features:

*   Voice-Enabled Interaction: The chatbot listens for user queries through the microphone and responds with synthesized speech.
*   AI-Powered Intent Classification: Utilizes a Logistic Regression model to understand the user's intent from their natural language query.
*   Custom Knowledge Base: All responses are fetched from a comprehensive custom-made .json dataset focused on digital safety and cyber awareness.
*   Dynamic and Interactive: The chatbot is designed to handle a wide range of queries related to phishing malware passwords online privacy and more.

<h2>🛠️ Installation Steps:</h2>

<p>1. Clone the Repository</p>

```
git clone https://github.com/D-Majumder/CyberGuardian
```

```
cd CyberGuardian
```

<p>3. Install Dependencies</p>

```
pip install speechrecognition pyttsx3 scikit-learn numpy pandas
```

```
pip install pyaudio
```

<p>5. Run the Jupyter Notebook</p>

```
jupyter notebook
```

<p>6. Execute the Cells</p>

```
The first cell loads the data and prepares the training sentences.
```

```
The second cell trains the LogisticRegression model.
```

```
The third cell contains the main conversational loop which will initiate the speech-based dialogue.
```

  
  
<h2>💻 Built with</h2>

Technologies used in the project:

*   Python: The core programming language.
*   Jupyter Notebook: Used for developing and demonstrating the chatbot's functionality.
*   scikit-learn: For the TfidfVectorizer and LogisticRegression model implementation.
*   speech\_recognition: To transcribe the user's voice input into text.
*   pyttsx3: To convert the chatbot's text responses back into speech.
*   json: For managing the chatbot's knowledge base.
