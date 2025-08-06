# Student Career Assistant Chatbot using Gemini 2.5
An AI-powered chatbot designed to guide engineering and management students in exploring career options, competitive exams, resume tips, and more — all through an interactive Gradio interface backed by Google’s **Gemini 2.5 (Flash)** model.

## Features
-Personalized career path guidance after **B.Tech**, **MCA**, **MBA**, etc.
-Preparation tips for **GATE**, **GRE**, **CAT**, and other competitive exams
-Suggestions for **higher education** opportunities like **MS**, **M.Tech**, **MBA**
-Resume writing help, trending skills, and industry-relevant job roles
-Built using **Gradio** and **Google Generative AI** (Gemini)

## Tech Stack
- **Google Generative AI (Gemini 2.5 Flash)**
- `google-generativeai` Python SDK
- **Gradio** for chatbot UI
- **Google Colab** for execution

## Installation
Install the required Python packages:
pip install -q google-generativeai gradio pillow

# API Key Setup
Get your Gemini API key from Google AI Studio.
In Google Colab, securely store your key:
python
Copy
Edit
from google.colab import userdata
//Store your API key like this:
userdata.set("GOOGLE_API_KEY", "your_actual_api_key")
