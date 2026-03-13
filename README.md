# Voice Assistant (Python)

This project is a simple voice assistant built using Python.
It uses text-to-speech to speak messages to the user.

## Features

* Speaks a greeting message
* Introduces itself as a voice assistant
* Uses text-to-speech technology

## Technologies Used

* Python
* pyttsx3 (Text to Speech library)

## Code

```python
import pyttsx3

engine = pyttsx3.init()

engine.say("Hello Reena, I am your voice assistant")
engine.say("How can I help you today")

engine.runAndWait()
```

## How to Run the Program

1. Install Python on your computer.
2. Install the required library:

```
pip install pyttsx3
```

3. Run the Python file:

```
python Voice_Assistant.py
```

## Example Output

The program will speak:

Hello Reena, I am your voice assistant
How can I help you today

## Project Purpose

This project demonstrates how Python can be used to convert text into speech and build a basic voice assistant.
.
