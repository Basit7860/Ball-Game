# Unity Rolling Ball Game

Project Description
This is a mobile game built in Unity where a rolling ball is controlled using the device's accelerometer (tilt controls). The game includes a timer, camera follow mechanics, and user interface elements to display gameplay information.

Features
- Tilt Controls: Move the ball by tilting the phone.
- Camera Rotation: The camera can be dragged to rotate but is restricted from going underground The camera includes various controls such as rotation, pan, zoom, and adjustable offsets for X, Y, and Z axes. It is also restricted from going underground..
- User Interface (UI):
  - Timer display in the top-left corner.
  - Start message with gameplay instructions.
- Graphics & Icons:
  - Simple and optimized 3D models.
  - Custom UI icons and textures.
- Sound Controls:
  - Toggle sound ON/OFF with a single line of code.
- Quit Functionality:
  - Allows the user to exit the game properly.

Installation
1. Clone or Download the Project
   - Download the ZIP.
   - Open the project in Unity (version 2022+ recommended).

2. **Build & Run**
   - Go to File → Build Settings.
   - Select Android platform.
   - Click Build and Run** to generate an APK.

 Controls
- Tilt Device → Moves the ball.
- Drag on Screen → Rotates the camera.
- Tap UI Buttons → Controls sound and game functions.

 Folder Structure
```
📂 Unity Project Root
 ┣ 📂 Assets
 ┃ ┣ 📂 Scripts
 ┃ ┃ ┣ 📜 PlayerController.cs
 ┃ ┃ ┣ 📜 CameraRotate.cs
 ┃ ┣ 📂 UI
 ┃ ┃ ┣ 📜 GameOver.cs
 ┃ ┃ ┣ 📜 Timer.cs
 ┃ ┣ 📂 Graphics (Models & Textures)
 ┣ 📂 ProjectSettings
 ┣ 📂 Packages
```

Important Scripts
- PlayerController.cs → Handles movement using accelerometer.
- CameraRotate.cs → Allows manual camera rotation and Keeps the camera focused on the ball.
- Obstacle.cs → Keeps the obstacle moving.
- GameOver.cs → Handles game-over scenarios.
- Sound Managment.cs → Handles the sound.

APK & Project Files
- APK File: https://drive.google.com/file/d/1Y-SAiaM2FkbJMJ-T-ePAOUy2O5Ua_zVk/view?usp=drive_link
- Project Files:  https://drive.google.com/file/d/1G92IlYZzBiHNR3McE_9er2eBydeLsJ3N/view?usp=drive_link

License
This project is for educational and development purposes. Feel free to modify and improve it!

