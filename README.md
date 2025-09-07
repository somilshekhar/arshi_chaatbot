# 🤖 Arshi Chaatbot

<!-- Replace with actual banner image -->

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)  
[![LiveKit](https://img.shields.io/badge/LiveKit-Realtime%20AI-orange)](https://livekit.io/)  
[![License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)

---

## 📖 Overview

**Arshi Chaatbot** is a voice-enabled AI assistant built using Python and **LiveKit Realtime AI**. It can manage files, control windows, perform web searches, provide weather updates, and interact with your system via keyboard and mouse—all through **voice and keyboard commands**.  

🌟 **Key Features**:  
- Real-time voice & video assistant using LiveKit  
- Google search and date/time queries  
- Weather updates  
- File and folder control  
- Keyboard and mouse automation  
- Volume and media control  
- Extensible tool-based architecture  

---

## 🛠️ Technologies Used

- **Python** 🐍: Core programming language  
- **LiveKit Agents** 🎙️: Realtime AI voice assistant  
- **dotenv** 🔐: Environment variable management  
- **pyautogui** 🖱️: Keyboard & mouse automation  
- **Custom Modules**:  
  - `arshi_search` – Google search & datetime  
  - `arshi_weather` – Weather fetching  
  - `arshi_window_CTRL` – Open/close windows & folders  
  - `arshi_file_opner` – Play media files  
  - `keyboard_mouse_CTRL` – Mouse & keyboard tools  

---

## 🚀 Getting Started

### Prerequisites
- Python 3.8+  
- LiveKit Realtime access  
- OpenAI / Google API keys (if applicable)  
- Internet connection  

### Installation

1. **Clone the Repository**:

```bash
git clone https://github.com/somilshekhar/arshi_chaatbot.git
cd arshi_chaatbot
```

2. **Set Up a Virtual Environment**:

```bash
python -m venv venv
# Activate the virtual environment
# Windows:
venv\Scripts\activate
# macOS/Linux:
source venv/bin/activate
```

3. **Install Dependencies**:

```bash
pip install -r requirements.txt
```

4. **Configure Environment Variables**:

- Copy `.env.example` to `.env`  
- Add your API keys and any configuration variables required:

```
# Example
LIVEKIT_API_KEY=your_livekit_key
LIVEKIT_API_SECRET=your_livekit_secret
```

---

## 🧠 Usage

1. **Run the Assistant**:

```bash
python main.py
```

2. **Voice & Video Interaction**:  
   - Speak to Arshi Chaatbot in a LiveKit room.  
   - The assistant can respond, execute tools, or fetch information.  

3. **Available Tools**:

| Category | Tools |
|----------|-------|
| Web & Info | `google_search`, `get_current_datetime`, `get_weather` |
| File & Media | `Play_file`, `open`, `close`, `folder_file` |
| Keyboard & Mouse | `move_cursor_tool`, `mouse_click_tool`, `scroll_cursor_tool`, `type_text_tool`, `press_key_tool`, `press_hotkey_tool`, `swipe_gesture_tool`, `control_volume_tool` |

---

## 📂 Project Structure

```plaintext
arshi_chaatbot/
├── main.py                 # Main entrypoint using LiveKit AgentSession
├── arshi_prompts.py        # Behavior and reply prompts
├── arshi_search.py         # Google search & datetime tools
├── arshi_weather.py        # Weather fetching tools
├── arshi_window_CTRL.py    # Window and file control tools
├── arshi_file_opner.py     # Media file control
├── keyboard_mouse_CTRL.py  # Keyboard and mouse tools
├── requirements.txt        # Python dependencies
├── .env.example            # Example environment variables
└── README.md               # Project documentation
```

---

## 🎯 Applications

- **Personal Assistant**: Automate system tasks and fetch information effortlessly  
- **Productivity**: Control your system hands-free  
- **Accessibility**: Voice-based control for easier interaction  
- **Learning & Experimentation**: Explore AI agents and tool-based architecture  

---

## 🤝 Contributing

Contributions are welcome! 🙌  

1. Fork the repository  
2. Create a new branch (`git checkout -b feature-branch`)  
3. Commit your changes (`git commit -m 'Add new feature'`)  
4. Push to the branch (`git push origin feature-branch`)  
5. Open a Pull Request  

---

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

⭐ **Star this repository if you find it useful!**  
For questions or feedback, contact [Somil Shekhar](https://github.com/somilshekhar).
