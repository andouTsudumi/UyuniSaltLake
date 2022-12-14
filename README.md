# UyuniSaltLake

This data is confirmed to be activated only in oculusquest2.
Also, when debugging with VR goggles, please do the following (As of December 13, 2022).

## Procedure
### 1 Download the Meta Quest app.

### 2 Detect the Meta Quest device you are using.

### 3 Enable developer mode from the device in the Meta Quest app.

It is also recommended to install android studio when necessary.
android studio file paths with special character codes (e.g. Japanese) may cause errors when launched in Unity.

### 4 Create a new 3D project in Unity Hub.
Version 2019 or later is recommended. We have confirmed that it works here with 2019.4.16f1 and 2021.3.10f1.
Also, please include Android Build Support (both OpenJDK and Android SDK & NDK Tools) as a module for that version.

### 5 Overwrite this github file with your new project file and save it.
There is a very large file, so this will take some time.

### 6 Open File on the menu bar and open Build Settings.
Change Texture Compression in Build Settings to ASTC.Connect Meta Quest2 to the PC and allow Meta Quest2 to connect to the PC. Then press the Refresh button under Run Device in the Build Settings, select Oculus Quest2 from the Default device, and press the Build and Run button.
