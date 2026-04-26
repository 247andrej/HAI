# 🤖 HAI - Local AI Chat

**HAI** is a minimalist, 100% offline AI chat application built with **Flutter** and **llama.cpp**. It allows you to run powerful Large Language Models (LLMs) locally on your own hardware with total privacy. No internet, no tracking, and no subscriptions.

## 🚀 Quick Start

1.  **Download:** Grab the latest release for your OS from the **[Releases]** tab:
    * `windows-x64.zip`
    * `linux-x64.tar.gz`
2.  **Extract:** Unzip the archive to a folder of your choice.
3.  **Add a Model:**
    * Create a folder named `models` inside the app directory.
    * Place your favorite **.gguf** model files inside (e.g., Llama 3, Mistral, or Phi-3).
4.  **Run:** Launch the executable (`main.exe` on Windows or the binary on Linux).

## 🛠 Features

* **Privacy First:** Your data never leaves your machine. Chats are stored locally in the `/chats` folder.
* **User Personas:** Save specific user information and profiles in the "Persona" section to quickly swap between different user contexts.
* **Custom Instructions:** Fully edit the system prompt for every chat to define exactly how the AI should behave.
* **Granular Control:** Adjust **Temperature**, **Context Length**, and **Frequency Penalty** in the model settings to fine-tune your experience.
* **Zen Design:** A clean, responsive interface designed for focus.

## 📁 Project Structure

The app manages your data using the following local files:
* `/models` — Folder for your `.gguf` model files.
* `/chats` — Your conversation history and AI instructions (JSON).
* `/personas.json` — Stores your saved user profiles.
* `/config.json` — Stores your hardware and model parameters.

## ⚠️ Requirements

* **OS:** Windows 10/11 (64-bit) or modern 64-bit Linux.
* **Hardware:** 8GB RAM minimum (16GB+ recommended).
* **Optimization:** Optimized for **CPU-based inference** to ensure a smooth experience on all devices, including laptops with integrated graphics.

---
*Note: This application is a runner only and does not include AI models. You must provide your own .gguf files.*
