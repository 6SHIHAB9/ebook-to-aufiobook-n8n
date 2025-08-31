# 📖➡️🎧 eBook to Audiobook (English Only)

This project is an **n8n automation workflow** that converts your eBooks or text files into an audiobook in English.  
It uses Text-to-Speech (TTS) to read the text and FFmpeg to merge audio chunks into one smooth file.  

---

## ✨ Features
- Convert **text/eBooks** into spoken audio (English only)  
- Automatically splits long text into smaller parts  
- Generates a single **.mp3 audiobook** file  
- Fully automated with **n8n**  

---

## 🚀 How It Works
Input Text (.txt) ➡️ Split ➡️ TTS (English) ➡️ Merge ➡️ Final Audiobook (.mp3)

## 🔧 Setup
1. Install & run **n8n**  
2. Import the workflow file: `workflows/ebook-to-audio.json`  
3. Configure your **TTS credentials** (English voice only)  
4. Install **FFmpeg** on your system  
5. Run the workflow with your `.txt` file  

