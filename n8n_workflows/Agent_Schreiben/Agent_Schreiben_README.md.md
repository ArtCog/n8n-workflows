# 🧠 Agent Schreiben — Adaptive AI Writing Evaluator

An advanced n8n-based agent that not only evaluates German exam writing tasks (Goethe B1/B2) but also learns, remembers, and adapts to each individual learner.  
Built as a **modular component** of a full Goethe-exam simulation system.

---

## 🎯 Purpose
To provide an **intelligent, self-learning feedback environment** where each student can practise, receive human-level evaluation, and see an ideal model answer — all within a single Telegram-based interface.

---

## ⚙️ Key Features
- **Official Rubric Evaluation:**  
  Objective scoring by Goethe B1/B2 criteria (Erfüllung, Kohärenz, Wortschatz, Strukturen).

- **Persistent Memory (Supabase):**  
  Each user’s history, strengths, and weaknesses are stored, allowing personalized feedback over time.

- **Self-Learning & Adaptivity:**  
  The agent continuously refines its advice and evaluation style based on stored interactions — forming an individualized teaching strategy.

- **Personalized Coaching:**  
  Instead of generic comments, users receive targeted, learner-specific recommendations drawn from their own previous work.

- **Ideal Letter Generation:**  
  Produces a flawless B1-level version of the student’s text for comparison and imitation.

- **Voice Interaction:**  
  Supports voice input and transcription; future versions enable spoken feedback (TTS).

- **Modular Architecture:**  
  Designed for integration with other n8n-based exam modules (Sprechen, Hören, Lesen, Schreiben) — enabling a full Goethe B1 simulation.

---

## 🧩 Workflow Logic
1. **Input:** user sends text or voice message.  
2. **Transcription:** voice converted to text via OpenAI Whisper.  
3. **Evaluation:** LLM scores the text by official rubric.  
4. **Scoring & Memory:** results stored in Supabase; long-term learning enabled.  
5. **Feedback:** AI coach generates short feedback and personalized recommendations.  
6. **Ideal Version:** system creates a perfect sample letter for reference.  
7. **Return:** user receives everything directly in Telegram.

---

## 📊 Result
✅ Real-time, human-level evaluation of writing.  
✅ Personalized improvement roadmap based on past performance.  
✅ 🧩 *Students gain a unique opportunity to test themselves under conditions identical to a real Goethe exam.*

---

## 🧰 Tech Stack
- **n8n** — core automation engine  
- **OpenAI API / OpenRouter** — evaluation & generation  
- **Supabase** — long-term memory and user data  
- **Telegram Bot API** — user interaction layer  
- **LangChain / Whisper / TTS** — natural-language and voice modules  

---

## 📄 Files
- `AGENT_Schreiben_V1.json` — complete workflow  
- `README.md` — project documentation (this file)

---

© 2025 — Art | Automation Engineer & AI Workflow Architect
