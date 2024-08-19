
# handMotionRacer

Welcome to the MotionRacer This endless runner-style game features a dynamic car racing experience where you navigate through a highway filled with obstacles and collect power-ups.

## Overview
In this game, you control a car that drives on a three-lane highway. The goal is to avoid obstacles, collect power-ups, and achieve the highest score possible. The game speed increases over time, making it more challenging as you progress.

 ## Features
- Endless Racing: Enjoy a continuous racing experience with gradually increasing difficulty.
- Dynamic Obstacles: Encounter a variety of obstacles on the road that you need to avoid.
- Power-Ups: Collect power-ups to gain temporary advantages like shields and speed boosts.
- Scoring System: Earn points based on distance traveled and obstacles avoided.
- Leaderboards: Compete with other players and share your high scores.
## Gameplay
- Controls: Use touch controls to switch lanes and maneuver your car and gestures as well 
- Objective: Avoid obstacles, collect power-ups, and survive as long as possible to achieve a high score.














## Authors

- [@Someone-tensai](https://www.github.com/Someone-tensai)
  [![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=black)](https://www.linkedin.com/in/sulav-paudel-5308a6305/) 
   [![instagram](https://img.shields.io/badge/instagram-0A66C2?style=for-the-badge&logo=instagram&logoColor=black)](https://www.instagram.com/paudelsulav1/)

- [@mythrhyth](https://www.github.com/mythrhyth)
  [![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=black)](https://www.linkedin.com/in/rhythm-bhetwal-957a7826a/)
    [![instagram](https://img.shields.io/badge/instagram-0A66C2?style=for-the-badge&logo=instagram&logoColor=black)](https://www.instagram.com/_rhythm_.exe/)

- [@_sushil_bhatta](https://www.github.com)
  [![instagram](https://img.shields.io/badge/instagram-0A66C2?style=for-the-badge&logo=instagram&logoColor=black)](https://www.instagram.com/_sushil_bhatta/)


## Installation Instructions
Follow these steps to set up and run the MotionRacer on your local machine:

 ### Prerequisites
- C++ Compiler: Ensure you have a C++ compiler installed (e.g., GCC or Clang).
- CMake: Required for building the project. Install it from CMake’s website.
- SFML: The Simple and Fast Multimedia Library (SFML) is used for graphics, window management, and input handling.
- Mediapipe: Required for handtracking and gesture recognition. 
### Installing SFML
 #### On Windows
1. Download SFML:
- Visit the SFML download page and download the SFML SDK for Windows.

2. Extract the SDK:

3. Extract the downloaded file to a directory of your choice (e.g., C:\SFML).
- Set Up SFML in Your Development Environment:

 #### On macOS
 Install SFML via Homebrew:
```
brew install sfml
```
#### On Linux
Install SFML via apt :
```
sudo apt-get install libsfml-dev
```
### Installing Mediapipe
### Installing MediaPipe via pip
The easiest way to install MediaPipe is through pip:
```
pip install mediapipe
```
### Installing from Source (Optional)
If you want to customize or contribute to MediaPipe, you can build and install it from source:

```
git clone https://github.com/google/mediapipe.git
cd mediapipe
```

## Install Dependencies:
Make sure you have the following dependencies installed:

### OpenCV: Required to need to work with images and video streams:

```
pip install opencv-python

```

This will build a sample project to verify your installation.

Before running make sure to use your ipaddress in hand_tracking_server.py file and Car.cpp file (intializeSocket() function)
To view your IP Adress in local machine:
## Methods to View IP Address
1. Viewing Internal (Local) IP Address
## For Windows:
Open the Command Prompt:

Press Win + R, type cmd, and hit Enter.
Run the following command:

```
ipconfig

```
Look for the IPv4 Address under your active network connection. This is your local IP address.

## For macOS/Linux:
Open the Terminal:

For macOS: Press Command + Space, type Terminal, and hit Enter.
For Linux: Open the Terminal from your system menu.
Run the following command:

```
ifconfig

```
or

```
ip addr show

```
Look for the inet field under your active network interface (usually eth0, wlan0, or en0). The address shown is your local IP.

## Note:
 Before running the cpp Project. You have to run the hand_tracking_server.py file on your command prompt for establishing connection. You may even have to change your port number in rare cases.

## Clone the Repository
Clone the Repository:
```
git clone https://github.com/mythrhyth/handMotionRacer.git
cd handMotionRacer
```

# Troubleshooting
If you encounter errors related to SFML:

Ensure SFML is correctly installed and the environment variables are set up properly.
Check the SFML documentation or community forums for help with specific issues.
If the build fails:

Make sure you have all necessary development tools and libraries installed.
Review any error messages for missing dependencies or misconfigurations.
Additional Notes
Configuration Files: Ensure that any configuration files or assets required by the game are present in the assets/ directory or as specified in the source code.
Dependencies: The game depends on SFML, so ensure it's properly linked during the build process.
## Support

For support, email info@abhishekpanthee.com.np  rhythmbhetwal77@gmail.com paudelsulav5@gmail.com bhattasushil763@gmail.com


## Badges


[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)


