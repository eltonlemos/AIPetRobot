# AIPetRobot
This was the code we wrote back in Engineering college for our final year project. As of the date of pushing this to Git it has been 2 years since we have seen the code, so some description may be lost to memory.

The Idea was to create a pet robot that had AI ML capabilites. We first used just a raspberry  pi but then we realised its weaknesses and used a an Arduino to do the heavy electronics work.

The raspbery pi is good for OpenCv but we soon realized that the frames were slow or would overload the Pi. so out architecture became a remote server doing all the heavy ml work, a raspberry pi doing all the on bot work and arduino doing mechanical work.

Following is the connection diagram

![Data connections](https://user-images.githubusercontent.com/61613837/160155450-33876a80-1a64-42f1-a62f-7efb6bfac962.png)


Following is the architecture diagram
![Architecture Block](https://user-images.githubusercontent.com/61613837/160155640-6d58a3ee-d64b-4f15-aa79-bcf811c5c516.png)


Note: you dont need a pi cam necessarily, you can use any Ip Camera
