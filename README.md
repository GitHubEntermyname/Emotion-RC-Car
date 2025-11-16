# 🚗 Emotion RC Car

### 📌 Overview
The **Emotion RC Car** is a Bluetooth-controlled robotic vehicle that combines mobility with expressive feedback using an 8x8 LED matrix.  
It features directional movement, servo-controlled gestures, and visual emotional cues like smile and anger — making it both functional and interactive.

### ⚙️ Features
- Forward, reverse, left, right, and stop commands via serial Bluetooth
- Servo motor for gesture control (0° to 180°)
- 8x8 LED matrix displays directional arrows and emotional icons
- Real-time command feedback via serial monitor

### 🛠️ Components
- Arduino UNO  
- L293D Motor Driver  
- DC Motors + Wheels  
- Servo Motor  
- HC-05 Bluetooth Module  
- 8x8 LED Dot Matrix Display  
- Jumper wires  
- 9–12V Battery

### 📂 Files
- `src/Emotion_RC_Car.ino` → Arduino sketch  
- `images/` → Project photos and build documentation  
- `.gitignore` → ignored files configuration  
- `.gitattributes` → repository attributes  
- `README.md` → project documentation  

### 🚀 How It Works
- The car receives serial commands via Bluetooth (e.g., 'F' for forward, 'L' for left).
- The LED matrix displays directional arrows or emotional icons based on the command.
- The servo motor adjusts its angle to simulate gestures.
- All motor and display logic is handled in the Arduino sketch.

### 📸 Project Images
*(Add your uploaded image references here once placed in `/images/`)*  
```markdown
![Emotion RC Car](images/RC-Mobile-Lifter.jpg)
