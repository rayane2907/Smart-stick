# Smart Stick for Blind People

## Overview
This project utilizes Arduino Uno to create a smart stick designed to assist blind individuals in navigating their surroundings more safely. The stick incorporates various sensors to detect obstacles and provide feedback through auditory signals, enhancing user awareness and mobility.

## Features
- **Ultrasonic Sensor:** Detects obstacles within a certain range and alerts the user through sound signals.
- **Vibration Motor:** Provides haptic feedback to the user based on proximity to obstacles.
- **Auditory Feedback:** Utilizes different tones or voice prompts to indicate obstacle distance and direction.
- **Arduino Uno Control:** Manages sensor inputs and controls the output signals for user feedback.
- **Portable and Lightweight:** Designed to be easily carried and used in various environments.

## Components Used
- Arduino Uno
- Ultrasonic Sensor (e.g., HC-SR04)
- Vibration Motor
- Buzzer or Speaker for Auditory Feedback
- Power Source (e.g., battery pack)

## Setup and Usage
1. **Assembly:**
   - Connect the ultrasonic sensor to Arduino Uno according to the circuit diagram.
   - Attach the vibration motor and buzzer/speaker to the Arduino for feedback.

2. **Upload Code:**
   - Upload the Arduino sketch provided (`smart_stick.ino`) to the Arduino Uno.

3. **Operation:**
   - Power on the Arduino using the designated power source.
   - The ultrasonic sensor detects obstacles; the vibration motor and buzzer/speaker provide feedback to the user.
   - Adjust settings or thresholds in the code as necessary for optimal performance.

## Future Improvements
- Integration with smartphone apps for additional functionality.
- Enhanced obstacle detection algorithms for more accurate feedback.
- Development of a more compact and ergonomic design for the stick.

## Credits
- Developed by [AMMAR KHODA Rayane, ZERROUKI EL Hachimi, ASSELAH Lamia]
