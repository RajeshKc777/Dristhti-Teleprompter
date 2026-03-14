# 🎬 Drishti - Teleprompter

![Platform](https://img.shields.io/badge/Platform-Windows-0078D6?logo=windows&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Active-success)

> **A modern desktop teleprompter for creators, educators, presenters, and anyone who wants to read smoothly on camera.**

---

## ✨ What Drishti Does

🎯 **Smart Reading Experience**
- 📝 Load or paste your script
- 🔄 Auto-scroll with speed control
- 🎨 Customize text size, colors, and opacity
- 🤖 Generate or refine scripts using AI
- 🎤 Voice input and text-to-speech in one place

---

## 👥 Who Is This For?

Drishti is built for:

- 🎥 **Content Creators** and YouTubers
- 👨‍🏫 **Teachers** and trainers
- 🎤 **Public Speakers** and presenters
- 💼 **Interview Prep** and practice sessions
- 🖥️ **Non-technical Users** who want a simple teleprompter app on Windows

---

## 🚀 Main Features

### 📺 Teleprompter Core
- ✅ Clean display with large readable text
- ▶️ Auto-scroll with play/pause, reset, and speed presets
- ⌨️ Manual scroll controls with keyboard support
- 📁 File support: `.txt` and `.docx`
- ✏️ Quick script editing: paste, clear, save

### 🎨 Customization
- 🔤 Font family and font size controls
- 🌈 Text color and background color customization
- 👁️ Window opacity and always-on-top option
- 🖼️ Fullscreen mode for distraction-free reading

### 🤖 AI-Powered Features
- 💬 AI script generation and chat sidebar
- 🔌 **Multiple AI Provider Support:**
  - OpenAI
  - Anthropic Claude
  - Google Gemini
  - Local models (Ollama / LM Studio)
  - Custom OpenAI-compatible providers
- 🔍 Auto-detect AI models from provider endpoints
- ✅ Built-in connection test for AI settings

### 🎙️ Voice Tools
- 🔊 **Text-to-Speech** (read script out loud)
- 🎤 **Speech-to-Text** (mic transcription into prompt)

### 💾 Persistence
- 🔐 Persistent settings (saved between launches)
- 📋 Keyboard shortcut helper
- ℹ️ About dialog

---

## ⚡ Getting Started

> [!TIP]
> **No installation needed! Just download and run.**

1. Download `Drishti.exe`
2. Double-click to launch
3. Start creating! ✅

---

## 📖 How To Use Drishti

### 📺 Basic Teleprompter Workflow

1. **📂 Open Script:**
   - Click **Open** button or press `Ctrl+O`
   - Or paste your text with `Ctrl+V`

2. **🎨 Adjust Readability:**
   - **Font size:** Use toolbar `+`/`-` buttons or `Ctrl++` / `Ctrl+-`
   - **Colors:** Click text/background color buttons in toolbar
   - **Opacity:** Adjust for see-through effect
   - **Dark/Light mode:** Toggle for comfort

3. **▶️ Start Reading:**
   - Press **Play** button or hit `Space`
   - Adjust speed with teleprompter speed controls
   - Pause/resume anytime with `Space`

4. **🖼️ Present in Fullscreen:**
   - Press `F11` to toggle fullscreen mode
   - Perfect for recording or presenting

5. **💾 Save Your Script:**
   - Click **Save** or press `Ctrl+S`
   - Supports `.txt` and `.docx` formats

---

### 🤖 Using AI Features

> [!NOTE]
> **AI features require an API key from your chosen provider**

#### Setup:

1. Open **AI > AI Settings...**
2. Choose your provider:
   - **OpenAI** (ChatGPT)
   - **Anthropic Claude**
   - **Google Gemini**
   - **Local** (Ollama / LM Studio - runs on your computer)
   - **Custom** (any OpenAI-compatible API)

3. Enter your API key (if using cloud providers)
4. Enter API URL and model name
5. Click **Auto Detect Model** (optional)
6. Click **Test Connection** to verify
7. Click **Save**

#### Usage:

**Option 1: Generate Script**
- Go to **AI > Generate Script...**
- Describe what you want
- AI creates the script
- Click to load into teleprompter

**Option 2: AI Chat Sidebar**
- Type your prompt
- Click send
- Review AI response
- Pin result to teleprompter if you like it

---

### 🎙️ Voice Tools

**🔊 Text to Speech:**
- Loads your current script
- Reads it aloud with karaoke-style word highlighting
- Great for practicing delivery

**🎤 Speech to Text:**
- Click microphone icon
- Speak your prompt
- Text appears in the prompt area
- Hands-free script creation!

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Ctrl+O` | 📂 Open script |
| `Ctrl+S` | 💾 Save script |
| `Ctrl+V` | 📋 Paste script |
| `Ctrl++` | ➕ Increase font size |
| `Ctrl+-` | ➖ Decrease font size |
| `F11` | 🖼️ Toggle fullscreen |
| `Space` | ▶️ Start/Stop auto-scroll |
| `Up / Down` | ⬆️⬇️ Manual scroll |

---

## 🔧 Troubleshooting

### ❌ AI is not responding

> [!WARNING]
> Check your AI configuration

- Open **AI Settings** and verify:
  - ✅ Correct provider selected
  - ✅ Valid API key entered
  - ✅ Correct API URL
  - ✅ Model name is correct
- Click **Test Connection** to diagnose
- For **local AI** (Ollama/LM Studio), make sure the app is running

---

### 🎤 Microphone not working

> [!IMPORTANT]
> Check Windows permissions

- Go to **Windows Settings > Privacy > Microphone**
- Make sure microphone access is enabled
- Restart Drishti after changing permissions

---

### 🔊 Text-to-Speech has no sound

- Check your system volume
- Make sure speakers/headphones are connected
- Restart Drishti
- Try selecting a different voice in Windows TTS settings

---

### 📄 Can't open .docx files

- Make sure the file isn't open in Microsoft Word
- Try copying the text and pasting it instead
- Save as `.txt` if issues persist

---

## 🔒 Privacy & Data

> [!NOTE]
> Your data, your control

**What's stored locally:**
- 💾 App settings in `teleprompter_settings.json`
- 📁 Your scripts (only if you save them)

**What's sent to the internet:**
- ☁️ **Cloud AI providers** (OpenAI, Claude, Gemini): Your prompts and scripts when using AI features
- 🏠 **Local AI** (Ollama/LM Studio): Nothing! Everything stays on your computer

**What's NOT collected:**
- ❌ No analytics
- ❌ No telemetry
- ❌ No tracking

---

## 💡 Tips & Tricks

> [!TIP]
> **Pro tips for better teleprompter experience**

🎯 **For Recording:**
- Use fullscreen mode (`F11`)
- Set opacity to 30-50% to see your camera preview behind the text
- Enable "Always on Top" to keep teleprompter visible

📝 **For Script Writing:**
- Use AI to generate first drafts
- Edit and refine in the app
- Save multiple versions for different takes

⚡ **For Speed Control:**
- Start slow and increase gradually
- Save your preferred speed as a preset
- Use keyboard shortcuts for quick adjustments

---

## 👨‍💻 Credits

**Developed by Rajesh Katuwal**

🌐 **Website:** [rajeshkatuwal.com.np](https://rajeshkatuwal.com.np/)

☕ **Support the Project:** [Buy Me a Coffee](https://www.buymeacoffee.com/rajeshkatuwal)

---

<div align="center">

### ⭐ Enjoying Drishti? Share it with other creators!

![Made with Love](https://img.shields.io/badge/Made%20with-❤️-red)
![Built for Creators](https://img.shields.io/badge/Built%20for-Creators-ff69b4)

**Questions or feedback? Reach out via the website!**

</div>
