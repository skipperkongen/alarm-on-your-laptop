# Alarm on your laptop

Use your laptop's built-in webcam an microphone as an alarm system. Honestly, it has only been tested on mac. In a separate repo I will remake a "suspicious behavior on video" machine learning example I saw at Spark + AI 2018 (stay tuned). 

## About

When you activate the laptop alarm, you computer begins to film through the webcam and listen through it's microphone.

It captures the following events:
- Sound detected
- Speech detected
- Motion detected
- Well-known face detected
- Unknown face detected

## Installation

```
pip install opencv-python
pip install face_recognition
```

## Research

Running Python in parallel:
https://stackoverflow.com/a/7207336

Libraries:
http://tutorial.simplecv.org/en/latest/

Capture webcam:
https://stackoverflow.com/questions/11094481/capturing-a-single-image-from-my-webcam-in-java-or-python

Face recognition:
https://github.com/ageitgey/face_recognition

Speech recognition:
https://realpython.com/python-speech-recognition/
