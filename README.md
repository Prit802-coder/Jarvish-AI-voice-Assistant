# 🤖 Jarvish - AI Voice Assistant

Jarvish is a Python-based AI Voice Assistant inspired by Alexa and Google Assistant. It listens for the wake word **"Jarvis"**, understands voice commands using Speech Recognition, and responds with natural speech. The assistant can perform various everyday tasks such as opening websites, playing music, fetching the latest news, and answering questions using the Groq LLM API.

---

## ✨ Features

- 🎙️ Wake word detection ("Jarvis")
- 🗣️ Speech-to-Text using Google Speech Recognition
- 🔊 Text-to-Speech responses
- 🤖 AI-powered conversations using Groq API
- 🌐 Open websites like Google, YouTube, Netflix, Flipkart
- 🎵 Play music through voice commands
- 📰 Fetch and read the latest news
- ⏰ Fast voice interaction with hands-free operation

---

## 🛠️ Technologies Used

- Python
- SpeechRecognition
- PyAudio
- pyttsx3
- Groq API
- News API
- Requests
- python-dotenv
- Webbrowser Module
- OS Module

---

## 📂 Project Structure

```
Jarvish/
│── main.py
│── client.py
│── musiclibrary.py
│── .env
│── .gitignore
│── README.md
```

---

## 🚀 Installation

### 1. Clone the repository

```bash
git clone https://github.com/Prit802-coder/Jarvish.git
```

### 2. Navigate into the project

```bash
cd Jarvish
```

### 3. Create a virtual environment

```bash
python -m venv .venv
```

### 4. Activate the virtual environment

**Windows**

```bash
.venv\Scripts\activate
```

**Linux / macOS**

```bash
source .venv/bin/activate
```

### 5. Install dependencies

```bash
pip install -r requirements.txt
```

### 6. Create a `.env` file

```env
GROQ_API_KEY=your_groq_api_key
NEWS_API_KEY=your_news_api_key
```

### 7. Run the assistant

```bash
python main.py
```

---

## 🎤 Example Voice Commands

- "Jarvis"
- "Open Google"
- "Open YouTube"
- "Open Netflix"
- "Play Believer"
- "News"
- "Open Flipkart"

---

## 🔒 Security

API keys are stored securely using a `.env` file and are excluded from version control through `.gitignore`.

---

## 🔮 Future Enhancements

- 🌤️ Weather updates
- 📧 Email sending
- 📅 Calendar & reminders
- 📝 Notes and To-Do List
- 💻 System control (volume, brightness, screenshots)
- 🎵 Spotify integration
- 📍 Location-based services
- 🧠 Conversation memory
- 🌍 Multi-language support
- 🖥️ GUI/Desktop Interface

---

## 👨‍💻 Author

**Prit Trivedi**

GitHub: https://github.com/Prit802-coder

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!
