# Three-Factor Security Door

## Overview

The Three-Factor Security Door is an advanced IoT-based security system designed to enhance the safety of residential or commercial premises. It integrates three layers of authentication—RFID, password, and fingerprint scanning—to ensure only authorized individuals can access the secured area.

## Features

- **Three-Layer Authentication:** Utilizes RFID tags, password input, and fingerprint scanning for multi-level security.
- **Real-Time Monitoring:** Provides notifications and logs access attempts for comprehensive security oversight.
- **Failsafe Mechanism:** Automatically locks the system and triggers an alarm after repeated failed access attempts.
- **Integrated IoT Components:** Employs Arduino, RFID module, keypad, and fingerprint sensor for seamless operation.

## Components

- **Microcontroller:** Arduino Uno or similar
- **RFID Module:** For RFID tag detection
- **Keypad Module:** For password input
- **Fingerprint Sensor:** For biometric authentication
- **Buzzer and LED Indicators:** For alert and status indication

## Installation

1. **Hardware Setup:**
   - Connect the RFID module, keypad, and fingerprint sensor to the Arduino according to the pin configuration in the project documentation.
   - Connect the buzzer and LED indicators for alerts and status display.

2. **Software Setup:**
   - Clone the repository to your local machine:
     ```bash
     git clone https://github.com/your-username/Three-Factor-Security-Door.git
     ```
   - Open the Arduino IDE and load the project code.
   - Upload the code to the Arduino.

## Usage

1. Present an RFID tag to the reader.
2. Enter the correct password using the keypad.
3. Scan your fingerprint using the fingerprint sensor.
4. If all authentication steps are successful, the door will unlock.




