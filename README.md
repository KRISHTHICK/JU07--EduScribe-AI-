# JU07--EduScribe-AI-
GEN AI

:

🎓 EduScribe AI – Lecture Notes Generator from Slides & Audio
🧠 What It Does
EduScribe AI automatically creates well-structured, editable lecture notes from uploaded:

🎤 Lecture audio (MP3/WAV)

📊 PowerPoint slides (PPTX)

📝 Combines content and generates:

Summarized notes per slide/topic

Question–Answer pairs for revision

Key terms and definitions

Smart highlights and diagrams (optional)

⚙️ Key Features
Feature	Description
📤 Upload PPTX and Audio	Users upload their slide deck + recorded class audio
🎯 Slide-by-Slide Summary	Generates a paragraph per slide/topic
🔍 Smart Q&A Generation	Creates revision questions based on context
🧠 Keyword Highlighter	Extracts key terms and definitions
📄 Download Notes	Outputs as Word or PDF
🗂️ Multi-topic Support	Supports lectures with sections/modules

👩‍🏫 Ideal Use Cases
Teachers generating notes post-class

Students summarizing webinars/lectures

EdTech platforms auto-generating learning material

Coaching centers creating handouts

🧱 Tech Stack
Layer	Tool
UI	Streamlit
PPT Parsing	python-pptx
Audio Transcription	Whisper (local or OpenAI API)
LLM	Ollama (TinyLLaMA / LLaMA3) or GPT
Notes Format	python-docx or fpdf

📦 Sample Output
json
Copy
Edit
{
  "Topic": "Artificial Intelligence",
  "Slide 3 Summary": "AI refers to machines that mimic cognitive functions...",
  "Key Terms": ["Artificial Intelligence", "Machine Learning", "Neural Networks"],
  "Generated Q&A": [
    {"Q": "What is Artificial Intelligence?", "A": "It is the simulation of human intelligence by machines."}
  ]
}
🔮 Future Add-ons
Live mode (record + auto-generate notes)

Speaker diarization (multi-speaker support)

Slide-to-topic mapping

Notes personalization (based on learning level)


# 🎓 EduScribe AI – Lecture Notes Generator

EduScribe AI is an AI-powered tool to convert lecture slides and audio into clean, structured, and editable notes with Q&A and key terms.

## 🚀 Features

- Upload PPTX slide decks
- Upload corresponding lecture audio
- Transcribes audio using Whisper
- Generates:
  - Slide-based summaries
  - Revision questions
  - Key definitions
- Output shown in Markdown

## 🛠️ Setup

```bash
git clone https://github.com/yourusername/eduscribe-ai.git
cd eduscribe-ai
pip install -r requirements.txt
ollama pull llama3
streamlit run app.py
