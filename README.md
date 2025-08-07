
# Anti-Sleep Alarm for Drivers Using Eye Blink Sensor 🚗💤🔔

## Project Overview

This project is a safety system designed to prevent drowsy driving accidents by monitoring a driver’s eye activity using an eye blink sensor. When signs of drowsiness are detected (such as prolonged eye closure), an alarm is triggered using a buzzer via a relay module.

## Hardware Components

- Arduino UNO/Nano
- Eye Blink Sensor
- Relay Module
- 5V Buzzer
- BO Motor & Wheel (for demo)
- 9V Battery
- Switch & MDF Board

## Software

- **Arduino IDE** using C/C++

## How It Works

1. The eye blink sensor detects eye closure and sends signals to Arduino.
2. If eyes are closed for more than 3 seconds, the system triggers a relay (e.g. turns on a light or warning).
3. If eyes remain closed for over 6 seconds, a buzzer is also triggered as a louder alarm.
4. The system resets once eyes are open again.

## Code

The code is available in this repository as [`anti_sleep_alarm.ino`](anti_sleep_alarm.ino).

## License

This project is for academic use and demonstration purposes.
