# Circuit Diagram and Connections

## Pin Configuration

### Arduino Connections

#### HC-SR04 Ultrasonic Sensor
```
HC-SR04          Arduino
--------         -------
VCC       →      5V
GND       →      GND
Trig      →      Pin 10
Echo      →      Pin 11
```

#### SG90 Servo Motor
```
Servo            Arduino
-----            -------
Red (VCC)   →    5V
Brown (GND) →    GND
Orange (Signal)→ Pin 12
```

## Circuit Diagram (Text Representation)

```
                    Arduino Uno
                   +-----------+
                   |           |
    HC-SR04        |  Digital  |        Servo Motor
   +-------+       |   Pins    |       +----------+
   |       |       |           |       |          |
   | VCC   |-------|  5V       |-------| Red      |
   | Trig  |-------|  10       |       |          |
   | Echo  |-------|  11       |       |          |
   | GND   |-------|  GND      |-------| Brown    |
   +-------+       |           |       |          |
                   |  12       |-------| Orange   |
                   |           |       +----------+
                   +-----------+
                        |
                        | USB Cable
                        |
                    Computer
```

## Component Specifications

### HC-SR04 Ultrasonic Sensor
- Operating Voltage: 5V DC
- Operating Current: 15mA
- Frequency: 40kHz
- Range: 2cm - 400cm
- Accuracy: ±3mm
- Measuring Angle: 15 degrees

### SG90 Servo Motor
- Operating Voltage: 4.8V - 6V
- Operating Current: 100mA (no load)
- Stall Current: 650mA
- Rotation: 180 degrees
- Speed: 0.1s/60° at 4.8V

### Arduino Uno
- Microcontroller: ATmega328P
- Operating Voltage: 5V
- Digital I/O Pins: 14
- PWM Pins: 6
- Flash Memory: 32KB

## Assembly Instructions

1. Place Arduino on breadboard or base
2. Mount servo motor securely
3. Attach ultrasonic sensor to servo horn
4. Connect wires as per pin configuration
5. Ensure stable power supply
6. Connect USB cable to computer

## Safety Notes
- Do not reverse polarity
- Ensure proper grounding
- Use appropriate power supply
- Check connections before powering on
