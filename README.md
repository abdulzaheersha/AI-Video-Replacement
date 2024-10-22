AI-Video-Replacement
Project Overview
The AI-Video-Replacement project demonstrates how to automatically replace a video's original audio with AI-generated audio, using Azure AI services. The process includes transcribing the video's audio, correcting the transcription using GPT-4, and generating new audio based on the corrected text using Text-to-Speech.

Key Features
Speech-to-Text: Extracts and transcribes audio from video using Azure's Speech-to-Text service.
GPT-4 Correction: Corrects grammatical errors and refines the transcription using Azure's GPT-4 service.
Text-to-Speech: Converts the corrected transcription back into audio using Azure's Text-to-Speech service.
Audio Replacement: Replaces the original video's audio with the newly generated AI audio using MoviePy.
