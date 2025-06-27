# 🗣️ CHINTU – Personal Voice Assistant Using Python 🎧

**CHINTU** is your very own voice-powered buddy, built with Python!  
It listens to your voice, understands commands, and performs fun and useful tasks like playing songs, telling the time, and even talking about you and your friends! 😄

---

## ✨ Features

- 🎧 Voice input using microphone
- 🧐 Recognizes and understands your voice
- 🎶 Plays YouTube songs
- 🧒 Tells the current time
- 📚 Gives short Wikipedia info
- 🤣 Tells programming jokes
- 🌐 Opens Chrome or VS Code
- 💖 Replies with custom messages for:
  - Chinni
  - Bhagyamma
  - Lokesh

---

## 🛠️ Tools & Technologies

- **Python 3.8 or above**
- **VS Code** or any code editor
- **Microphone**
- **Internet connection** (for YouTube/Wikipedia access)

---

## 📆 Project Setup Steps

### 🧪 Step 1: Create Project Folder

- Open VS Code
- Create a new folder (e.g., `chintu_voice_assistant`)

### 🔄 Step 2: Set Up a Virtual Environment

```
python -m venv venv
```

#### Activate the environment:

- **Windows**:
  ```
  venv\Scripts\activate
  ```
- **Mac/Linux**:
  ```
  source venv/bin/activate
  ```

You’ll see `(venv)` in your terminal – that means it’s activated ✅

### 📦 Step 3: Install Required Libraries

```
pip install SpeechRecognition pyttsx3 pywhatkit wikipedia pyjokes
```

---

## 📊 Library Overview

| Library              | Purpose                                  |
|----------------------|------------------------------------------|
| `speech_recognition` | Converts voice to text                   |
| `pyttsx3`            | Converts text to speech (offline)        |
| `pywhatkit`          | Plays YouTube videos                     |
| `wikipedia`          | Summarizes people or topics              |
| `pyjokes`            | Tells random programming jokes           |
| `os`, `sys`, `webbrowser` | Opens apps, exits assistant        |

---

## 🚀 Run the Assistant

```
python voiceassistant.py
```

On start, you’ll hear:
> "Yo! I'm CHINTU – your personal voice assistant 💡"

Now, try these commands:

- `play Shape of You`
- `what's the time`
- `who is bhagyamma`
- `open chrome`
- `tell me a joke`
- `exit`

---

## 📸 Demo Preview



https://github.com/user-attachments/assets/16a06e55-56c0-4531-9062-0c9b2dd863cc


---

## 👨‍💻 Author

**Samala Susmitha Reddy**  
Passionate about voice tech ✨  
[LinkedIn][http://www.linkedin.com/in/samala-susmitha-reddy-86056b302]

---

