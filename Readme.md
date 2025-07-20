# 🎧 Audio Dataset Streamlit App

This Streamlit app allows users to **upload** and **download categorized audio datasets** with a simple and clean interface.

---

## 🚀 Features

### 1. 📤 Input Data Section
- Choose a category (e.g., Agriculture, Food, Songs).
- Upload multiple audio files (`.mp3`, `.wav`, `.ogg`) to that category.
- Files are saved in a structured folder (`audio_data/<category>/`).

### 2. 📁 Explore Section
- Select a category to view uploaded files.
- Option to download **all audio files** in a category as a **ZIP file**.

---

## 📁 Available Categories

- Agriculture  
- Food  
- Places  
- Songs  
- Historical People  
- Education  
- Events  
- Skills  

---

## 🏗 Project Structure
audio-dataset-app/
├── app.py # Main Streamlit app code
├── README.md # This file
├── requirements.txt # Libraries needed to run
├── audio_data/ # Folder auto-created to store uploads


---

## ⚙️ How to Run

1. Clone this repo or download the files.

```bash
git clone https://github.com/your-username/audio-dataset-app.git
cd audio-dataset-app

Install dependencies:

pip install -r requirements.txt
Start the Streamlit app:

streamlit run app.py
Open http://localhost:8501 in your browser.

