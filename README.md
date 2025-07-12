# Python-Project-Text-to-Speech-AI-voice-Agent
Python Project Text to Speech AI voice Agent

import pyttsx3

# Initialize the text-to-speech engine
engine = pyttsx3.init()

# Set speech rate (speed) and volume (max volume)
engine.setProperty('rate', 150)
engine.setProperty('volume', 1.0)   # Max volume

# The new text you want to speak
text = """
Welcome to Madeeha programming language.
We are learning Python.
We are learning from Enablers.
Sir Ansar is our teacher.
And Madeeha Wali made a voice AI agent to speak their text to speech.
"""

# Print the text
print(text)

# Speak the text
engine.say(text)
engine.runAndWait()
