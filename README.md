Tested on Chromium and Firefox browsers

# mediaLab5

This lab aims to build video streaming app based on WebRTC framework.

Some good examples:
https://www.scaledrone.com/blog/webrtc-tutorial-simple-video-chat/

# Requirements for repository
  - You have to clone this repository and make two branches (master and develop).
  - The develop branch should contain commits of every new feature of the AR application.
  - When all features will be ready you have to merge the development branch to the master.

# Requirements for streaming application
There are two options to choose from. 

Option A:
  - Capture images from camera by using WebRTC API. Basic code for chat application is provided.
  - By using RTCPeerConnection send images from camera to the client and display them.
  - You can use base64 to encode image to string and decode on client side.
  
Option B:
  - Find out how WebRTC API is designed.
  - Create client and server pages.
  - Server page should capture video from browser.
  - Client page should display stream. 
  
  
The general requirements for option A & B.
  - Test application on at least two browsers and specify in README.md which version and browser it was.
  - To pass this lab, you have to fully complete an option.  
