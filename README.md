# Audio Transcription and Question Answering

This application allows you to transcribe audio recordings and generate answers to questions based on the transcription using OpenAI's GPT-3.5 Turbo model. It also provides an option to download the results as a CSV file.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Tai-O/Call-Analysis-Question-Answering.git

2. Get Open AI API KEY
- Create an account on https://platform.openai.com/api-keys and get an API KEY (Needed to access GPT 3.5 turbo model)
- Open command prompt (Windows)
- ```bash
    setx OPENAI_API_KEY "your-api-key-here"
    ```


## Usage
- ```bash
    streamlit run app.py
    ```
- Upload a recording of a call in MP3 format.
- Upload a CSV file containing the questions related to the call.
- View the transcription of the audio and the corresponding questions.
- Generate answers to the questions based on the transcription.
- Download the results as a CSV file.
