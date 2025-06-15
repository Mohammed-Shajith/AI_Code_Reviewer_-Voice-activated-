# **AI Code Reviewer**  
### _Voice Activated_

An AI-powered code review assistant that takes your voice input as a command , just say"Review code" and just give your path of any language (py,C,CPP,java), and intelligently analyzes it for potential improvements, syntax issues, and suggestions. Built using speech recognition and natural language processing libraries, this tool simplifies and speeds up the code review process.

---

##  Features

-  **Voice-to-Code**: Speak your Python code – the bot will transcribe and review it.
-  **AI-based Review**: Detects code smells, errors, and offers suggestions.
-  **Real-time Feedback**: Immediate analysis on spoken or written code.

---

## How to Run

### Option 1: Run via Jupyter Notebook
1. Open the `.ipynb` file.
2. Run all cells in order.
3. Ensure your microphone is active and permitted.

### Option 2: Run with Streamlit UI
```bash
pip install -r requirements.txt
streamlit run st.py
```

---

##  Requirements

Install dependencies using pip:
```bash
pip install -r requirements.txt
```

Required packages include:
- `streamlit`
- `speechrecognition`
- `pyaudio`
- `openai` or similar for AI-based suggestions
- `ast`, `io`, and other built-in Python modules

---

##  Files Included

- `AI_Code_Reviewer.ipynb` – Jupyter notebook for core logic.
- `st.py` – Streamlit version of the same application (UI-based).
- `requirements.txt` – All Python package dependencies.
- `README.md` – You’re reading it!

---

##  Author

**MOHAMMED SHAJITH**  
[LinkedIn Profile](https://www.linkedin.com/in/shajith-a-32aaa6287?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)