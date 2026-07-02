# ✉️ Local AI Email Assistant

A local AI-powered email assistant built with Python, Streamlit, and Ollama that converts rough notes into professional emails instantly — completely free with no API costs!

---
---

## ✨ Features

- 📝 Convert rough notes into well-structured emails
- 🎯 Multiple tone options (Professional, Friendly, Apologetic, Direct)
- 🔒 Runs 100% locally — no API keys, no costs, no data sent to cloud
- ⚡ Powered by llama3 model via Ollama
- 🎨 Clean and simple Streamlit UI

---

## 🛠️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| Python | Core programming language |
| Streamlit | Web UI framework |
| Ollama | Local LLM runner |
| llama3 | AI language model |

---

## 📋 Prerequisites

Before running this project make sure you have:

- Python 3.8 or higher
- Ollama installed on your machine
- llama3 model downloaded

---

## ⚙️ Installation

**Step 1 — Clone the repository**
```bash
git clone https://github.com/vivek2004-sec/ai-email-assistant.git
cd ai-email-assistant
```

**Step 2 — Install Python dependencies**
```bash
pip install streamlit ollama
```

**Step 3 — Install Ollama**

Download from: https://ollama.com/download

**Step 4 — Pull llama3 model**
```bash
ollama pull llama3
```

**Step 5 — Run the app**
```bash
streamlit run app.py
```

**Step 6 — Open in browser**

---

## 📖 How to Use

1. Select your desired **email tone** from the dropdown
2. Enter your **rough notes** in the text area
3. Click **Generate Professional Email**
4. Copy the generated email and use it!

---

## 💡 Example

**Input (rough notes):**


---
---

## 🔧 Troubleshooting

**Blank screen on startup:**
```bash
# Make sure Ollama is running
ollama serve

# Hard refresh browser
Ctrl + Shift + R
```

**Ollama connection error:**
```bash
# Check if Ollama is running
ollama list

# Pull model again if needed
ollama pull llama3
```

**Module not found error:**
```bash
pip install streamlit ollama
```

---

## 🗺️ Future Improvements

- [ ] Add email subject line generator
- [ ] Add copy to clipboard button
- [ ] Support multiple AI models
- [ ] Add email templates
- [ ] Save email history
- [ ] Add dark/light mode toggle

---
## 👨‍💻 Author

**Vivek Kamble**
- GitHub: [@vivek2004-sec](https://github.com/vivek2004-sec)
- LinkedIn: [Vivek Kamble](https://www.linkedin.com/in/vivekkamble2004)
---

## 📄 License

This project is open source and available under the
[MIT License](LICENSE)

---

## ⭐ Support

If you found this project helpful please give it a ⭐ on GitHub!

---

*Built with ❤️ using Python, Streamlit and Ollama*
