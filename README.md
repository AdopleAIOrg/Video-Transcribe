# Video-Transcribe

This code transcribes audio files and segments them by speaker. It uses the Whisper library to transcribe audio, and the simple_diarizer library to segment audio by speaker.

# Install Requirements

    !pip install requirements
    
# Then, run the code:

    !streamlit run app.py & npx localtunnel --port 8501

The code will open a Streamlit app. In the app, you can upload an audio file and choose a Whisper model. The app will then transcribe the audio file and segment it by speaker. The transcript will be displayed in the app, and you can download it as a text file or a CSV file.

# Here are some additional details about the code:

1. The VideoTranscriber class contains the main logic for transcribing audio and segmenting it by speaker.

2. The video_submission function creates a Streamlit form for uploading an audio file and choosing a Whisper model.
   
3. The choose_model function transcribes the audio file and segments it by speaker, and then displays the transcript in the Streamlit app.

# contact

If you have any doubt about this github feel free and ask Email:ceo@adople.com
