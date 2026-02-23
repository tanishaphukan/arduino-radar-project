# Complete Setup Guide for Beginners

## Step 1: Install Required Software

### Arduino IDE
1. Go to https://www.arduino.cc/en/software
2. Download Arduino IDE for your operating system
3. Install the software
4. Open Arduino IDE

### Processing IDE (for visualization)
1. Go to https://processing.org/download
2. Download Processing for your OS
3. Install and open Processing

## Step 2: Hardware Assembly

1. **Connect Ultrasonic Sensor to Arduino:**
   - VCC (sensor) → 5V (Arduino)
   - GND (sensor) → GND (Arduino)
   - Trig (sensor) → Pin 10 (Arduino)
   - Echo (sensor) → Pin 11 (Arduino)

2. **Connect Servo Motor to Arduino:**
   - Red wire → 5V (Arduino)
   - Brown wire → GND (Arduino)
   - Orange wire → Pin 12 (Arduino)

3. **Mount sensor on servo:**
   - Attach ultrasonic sensor to servo horn using tape or glue
   - Ensure sensor faces forward

## Step 3: Upload Arduino Code

1. Open Arduino IDE
2. Copy the code from `arduino_code.ino`
3. Connect Arduino to computer via USB cable
4. Select correct board: Tools → Board → Arduino Uno
5. Select correct port: Tools → Port → (select your Arduino port)
6. Click Upload button (→)
7. Wait for "Done uploading" message

## Step 4: Test the Setup

1. Open Serial Monitor (Tools → Serial Monitor)
2. Set baud rate to 9600
3. You should see angle and distance values
4. Move your hand in front of sensor to test

## Step 5: Run Visualization (Optional)

1. Open Processing IDE
2. Paste the Processing code (if you have it)
3. Click Run button
4. Select correct COM port
5. Radar display should appear

## Troubleshooting

### Arduino not detected
- Install CH340 drivers (for clone boards)
- Try different USB cable
- Check Device Manager (Windows)

### No sensor readings
- Check all connections
- Verify pin numbers in code
- Test sensor separately

### Servo not moving
- Check power supply (may need external 5V)
- Verify servo connection
- Test servo separately

## Tips for ENTC Students

1. **Document everything** - Take photos at each step
2. **Test components individually** before final assembly
3. **Keep a project diary** - Note problems and solutions
4. **Measure voltages** to verify connections
5. **Ask for help** if stuck for more than 30 minutes

## Common Mistakes to Avoid

- Reversing VCC and GND
- Wrong pin numbers in code
- Insufficient power supply
- Loose connections
- Wrong baud rate in Serial Monitor

## Next Steps

After successful setup:
1. Experiment with different distances
2. Try different scanning speeds
3. Add LED indicators
4. Create your own modifications
5. Document your improvements
