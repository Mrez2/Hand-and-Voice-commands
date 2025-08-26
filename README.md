# Hand & Voice Controlled Virtual Mouse  
<img width="1139" height="686" alt="Screenshot 2025-08-26 180640" src="https://github.com/user-attachments/assets/b107fe1d-cb04-442f-a739-76180fa66b91" />

A Python-based **virtual mouse** powered by **OpenCV**, **Mediapipe**, and **PyAutoGUI**.  
Control your computer using **hand gestures** and **voice commands**, enabling touch-free interaction and accessibility.  

---

## ✨ Features  
- 🖱️ **Mouse Control with Hand Gestures**  
  - Move cursor with index finger  
  - Left click (thumb + index)  
  - Double click (quick thumb + index)  
  - Right click (open palm)  
  - Zoom in/out (index + middle fingers pinch)  
  - Scroll up (ring finger up)  
  - Scroll down (pinky finger up)  

- 🎙️ **Voice Commands**  
  - `"left click"`, `"right click"`, `"double click"`  
  - `"scroll up"`, `"scroll down"`  
  - `"start typing"` → activates speech-to-text mode  
  - `"stop typing"` → deactivates speech-to-text mode  

- ⌨️ **Speech-to-Text Typing**  
  - Dictate text hands-free once typing mode is enabled  

---

## 📥 Clone the Repository  

Clone this project to your local machine with:  

```bash
git clone https://github.com/Mrez2/virtual-mouse.git
cd virtual-mouse
🛠️ Requirements
Install dependencies with:

bash
Copy
Edit
pip install opencv-python mediapipe pyautogui SpeechRecognition
You also need:

pyaudio (for microphone input):

bash
Copy
Edit
pip install pyaudio
▶️ Usage
Run the script:

bash
Copy
Edit
python main.py
Show your hand in front of the webcam.

Use gestures to move/click/scroll/zoom.

Use voice commands for extra control.

Press q to quit.

📌 Notes
Works best in good lighting.

Keep your hand visible to the webcam.

Typing mode requires an active text field (e.g., Notepad, browser).

