# Voice Assistant
AIY Project Experiments

# Summary
This project requires the AIY-voice-kit

https://aiyprojects.withgoogle.com/voice

# About the Project
The default assistant-demo program has been modified and following capabilities have been added:
added IP Address, sleep, reboot, volume up and volume down [see][1]


# Installation as a service
To run, my assistant as a service the my_assistant.service file needs to be copied in /lib/systemd/system folder and then the service needs to be enabled using the following command
```
sudo systemctl enable my_assistant
sudo service my_assistant start
```

The my_assistant.py needs to be symlinked to the AIY-projects-python folder
To do this change directory (cd;cd AIY-projects-python) to AIY-projects-python and issue the following command
```
ln -s <path to my_assistant.py> .
```


# References
[1]: https://ktinkerer.co.uk/list-mods-raspberry-pi-aiy-project/
