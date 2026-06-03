# CARDASHIANS: A Retro Arcade Car Game

A custom-built, retro-style arcade game featuring real-time obstacle avoidance, integrated audio, and interactive hardware controls. This project demonstrates end-to-end embedded system integration using limited resources to create an immersive, responsive gaming experience.

## 🛠 Technologies Used

### Hardware
* **Microcontroller:** Arduino UNO
* **Main Display:** TFT Capacitive Touch Display
* **Scoreboard:** LCD Module
* **Audio System:** MP3 Player Module + 1W, 8 Ohms Mini Speaker
* **Storage:** 2GB SD Card (for audio assets)
* **Inputs:** Joystick (Vehicle Control), Push Buttons (Start/Reset)

### Software
* **Language:** C++
* **Development Environment:** Arduino IDE

## 📋 Project Overview
CARDASHIANS was developed to challenge the limitations of an 8-bit microcontroller environment. The project required precise timing for game logic, concurrent management of two distinct display types, and serial-based audio playback. It serves as a practical demonstration of hardware-software integration, showcasing the ability to unify disparate modules into a cohesive, user-interactive system.

## 🚀 Key Features

* **Dual-Display Architecture:** Employs a TFT capacitive display for primary gameplay rendering while utilizing a dedicated LCD for clear, real-time tracking of scores and high-score data.
* **Immersive Audio Engine:** Integrated MP3 player module and dedicated speaker system deliver game-specific sound effects and ambient audio, managed via SD card storage.
* **Intuitive Control Interface:** Features a responsive analog joystick input for fluid vehicle navigation, complemented by hardware push buttons for seamless game state management (Start/Reset).
* **Embedded Logic Integration:** Built on the Arduino UNO to manage game state, collision detection, and concurrent hardware communication between the display, audio module, and input peripherals.

## 📸 Media Gallery

* **Demo Video:** [Insert link to video here]
* **Gameplay Capture:** [Insert image/GIF of gameplay here]
* **System Wiring Diagram:** [Insert image of your wiring setup here]

## 🔧 How to Run

1. **Clone the Repository:** `git clone [repository-link]`
2. **Hardware Assembly:** Connect components to the Arduino UNO according to the provided system wiring diagram.
3. **Setup Audio:** Ensure the 2GB SD card is formatted and populated with the necessary sound files for the MP3 module.
4. **Upload Code:** Open `CARDASHIANS.ino` in the Arduino IDE, select the correct board and port, and upload the sketch to your Arduino UNO.
5. **Initialize:** Press the "Start" button to begin the game loop.
