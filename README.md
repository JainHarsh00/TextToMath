# Text-to-Math Problem Solver & Data Search Assistant (Streamlit + Groq + LangChain)

An interactive Streamlit app that:
- solves natural-language math problems step-by-step,
- performs quick factual lookups via Wikipedia,
- and reasons through general questions — all powered by **Groq’s `gemma2-9b-it`** through **LangChain**.

> 💡 This is the first milestone in my Generative AI journey!

---

## ✨ Features
- 🧮 **Math solver** using `LLMMathChain` for structured calculations  
- 🔍 **Wikipedia tool** for concise factual lookups  
- 🧠 **Reasoning tool** with a custom prompt for point-wise explanations  
- 💬 **Chat-style UI** with message history in Streamlit  
- 🔐 Works locally with `.env`, and on Streamlit Cloud using **Secrets**

---

## 🧱 Tech Stack
- **Python**, **Streamlit**
- **LangChain** (`LLMMathChain`, `LLMChain`, Tools/Agents)
- **Groq** via `langchain_groq` (`gemma2-9b-it`)
- **WikipediaAPIWrapper** (from `langchain_community`)

## 🔎 Try it Out : [Text To Math]
