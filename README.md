# Medical Call Analysis Project Pilot

## Overview
This project processes doctor-patient audio recordings to produce **speaker-diarized transcriptions** and **summaries** using AI models. 

##WORKFLOW

Speaker Diarization

Input: Raw doctor-patient audio (.mp3)

Model: Pyannote Audio (pyannote/speaker-diarization-3.1)

Output: Speaker-labeled segments (timestamps and speaker IDs)

Speech-to-Text Transcription

Input: Speaker-labeled audio segments

Model: Whisper (OpenAI, base model)

Output: Text transcripts for each speaker

Summarization

Input: Full speaker-labeled transcript

Model: Llama-3.1 via Hugging Face API

Output: Concise summary of the doctor-patient conversation


The goal is to convert raw audio into structured, readable transcripts with speaker labels, and provide a concise summary of the conversation for easy analysis.

##HOW TO USE 

1. Clone the repository.
2. Create a virtual environment and activate it.
3. Install dependencies(requirements.txt).
4. Set your Hugging Face API token.



