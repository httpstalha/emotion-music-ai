# 🎵 Emotion Music AI Pro

An AI-powered music recommendation system that detects user emotions using **facial expressions** and **text sentiment analysis**, then recommends songs based on the detected mood.

---

## 🚀 Features

* 😊 Face Emotion Detection using AI/Computer Vision
* 💬 Text Emotion & Sentiment Analysis
* 🎶 Smart Music Recommendation System
* 📂 CSV-based Song Dataset
* 🌐 Simple Web Interface
* ⚡ Fast and Lightweight Python Backend
* 🧠 Multiple Emotion Categories Support

---

## 🛠️ Tech Stack

### Backend

* Python
* Flask
* OpenCV
* Machine Learning / AI Models

### AI Modules

* Face Emotion Recognition
* Text Sentiment Analysis
* Music Recommendation Engine

### Database / Dataset

* CSV Dataset (`songs.csv`)

---

# 📁 Project Structure

```bash
emotion_music_ai_pro/
│
├── app.py
├── requirements.txt
├── data/
│   └── songs.csv
│
├── backend/
│   ├── face_emotion.py
│   ├── text_emotion.py
│   ├── recommender.py
│   └── player_template.html
│
├── scrape.py
├── update_db.py
├── generate_hindi.py
└── README.md
```

---

# ⚙️ Installation

## 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/emotion_music_ai_pro.git
cd emotion_music_ai_pro
```

---

## 2️⃣ Create Virtual Environment

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

### Linux / Mac

```bash
python3 -m venv venv
source venv/bin/activate
```

---

## 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Run the Project

```bash
python app.py
```

Then open your browser:

```bash
http://127.0.0.1:5000
```

---

# 🧠 How It Works

## 🎥 Face Emotion Detection

The system captures facial expressions using the webcam and predicts emotions such as:

* Happy
* Sad
* Angry
* Neutral
* Fear
* Surprise

---

## 💬 Text Emotion Analysis

Users can enter text, and the system analyzes emotional sentiment using NLP techniques.

---

## 🎶 Music Recommendation

Based on detected emotion, the AI recommends matching songs from the dataset.

---

# 📊 Example Workflow

```text
User Face/Text Input
        ↓
Emotion Detection AI
        ↓
Mood Classification
        ↓
Song Recommendation
        ↓
Music Playback
```

---

# 📦 Requirements

Main libraries used:

```txt
flask
opencv-python
numpy
pandas
scikit-learn
tensorflow
keras
```

---

# 🌟 Future Improvements

* Spotify API Integration
* Real-Time Streaming
* Better Deep Learning Models
* Personalized Playlists
* Mobile App Version
* Voice Emotion Detection

---

# 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

---

# 📜 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

Developed with ❤️ by **Engnr Shb**

---

# ⭐ Support

If you like this project:

* Star the repository ⭐
* Share with others 🚀
* Contribute to improvements 💡
