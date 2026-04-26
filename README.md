# 🤖 HAI - Local AI Chat (Linux)

**HAI** is a minimalist, 100% offline AI chat application built with **Flutter** and **llama.cpp**. It allows you to run powerful Large Language Models (LLMs) locally on your Linux machine with total privacy. No internet, no tracking, and no subscriptions.

## 🚀 Quick Start

1.  **Download:** Grab the latest `linux-x64.tar.gz` from the **[Releases]** tab.
2.  **Extract:** Unpack the archive to a folder of your choice.
3.  **Add a Model:** * Create a folder named `models` inside the app directory.
    * Place your favorite **.gguf** model files inside (e.g., Llama 3 or Mistral).
4.  **Run:** Execute the binary directly from your terminal or file manager.

## 🛠 Features

* **Privacy First:** Your data never leaves your machine. Chats are stored locally in the `/chats` folder.
* **User Personas:** Save specific user information and profiles in the "Persona" section to provide the AI with your personal context.
* **Custom Instructions:** Fully edit the system prompt for every chat to define how the AI should behave.
* **Granular Control:** Adjust **Temperature**, **Context Length**, and **Frequency Penalty** in the model settings.
* **Zen Design:** A clean, responsive interface built with Flutter, designed for focus.

## 📁 Project Structure

The app manages your data using the following local files:
* `/models` — Folder for your `.gguf` model files.
* `/chats` — Your conversation history and AI instructions (JSON).
* `/personas.json` — Stores your saved user profiles.
* `/config.json` — Stores your hardware and model parameters.

## ⚠️ Requirements

* **OS:** Modern 64-bit Linux distribution.
* **Hardware:** 8GB RAM minimum (16GB+ recommended for larger models).
* **Optimization:** Optimized for **CPU-based inference** using `flash_attn` to ensure a smooth experience on all systems, including laptops with integrated graphics.

---
*Note: This application is a runner only and does not include AI models. You must provide your own .gguf files.*
