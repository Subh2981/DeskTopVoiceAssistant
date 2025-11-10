🗣️ Desktop Voice Assistant using Python
📘 Project Overview

This is a Desktop Voice Assistant built using Python that can listen to user commands, process voice inputs, and perform actions like:

Searching the web

Opening applications

Telling the current time and date

Sending emails

Playing music or YouTube videos

Giving weather updates

It uses speech recognition and text-to-speech (TTS) technologies to interact with the user — similar to Alexa, Google Assistant, or Siri but simplified for desktop use.

⚙️ Tech Stack & Libraries
Function	Library Used

Voice Input	speech_recognition

Text-to-Speech	pyttsx3

Web Access	webbrowser, requests

System Control	os, datetime, subprocess

Optional Add-ons	wikipedia, pywhatkit

🚀 Features

✅ Responds to your voice commands

✅ Speaks back using a natural voice

✅ Opens websites and desktop apps

✅ Plays YouTube videos and songs

✅ Gives time and date updates

✅ Searches information on Wikipedia

✅ Can be extended with custom commands

🧠 How It Works

The assistant listens for your command using the microphone.

The speech_recognition library converts speech into text.

The command is processed, and actions are triggered accordingly.

The assistant speaks the response using the pyttsx3 text-to-speech engine.

🖥️ Demo Commands

Try saying:

“Hello”

“What’s the time?”

“Open YouTube”

“Search Python on Google”

“Play music on YouTube”

“Tell me about Elon Musk”

📦 Installation Steps

Clone this repository

git clone https://github.com/your-username/desktop-voice-assistant.git
cd desktop-voice-assistant


Install dependencies

pip install speechrecognition pyttsx3 pywhatkit wikipedia requests


(Optional) Install PyAudio for microphone access

pip install pyaudio


If PyAudio fails, use:

pip install pipwin
pipwin install pyaudio


Run the program
 Run.py

🧑‍💻 Future Improvements

Add GUI using Tkinter or PyQt

Integrate with OpenAI API for smarter answers

Add reminders and alarms

Connect to IoT or smart devices

🏆 What This Project Demonstrates

✅ Python scripting & automation

✅ API integration and speech recognition

✅ Practical use of voice-based AI interaction

✅ Modular and expandable code design
