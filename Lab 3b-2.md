For this lab, we were tasked to setup an additional server on Ubuntu.
Therefore, I have choosen Docker as my additional server.

<img width="1280" height="800" alt="Lab 3b-2 update and upgrade" src="https://github.com/user-attachments/assets/09aa1c3c-ee55-495f-8bf2-b7fe523b9e03" />
<img width="1280" height="800" alt="Lab 3b-2 System Prep" src="https://github.com/user-attachments/assets/3bb12a1f-cdbd-4fc1-8539-129d51e8c166" />

Before installing Docker, I check whether there is updates to the system and download the basic prerequisites. Then reboot the system.

<img width="1280" height="800" alt="Lab 3b-2 additional service 1" src="https://github.com/user-attachments/assets/c48f6156-6cd5-4a6e-8f00-75ef641b21a6" />

The first step is to remove the old Docker versions. However, it's my first time doing this so there was no older versions to remove.
The second step is to install Docker using Ubuntu repository. As shown in the picture the installation was successful.

<img width="1280" height="800" alt="Lab 3b-2 additional service 2" src="https://github.com/user-attachments/assets/567567bf-211b-44af-9b47-30cde9447eb8" />

The third step I start and enable Docker using "sudo systemctl start docker" & "sudo systemctl enable docker".
The last step to ensure Docker is running and installed properly, I check the version installed and run hello world to show that Docker is working. The image above shows the hello message from Docker.
