
   _____                  _     _____ _             
  / ____|                | |   / ____(_)            
 | (___  _ __   ___  __ _| | _| (___  _  __ _ _ __  
  \___ \| '_ \ / _ \/ _` | |/ /\___ \| |/ _` | '_ \ 
  ____) | |_) |  __/ (_| |   < ____) | | (_| | | | |
 |_____/| .__/ \___|\__,_|_|\_\_____/|_|\__, |_| |_|
        | |                              __/ |      
        |_|                             |___/       

===========================================================
SpeakSign, formerly speakNsign, version 2.0, Rewrite Stable Demo Release

Version released on 13/8/2023
===========================================================
About:
This is a windows application that translate a users speech into text, then sends it over a wireless network to a 'server'.
This application was created as part of the project by Tew Gun Rui, Logan Wong Duran, Darur Mithil for the module DV 2134 Junior Maker, AY 2023.

Github repository for this project: https://github.com/DevNerdGR/SpeakSign
==========================================================
Requirements:
Python 3 needs to be installed locally, along with with the PyAudio and SpeechRecognition libraries.
==========================================================
Setup guide:
Download the repository from GitHub, then unzip the downloaded file. After unzipping, navigate to directory ".../SpeakSign-main/SpeakSign-main/Debug". Look for "SpeakSignRewrite1.exe" and run it.

Before using the app, please ensure that Python 3 is installed locally, along with PyAudio and SpeechRecognition libraries.
To be able to use the speech to text feature, setup is required. Follow the steps below:    
    Configure Speech to Text Script:
        1. Click on "Configure script path...". A file selection dialog should pop up.
        2. Navigate to ".../SpeakSign-main/SpeakSign-main/Scripts" and look for the file STT.py.
        3. Select "STT.py" and then click "open" on the file selection dialog.
    
    Target URL config:
        1. Determine the ip address of the host/server.
        2. Type the IP of the host/server (without "http://", ONLY the IP) into the Target IP Address bar
        3. Press enter
    
    Notes and troubleshooting:
        1. The program is extremely sensistive to poor user inputs, and entering an invalid IP address could cause the program to crash
	2. If Python 3 is not installed, the program will also crash
	3. If disconnected from the network or if the host/server IP could not be located, the program will also crash
	4. For more information, please do contact the team through GitHub or physical means.
==========================================================
Usage:
1. Click once on the "Press and speak..." button and speak into the audio input device on your computer (e.g. microphone)
2. Your words will be sent over wireless network to the physical robotic hand, and it will sign out what you said accordingly in ASL.
==========================================================
Techincal specifications:
This app was built using Microsoft's .NET framework, and is written in C#.
The STT feature utilises the python libraries PyAudio and SpeechRegonition to provide STT capabilities.
==========================================================
Credits:
App designer/programmer: Tew Gun Rui
Robotic hand design/programming: Logan Wong Duran
ASL research & overall coordinator: Darur Mithil
==========================================================
Thank you for trying out our project!