<p align="center">
  <img src="SARA_Logo.png" width="200">
</p>

<h1 align="center">SARA AI</h1>
<h3 align="center">Smart Accessible Reader & Assistant</h3>

<p align="center">
"Created with love for the ones who can make this world a beautiful place to live in."
</p>

<p align="center">

![AI Model](https://img.shields.io/badge/AI-Llama%203.3-blue)
![Platform](https://img.shields.io/badge/Platform-Web%20Browser-green)
![Accessibility](https://img.shields.io/badge/Focus-Accessibility-purple)
![Languages](https://img.shields.io/badge/Languages-8%2B-orange)
![License](https://img.shields.io/badge/License-Educational-lightgrey)

</p>

---

#  About SARA AI

SARA AI is an **agentic AI-powered study assistant** built specifically for **visually impaired and dyslexic K-12 students**.

It is **fully voice-controlled, personalised, and works directly in the browser** — no installation required.

The project aims to make **AI-powered education accessible for students who cannot rely on traditional text-heavy interfaces.**

---

# Project Information

**Creators:**  
Aditya Rai  
Sparsh Ruhela  

**School:**  
Shaheed Rajpal DAV Public School, New Delhi

**Mentor:**  
Vineeta Garg

**Category:**  
Agentic AI • Assistive Technology • Inclusive Education

---

# The Problem

More than **253 million people worldwide are visually impaired**, and **hundreds of millions live with dyslexia**.

Most AI learning tools rely on:

- visual menus
- typing
- complex interfaces
- dense text content

These design choices make them **inaccessible for many students**.

As a result, **millions of learners cannot benefit from AI-assisted education.**

---

# The Solution — SARA AI

SARA AI is a **voice-driven AI tutor** that teaches, quizzes, motivates, and plans study sessions through **natural conversation**.

Students interact with SARA entirely through **voice commands**, making learning accessible for visually impaired and dyslexic learners.

The entire system runs **inside a web browser**, ensuring easy access without installation.

---

#  Key Features

###  Voice Control
- 30+ voice commands
- completely hands-free

###  AI Lessons
- personalised lessons based on **grade and board**

###  Smart Quiz
- answer questions using voice
- simply say **A, B, C or D**

###  Exam Mode
- full mock exams with voice interaction

### Timetable Scanner
- upload exam timetable image
- OCR automatically reads schedule

### Syllabus Upload
- upload syllabus
- SARA teaches chapter-by-chapter

###  Doubt Solver
- ask any question
- receive instant explanation

###  Multilingual Support
Supports **8+ languages** including:

- Hindi
- Tamil
- Telugu
- Bengali
- and more

###  Accessibility Controls
- adjustable font size
- line spacing control
- high contrast mode

###  Dyslexia Support
- OpenDyslexic font mode
- increased letter spacing
- simplified AI responses

###  PDF Reader
Upload study PDFs and **ask questions about the document**

### Motivational Coach
Encourages students during study sessions.

---

#  Comparison with Major AI Assistants

Many AI assistants exist today such as 1, 2, and 3.

However, they are designed for **general productivity**, not **accessibility-focused education**.

| Feature | SARA AI | ChatGPT | Google Gemini | Microsoft Copilot |
|--------|---------|---------|---------------|-------------------|
| Voice-First Learning | ✅ | ⚠️ Limited | ⚠️ Limited | ⚠️ Limited |
| Designed for Visually Impaired | ✅ | ❌ | ❌ | ❌ |
| Dyslexia Reading Mode | ✅ | ❌ | ❌ | ❌ |
| Voice Quiz Mode | ✅ | ❌ | ❌ | ❌ |
| Exam Simulation | ✅ | ❌ | ❌ | ❌ |
| Timetable Scanner (OCR) | ✅ | ❌ | ❌ | ❌ |
| Syllabus Upload Teaching | ✅ | ❌ | ❌ | ❌ |
| PDF Question Answering | ✅ | ⚠️ | ⚠️ | ⚠️ |
| Multilingual Support | ✅ | ✅ | ✅ | ✅ |
| Motivational Study Coach | ✅ | ❌ | ❌ | ❌ |
| Privacy-First (Local Processing) | ✅ | ⚠️ | ⚠️ | ⚠️ |

---
##  System Architecture

SARA AI follows a **voice-driven AI interaction pipeline** that converts student speech into intelligent spoken responses.

| Step | Component | Technology Used | Description |
|-----|-----------|----------------|-------------|
| 1 | Student Voice | Microphone Input | Student speaks a command or question to SARA |
| 2 | Speech Recognition | Web Speech API | Converts spoken words into text |
| 3 | SARA AI Agent | JavaScript Logic | Processes commands and determines the task |
| 4 | AI Model Processing | Groq API – Llama-3.3-70B | Generates intelligent responses |
| 5 | Response Generation | AI Output Processing | Formats response for the student |
| 6 | Text-to-Speech | Web Speech API | Converts AI response into spoken audio |
| 7 | Audio Response | Browser Audio Output | Student hears the answer from SARA |
---

## Components

###  Voice Input
Captures student speech using **Web Speech API**.

### AI Agent
Processes commands such as:

- "Hello SARA"
- "Start quiz"
- "Explain photosynthesis"
- "Read my syllabus"

###  Language Model
Uses **Groq API with Llama-3.3-70B** for intelligent responses.

###  OCR Engine
Powered by **Tesseract.js** for:

- timetable scanning
- syllabus reading
- text extraction

###  Text-to-Speech
Converts responses into spoken audio for accessibility.

---

#  Accessibility & Inclusion

SARA AI is built for two underserved communities.

##  Visually Impaired Students

- fully voice-controlled interface
- no mouse navigation required
- text-to-speech for all content
- high contrast display

##  Dyslexic Students

- OpenDyslexic font mode
- increased letter spacing
- simplified language output
- voice input eliminates typing barriers

---

#  Impact

- tested with visually impaired students
- evaluated by teachers
- **34% improvement in quiz scores after two weeks**

Potential reach:

- **253M visually impaired learners**
- **700M dyslexic learners worldwide**

---

#  Responsible AI

SARA AI follows privacy-first principles.

- no student data stored on servers
- all processing done locally in browser
- no login required
- designed for safe and fair AI usage

---

#  Repository Structure
-sara_student.html      → main application
- presentation.pptx      → project slides
- summary.docx.→ project report
- video_script.docx      → competition script
---

#  How to Run

1. Download `sara_student.html`
2. Open in **Google Chrome**
3. Allow microphone access
4. Say **"Hello SARA"**

The application runs **entirely in the browser**.

No installation required.

---

#  Creators

Aditya Rai  
Sparsh Ruhela  

Shaheed Rajpal DAV Public School  
New Delhi, India

Mentor: Vineeta Garg

---

#  License

© 2026 Aditya Rai & Sparsh Ruhela

This project is created for **educational and competition purposes**.
