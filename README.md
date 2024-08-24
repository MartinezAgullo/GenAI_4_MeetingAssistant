# Meeting Assistant

Generative AI-powered business meeting assistant.
AI app to transcribe and summarise discussions.

- [Open AI whishper](https://openai.com/index/whisper/): For speach to text conversion

- [Llama2 LLM:](https://llama.meta.com/llama2/) Summarise and extract key points

- [Gradio](https://www.gradio.app/): For user's friendly interface

![AudioTranscriptionApp](https://github.com/MartinezAgullo/GenAI_4_MeetingAssistant/blob/main/Tests/webApp_og.png)


# Installation
Installing required libraries:
> pip install transformers==4.35.2 torch==2.1.1 gradio==4.17.0 langchain==0.0.343 ibm_watson_machine_learning==1.0.335 huggingface-hub==0.19.4


To install OpenAI Whisper:
> brew install ffmpeg
> pip install git+https://github.com/openai/whisper.git


# Running code
## Transcription simple version
execute:
> python3.9 speech_to_text_simple.py
output:
'''
Hello, I want to speak fast because I want to test four speech-to-text applications. Today, whether it's sunny, with a slight breeze, making it perfect for outdoor activity, later I plan for a busy local part, maybe even a picnic. The test is designed to assess the accuracy and responsiveness of the speech-to-text feature. Thank you for participating in this test.
'''

## Transcription web app
>  python3.9 speech_to_text.app.py

## Simple LLM
> python3.9 LLM_simple.py 
output:
'''
Reading is one of the most efficient ways to gain knowledge and expand your mind. However, not all reading is created equal. Here are some tips to help you read a book effectively:

1. Set goals: Before you start reading, set specific goals for what you want to achieve. Do you want to learn a new skill or gain a deeper understanding of a particular subject? Having clear goals in mind will help you stay focused and motivated throughout the reading process.

[....]

10. Seek out additional resources: Don't be afraid to seek out additional resources to supplement your reading. This could include watching videos, listening to podcasts, or joining online communities related to the subject matter.

By following these tips, you can read a book effectively and get the most out of your reading time. Remember, reading is a lifelong learning process, and the more you practice, the better you'll become at it.
'''