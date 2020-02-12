# ML_project
VISIVOICE- Voice for the dumb and spirit for the deaf

This Speech to Text engine utilises libraries like SpeechRecognition and pyAudio to convert either .wav files or real time audio to text format.

1.	The SpeechRecognition interface of the Web Speech API is the controller interface for the recognition service; this also handles the Speech Recognition Event sent from the recognition service. Library for performing speech recognition, with support for several engines and APIs, online and offline.

•	Speech recognition engine/API support:
•	CMU Sphinx (works offline)
•	Google Speech Recognition
•	Google Cloud Speech API
•	Wit.ai
•	Microsoft Bing Voice Recognition
•	Houndify API
•	IBM Speech to Text
•	Snowboy Hotword Detection (works offline)

We have used the Google Speech Recognition API for the project.

2.	PyAudio provides Python bindings for PortAudio, the cross-platform audio I/O library. With PyAudio, you can easily use Python to play and record audio on a variety of platforms, such as GNU/Linux, Microsoft Windows, and Apple Mac OS X / macOS./ 
	
We have used PyAuio Library from PyPi for preprocessing and processing of the audio into a favourable format (txt). We also use it to display the transcript of the library directly in the console.

3.	Our Text to Speech engine utilises libraries like OS, gTTS (Google Text to Speech) and IPython to either save the text into a music file or instantaneously play the file created.

	OS:

This module provides a portable way of using operating system dependent functionality.

	gTTS:

gTTS (Google Text-to-Speech), a Python library and CLI tool to interface with Google Translate’ s text-to-speech API. Write spoken mp3 data to a file, a file-like object (bytestring) for further audio manipulation, or stdout.

gTTS is one of the libraries included in the PyPi repository and consists of very easy to use tools for converting text to audio. The gTTS API supports several languages including English, Hindi, Tamil, French, German and many more. The speech can be delivered in any one of the two available audio speeds, fast or slow. 
