# OLlama-AI-RPG
A vibe-coded Ollama based RPG created by Gemini.
Here are the external dependencies you need:

Pillow (PIL): This handles resizing and displaying the character avatars in the Tkinter UI.

Ollama (ollama): This is the official Python client that lets our script talk to your local AI models.

You can install both of them at once using your terminal or command prompt:

Bash
pip install pillow ollama

The Hidden Dependency: The Ollama App
Because this runs locally, the Python package alone isn't enough. You also need the actual Ollama software installed and running on your computer.

If you haven't set that up yet:

Download and install Ollama from their official website. (https://ollama.com/download/windows)

Open your terminal and pull a model so the script has a brain to talk to. For example, to get the default model we used in the code, run:

Bash
ollama run llama3
