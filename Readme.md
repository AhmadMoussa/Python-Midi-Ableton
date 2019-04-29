# Python-Midi-Ableton

A tutorial on how to send midi signals from a python script to a midi track in ableton live

## What you'll need:
* Python (duh...), I am using (python 3.7.3)[https://www.python.org/downloads/]
* Pip install this package [pip install python-rtmidi](https://pypi.org/project/python-rtmidi/)
* Install this software: [loopMidi by Tobias Erichsen](http://www.tobias-erichsen.de/software/loopmidi.html)
* A DAW (short for Digital Audio Workstation), I am using Ableton live 10 Standard 10.0.6
* Windows?

## Why is this relevant:
* Because I couldn't find any resources on how to send Midi Notes from a Python script to Ableton
* You want to send Midi Signal from Python to Ableton Live on a Windows pc

## What are we actually going to do:
1. We can't communicate directly between ableton live and python
2. We need to create a virtual [port](https://en.wikipedia.org/wiki/Port_(computer_networking)) to which we can send midi signals from python and to which ableton will be "listening" to
3. We need to write a script that send midi signals, for that purpose we will use the [python-rtmidi](https://pypi.org/project/python-rtmidi/) package
4. We need to setup ableton to listen to the port

## What you'll have to do:
1. Install python and the python rt-midi package
![like this](https://imgur.com/a/n4bMiel)
* Install the loopMidi software, once you launch it
