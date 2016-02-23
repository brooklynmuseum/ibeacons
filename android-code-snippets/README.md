# Android Code Snippets 

### Owner
Brooklyn Museum Android App

### Developers
Daniel Albert <br>
Chris Wilson

### Purpose
This application allows a user to chat with Brooklyn Museum operators.  When sending messages, the location of the most closely approximated beacon information will be sent to allow the museum operators to understand the location of the user, and to more quicly respond to their inquiries.

### Technologies
Android Framework
Java
Android Studio

### Install
In Android Studio, select File -> Project From Version Control -> GitHub <br>
Sign in to GitHub from Dialog <br>
Paste in the Git Repository URL - https://github.com/HappyFunCorp/bkmuseum-ask-android <br>
Clik Clone

### Running App in Development Setting
Select Build Variant stagingDebug <br>
Select Run -> Debug App <br>
Note - It is recommended that you run this on a device rather than an emulator

### Building APK
From command line - Run 'gradle assembleStagingDebug' for staging <br>
From Android Studio - Run Build -> Build APK option <br>
The file is stored at: `<project root folder>\app\build\outputs\apk
