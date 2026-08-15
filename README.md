🎙️ Voice-to-Voice AI Assistant
📌 Project Description
This project is a Voice-to-Voice AI Assistant that receives spoken input, converts the speech into text, sends the text to a Large Language Model (LLM) to generate a response, and then converts the AI response back into speech.
The project was developed using Google Colab and Python.
🎯 Project Objective
The objective of this project is to build a simple intelligent voice assistant that can understand spoken input and respond with a generated voice response.
🔄 How the Project Works
The project consists of three main stages:
1. Speech-to-Text
The user provides an audio input. The Whisper speech recognition model processes the audio and converts the spoken words into written text.
2. LLM Processing
The recognized text is sent to the Cohere Large Language Model. Cohere analyzes the user's question and generates an appropriate response.
3. Text-to-Speech
The generated response is converted from text into speech using Google Text-to-Speech (gTTS). The resulting audio file is then played for the user.
🛠️ Technologies Used
Python
Google Colab
OpenAI Whisper
Cohere API
gTTS (Google Text-to-Speech)
IPython Audio
📋 Project Workflow
Audio Input
     ↓
Speech-to-Text (Whisper)
     ↓
Text
     ↓
Cohere LLM
     ↓
AI Response
     ↓
Text-to-Speech (gTTS)
     ↓
Audio Output
⚙️ Installation
The required libraries can be installed using:
!pip install -q openai-whisper cohere gTTS
▶️ How to Run the Project
Open the Voice_to_Voice_AI_Assistant.ipynb notebook using Google Colab.
Install the required libraries.
Import the required Python libraries.
Load the Whisper model.
Enter the Cohere API key when requested.
Record or provide an audio input.
Whisper converts the audio into text.
The text is sent to the Cohere language model.
Cohere generates an AI response.
gTTS converts the response into an audio file.
The generated audio response is played.
🔐 API Key Security
The Cohere API key is not written directly in the source code.
The key is entered securely at runtime using a hidden input field. The API key should never be uploaded or shared publicly on GitHub.
🧪 Example
Input
The audio input asks:
Can you tell me what artificial intelligence is?
Speech-to-Text Output
Can you tell me what artificial intelligence is?
AI Response
The Cohere language model generates an explanation of artificial intelligence.
Final Output
The generated response is converted into speech and played as an audio response.
✅ Result
The project successfully demonstrates a complete Voice-to-Voice AI Assistant pipeline:
Speech → Text → AI Response → Speech
📁 Project Files
Voice_to_Voice_AI_Assistant.ipynb — Main Google Colab notebook containing the project code.
README.md — Project description, workflow, installation, and usage instructions.
👩‍💻 Development Environment
The project was developed and tested using Google Colab.
