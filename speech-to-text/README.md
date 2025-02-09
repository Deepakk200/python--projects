# 🎤 **Speech-to-Text & Text-to-Speech Converter** 🔊  

A Python script which converts **real-time speech into text** and **reads it back** using AI-driven speech recognition. 🚀  

---

## 📌 **Features**  
✅ **Real-Time Speech Recognition** – Converts spoken words into text.  
✅ **Text-to-Speech Conversion** – Reads back the recognized text.  
✅ **Handles Ambient Noise** – Automatically adjusts to background noise.  
✅ **Error Handling** – Catches request errors and unknown speech input.  

---

## 🛠 **Prerequisites**  

Before running this script, ensure you have the following dependencies installed:  

### 📌 **Install Required Libraries**  
```bash
pip install SpeechRecognition pyttsx3 pyaudio
```
- **`SpeechRecognition`** – Recognizes and transcribes spoken words.  
- **`pyttsx3`** – Converts text to speech using offline TTS engines.  
- **`pyaudio`** – Captures real-time audio from the microphone.  

---

## 🚀 **How to Use**  
1️⃣ Run the script in your terminal:  
   ```bash
   python speech_to_text.py
   ```  
2️⃣ Speak into the microphone when prompted.  
3️⃣ The program will transcribe your speech and read it back to you.  

---

## ⚠ **Troubleshooting**  

### 🔹 **Facing "No module named 'pyaudio'" Error?**  
Try installing **pyaudio** using this alternative command:  
```bash
pip install pipwin  
pipwin install pyaudio  
```  

### 🔹 **Microphone Not Detecting Input?**  
- Ensure your microphone is enabled in system settings.  
- Run the script as administrator for permission issues.  

---

Let me know if you need any modifications! 😊
