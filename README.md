# JARVIS – AI Personal Assistant

A Python-based personal desktop assistant inspired by the JARVIS system. This project combines voice recognition, speech responses, computer automation, basic AI interaction, and a futuristic HUD interface.

## Features

- **Voice Recognition** – Recognizes spoken commands using Faster-Whisper.
- **Voice Responses** – Responds using Microsoft Edge TTS.
- **Computer Automation** – Opens applications, folders, and websites.
- **System Monitoring** – Checks CPU, RAM, battery, and internet status.
- **Windows Controls** – Volume, brightness, screenshots, and window controls.
- **Power Management** – Lock, restart, shutdown, and sleep commands.
- **Basic AI Interaction** – Responds to common questions and greetings.
- **Web Search** – Retrieves Google search results.
- **Futuristic HUD Interface** – Animated JARVIS-inspired interface built with Tkinter.

## Technologies Used

- Python
- Faster-Whisper
- SpeechRecognition
- Microsoft Edge TTS
- Pygame
- Tkinter
- Psutil
- Requests

## Project Structure

```text
JARVIS/
│
├── ai/
│   ├── brain.py
│   └── web_search.py
│
├── core/
│   ├── assistant.py
│   ├── commands.py
│   └── voice.py
│
├── gui/
│   └── hud.py
│
├── system/
│   ├── apps.py
│   ├── power.py
│   ├── system_info.py
│   └── windows.py
│
├── config.py
├── main.py
├── requirements.txt
└── README.md
```

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/klkpofficial-ops/JARVIS---AI-Assistant.git
```

### 2. Open the project folder

```bash
cd JARVIS---AI-Assistant
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

### 4. Activate the environment (Windows)

```bash
venv\Scripts\activate
```

### 5. Install dependencies

```bash
pip install SpeechRecognition PyAudio edge-tts pygame faster-whisper psutil requests
```

## How to Run

### Start the Voice Assistant

```bash
python main.py
```

### Launch the HUD Interface

```bash
python gui/hud.py
```

## Example Voice Commands

- "Jarvis, open Google."
- "Jarvis, open YouTube."
- "Jarvis, open Notepad."
- "Jarvis, system status."
- "Jarvis, battery status."
- "Jarvis, increase volume."
- "Jarvis, take screenshot."
- "Jarvis, lock computer."

## Project Status

**Currently under development.**

The project includes a modular voice assistant, system automation features, basic AI responses, web search functionality, and a separate animated HUD interface.

Further development will focus on integrating the HUD with the voice assistant and expanding AI capabilities.

## Developer

**Developed by:** KLK P Official

## License

This project is licensed under the MIT License.
