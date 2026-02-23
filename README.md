# Arduino Based Radar System

A radar system built using Arduino that detects objects within a range and displays them on a graphical interface with angle and distance measurements.

## Overview

This project uses an ultrasonic sensor mounted on a servo motor to scan the surrounding area. The sensor rotates 180 degrees, detecting objects and measuring their distance. The data is sent to a computer where it's visualized as a radar display showing the angle and distance of detected objects.

## Components Required

- Arduino board (Uno/Nano/Mega)
- HC-SR04 Ultrasonic Sensor
- SG90 Servo Motor
- Jumper wires
- Breadboard
- USB cable for Arduino connection

## Circuit Connections

### Ultrasonic Sensor (HC-SR04)
- VCC → 5V
- GND → GND
- Trig → Digital Pin 10
- Echo → Digital Pin 11

### Servo Motor
- VCC (Red) → 5V
- GND (Brown) → GND
- Signal (Orange) → Digital Pin 12

## Features

- 180-degree scanning range
- Real-time distance measurement
- Visual radar display on computer
- Angle and distance indicators
- Object detection and tracking

## How It Works

1. The servo motor rotates the ultrasonic sensor from 0° to 180°
2. At each angle, the sensor measures the distance to any object in front
3. Data is sent via serial communication to the computer
4. Processing software displays the information as a radar screen
5. Detected objects appear as bright spots on the radar display

## Installation

1. Clone this repository
2. Upload the Arduino sketch to your Arduino board
3. Install Processing IDE for the visualization
4. Run the Processing sketch
5. Select the correct COM port

## Usage

1. Connect the Arduino to your computer via USB
2. Open the Processing application
3. The radar will start scanning automatically
4. Objects within range will appear on the radar display

## Applications

- Obstacle detection for robotics
- Security systems
- Distance measurement projects
- Educational demonstrations
- DIY automation projects

## Project Files

- `arduino_code.ino` - Arduino code for the radar system
- `PROJECT_DOCUMENTATION.md` - Detailed project documentation
- `CIRCUIT_DIAGRAM.md` - Circuit connections and specifications
- `SETUP_GUIDE.md` - Step-by-step setup instructions
- `BOM.md` - Bill of materials with cost estimates
- `GITHUB_UPLOAD_GUIDE.md` - Guide for uploading to GitHub

## Student Information

- **Department**: Electronics and Telecommunication Engineering (ENTC)
- **Project Type**: Mini Arduino Project

## License

This project is open source and available under the MIT License.

## Contributing

Feel free to fork this project and submit pull requests for any improvements.

## Acknowledgments

Built with Arduino and Processing for educational and hobbyist purposes.
