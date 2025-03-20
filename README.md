# AIPetRobot

![68747470733a2f2f64726976652e676f6f676c652e636f6d2f75633f6578706f72743d766965772669643d316e3449304e4d4258324954374c70646d58673337662d7a306b4c78704d385445](https://github.com/user-attachments/assets/64593c8d-1356-4326-978b-ccc044dc5e61)

This was the code we wrote back in Engineering college for our final year project. As of the date of pushing this to Git it has been 2 years since we have seen the code, so some description may be lost to memory.

The Idea was to create a pet robot that had AI ML capabilites. We first used just a raspberry  pi but then we realised its weaknesses and used a an Arduino to do the heavy electronics work.

The raspbery pi is good for OpenCv but we soon realized that the frames were slow or would overload the Pi. so out architecture became a remote server doing all the heavy ml work, a raspberry pi doing all the on bot work and arduino doing mechanical work.


# Working

Following is the Connection Diagram

![Data connections](https://user-images.githubusercontent.com/61613837/160155450-33876a80-1a64-42f1-a62f-7efb6bfac962.png)


Following is the Architecture Diagram
![Architecture Block](https://user-images.githubusercontent.com/61613837/160155640-6d58a3ee-d64b-4f15-aa79-bcf811c5c516.png)

# Features
1) Detect and track a face (only the head of the bot)
2) Recognise a face
3) Understand emotions
4) Can follow a person wearing Fluorescent Yellow sneakers
5) Play stone paper sissors
6) Can play music and dance

# Note
You dont need a pi cam necessarily, you can use any Ip Camera

# Demos
You can view the full demo and explanation at https://www.youtube.com/watch?v=lxDzJWlctn4

Follow function

![follow](https://github.com/user-attachments/assets/c4754535-6586-4c56-a3d1-01d5d884b05d)

Follow function from the POV of the robot

![follow_bot_view](https://github.com/user-attachments/assets/805d121b-8805-428d-97ce-728398c869fa)

Face Tracking function

![face_track](https://github.com/user-attachments/assets/cdc06b3f-073b-4021-8c45-e50a70205c25)

# Hardware Used
1) Raspberry Pi 4
2) Remote server (any computer capable or running ML Algos)
3) Arduino boards and assorted modules
4) IP camera: can be a mobile phone cam or even a Pi cam

# Authors
* **Elton Lemos** - [eltonlemos](https://github.com/eltonlemos)
* **Abhishek Ghoshal** - [abhighosh98](https://github.com/abhighosh98)
* **Aditya Aspat** - Not on Git yet

