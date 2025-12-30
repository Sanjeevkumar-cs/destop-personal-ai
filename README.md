# AI Jarvis – Voice Assistant in Python

AI Jarvis is a **voice-controlled desktop assistant** built with Python. It listens to user commands, recognizes speech, and performs everyday tasks such as opening websites, playing music, launching applications, and announcing the current time.

---

##  Features
- **Speech Recognition**: Captures and processes voice commands using `speech_recognition`.
- **Text-to-Speech**: Responds with voice using Microsoft SAPI (`win32com.client`).
- **Web Automation**: Opens websites like YouTube, Google, and Copilot.
- **Music Playback**: Plays local audio files by name.
- **App Control**: Launches system applications (Camera, Snipping Tool, MS Word).
- **Time Announcements**: Speaks out the current system time.
- **Exit Command**: Gracefully shuts down when the user says *"goodbye"*.

---

## Tech Stack
- **Python 3**
- `speech_recognition` (Google Speech API)
- `win32com.client` (Microsoft SAPI for voice output)
- `webbrowser`, `os`, `subprocess`, `datetime`

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/AI-Jarvis.git
   cd AI-Jarvis

---

1. Install dependencies:
   ```bash
   pip install speechrecognition pywin32

2. Run the script::
   ```bash
   python jarvis.py

