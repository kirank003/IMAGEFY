# IMAGEFY
Imagify – AI Text-to-Image Generator
📌 Overview

Imagify is an AI-powered text-to-image generation tool that converts written prompts into high-quality visuals. It leverages Stable Diffusion through the Hugging Face Inference API, with a simple yet powerful web interface built using Flask, HTML, Bootstrap, and JavaScript.

🚀 Features

Convert text prompts into realistic AI-generated images

Clean and user-friendly interface with Bootstrap styling

Backend powered by Flask for request handling

Integration with Hugging Face Stable Diffusion API

Download or preview generated images instantly

🛠️ Tech Stack

Frontend: HTML, Bootstrap, JavaScript

Backend: Python (Flask)

API: Hugging Face Inference API (Stable Diffusion)

Other Tools: PIL, Requests

⚙️ Installation & Setup

Clone this repository:

git clone https://github.com/your-username/imagify.git
cd imagify


Create and activate a virtual environment:

python -m venv venv
source venv/bin/activate   # for Linux/Mac
venv\Scripts\activate      # for Windows


Install dependencies:

pip install -r requirements.txt


Add your Hugging Face API key in app.py:

HF_API_KEY = "your_api_key_here"


Run the Flask app:

python app.py


Open your browser and go to:

http://127.0.0.1:5000/.
