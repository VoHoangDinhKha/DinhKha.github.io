# Smartdoor with ESP32-CAM FaceDetection and IFTTT for control device
  ## Description:
In this project, we are focusing on developing ESP32_Camera for the purpose of door opening through facial recognition and device control capabilities via Google Assistant (IFTTT) voice commands. We are using two separate ESP32s for two purposes, ESP32_CAM for facial recognition and door opening, and a regular ESP32 for device control
  
  1. The primary objective of ESP32_CAM is facial recognition and door opening, along with other tasks such as interacting with the chatbox tool on Telegram to execute functions like remote door opening and capturing images from the camera to enhance security and safety.
  
  2. The system allows users to use voice commands to execute requests through their phones with support from Google Assistant and IFTTT (Blynk database), thereby creating convenience in daily life. It enables remote device control without the need for extensive physical movement, and offers relatively fast response times.

In addition to the functions mentioned above, the system in our project still has some limitations that we will continue to modify and improve in the future: 
- When power is lost, the security system will not function.
- Without internet or Wi-Fi, remote device control is not possible, and device status updates may not be accurate.
- Modules are not yet properly linked together, meaning that successful activation of the facial recognition block to unlock does not necessarily trigger the voice-controlled block to operate.

## Demo

[![demo](https://github.com/user-attachments/assets/db8a6d5a-1235-4fa6-b20f-690629c4f124)](https://www.youtube.com/watch?v=dXrwPEIFxHo&t=113s)

### The remaining member of our team in developing this project, you can find him [here](https://github.com/TQ-Hung).
