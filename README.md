**Jarvis AI Desktop Voice Assistant Python Project**

Jarvis is an interactive voice assistant built in Python that can perform tasks based on your voice commands. It uses pyttsx3 for speech synthesis and speech_recognition for understanding your voice. You can ask Jarvis to search Wikipedia, open websites, play music, tell the time, open applications, and even send emails.

Features:

⦁	Greets the user based on the time of day
⦁	Recognizes voice commands using your microphone
⦁	Search and summarize information from Wikipedia
⦁	Open websites like YouTube, Google, and StackOverflow
⦁	Play local music files
⦁	Tell the current time
⦁	Open applications installed on your system
⦁	Send emails through Gmail


Technologies Used:

1.	Backend:

⦁	Python 3.8+
⦁	pyttsx3 for text-to-speech
⦁	SpeechRecognition for voice input
⦁	Wikipedia API for fetching information
⦁	smtplib for sending emails

2. Optional:

Any code editor (VS Code, PyCharm) for opening apps


Installation and Setup:

1.	Prerequisites

⦁	Python 3.8 or higher
⦁	A working microphone
⦁	Gmail account for sending emails (less secure app access may be required)

2. Setup

⦁	Clone the repository:

git clone https://github.com/yourusername/jarvis-voice-assistant.git

⦁	Navigate to the project folder:

cd jarvis-voice-assistant

⦁	Install the required packages:

pip install pyttsx3 SpeechRecognition wikipedia

⦁	Update the script:

Add your Gmail credentials in sendEmail() function

Update local paths for music and applications

⦁	Run
python jarvis.py
