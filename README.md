# JarvisClipDat

This is a little side project I'm working on.
It is a screen clipper activated by a voice command, "Jarvis, clip that".

I tried to separate this project into smaller parts easier to achieve. Here they are:

- Voice Engine:

  The program will always be listening to the user's voice input, and when they say the command, it will execute the capturing.

  Mic Stream -> Word Detector -> Execute Event

- Capture:

  The program will capture the last 30 seconds (for now) of the screen and audio, from the moment it receives the command.

  Display Capture + Audio Capture + 30s
  
- Saving:

  Save an .mp4 file of the capture.

- UI Design:

  Create the UI and user interface.

---
## Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) + [Tauri](https://marketplace.visualstudio.com/items?itemName=tauri-apps.tauri-vscode) + [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)
