# OpensourceLLMprojects
This repository contains the all the projects that I have done and learnings that I have received in the journey of learning about LARGE LANGUAGE MODELS

Project 1 :

Description:
The project is an AI-powered and LLM powered audio to text generator. The model needs to be fed upon an audio file and depending upon the size of the file it can generate the text or the points in the audio file.

Tech-Stack:

Audio model -- Openai-WhisperR1
Text model -- Gemini-2.0-Flash
Tokenization model -- Tallonai

Libraries -- Pytorch , BitsAndBytes , Transformers , SentencePiece , accelarate
Base Concept -- LLM inference 
As I was working on google colab free version I was unable to quantize a 7B parameters AI model but if it was a 3B or even a 4B model the quantization could be done upto 4bits 

Library for quantization is AutoModelForCausalLM()
