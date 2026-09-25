# Gen-AI Dockerfile Generator

A simple Gen-AI project that generates Dockerfiles using Python and Ollama.

Instead of writing a Dockerfile from scratch, you enter the programming language and the local AI model generates a Dockerfile based on common best practices.

## How It Works
Language → Python Script → Ollama (Llama 3.2) → Dockerfile

## Tech Used

* Python
* Ollama
* Llama 3.2
* Docker

## Run the Project

Install the Python dependency:

pip install -r requirements.txt

Make sure Ollama is installed and the model is available:

ollama pull llama3.2

Run the script:

python generate_dockerfile.py

Enter a language when prompted, for example:

Enter the programming language: Python

The generated Dockerfile will be displayed in the terminal.

## Purpose

I built this project to explore how **Generative AI can be used to automate common DevOps tasks**, such as creating Dockerfiles.

