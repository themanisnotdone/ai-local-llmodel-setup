# ⚙️ Setting Up Local Models with Ollama and LM Studio

This guide walks you through installing **Ollama** and/or **LM Studio**, two tools for running open-source LLMs like LLaMA2, Mistral, and Gemma entirely on your machine.

> 🧠 **Why these tools?**
> - **Ollama**: Great CLI/API interface. Easy model switching. Actively developed.
> - **LM Studio**: GUI-based, beginner-friendly, local chat + API access.
> - Both tools allow fully offline inference once models are downloaded.

---

## 🪛 1. Install Ollama

### 🖥 macOS / Linux / Windows

Visit: [https://ollama.com/download](https://ollama.com/download)

Follow the instructions for your OS. It handles everything, including dependencies.

Once installed, verify with:

```bash
ollama run llama2
