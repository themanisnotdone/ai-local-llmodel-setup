# ⚙️ Setting Up Ollama for Local LLMs

This guide walks you through installing **Ollama**, a powerful CLI/API tool for running open-source LLMs like LLaMA2, Mistral, and Gemma entirely on your local machine.

> 🧠 **Why Ollama?**
> - Simple CLI and API for direct model access
> - Actively developed with wide model support
> - No cloud dependency—everything runs locally
> - Perfect for automated, scriptable, or dev workflows

---

## 🪛 1. Install Ollama

### 🖥 macOS / Linux / Windows

Visit: [https://ollama.com/download](https://ollama.com/download)

Follow installation instructions for your OS. After install, open your terminal and verify:

```bash
ollama run llama2
This will:

Download the llama2 model (first-time only)
Launch an interactive shell interface
🧰 Basic Commands

ollama run mistral            # Run Mistral 7B
ollama pull gemma:2b          # Download Gemma 2B model
ollama list                   # List all models downloaded
ollama create mymodel -f Modelfile   # Custom model (advanced)

