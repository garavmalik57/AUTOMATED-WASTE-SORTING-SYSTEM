# 🗑️ Automated Waste Sorting System

An embedded system project designed to automatically sort waste into categories using sensors and a servo-controlled dustbin. The system aims to reduce manual labor and improve the efficiency of waste management in smart cities.

## 🔧 Features

- Detects and classifies waste as **bio-waste**, **metal**, or **non-biodegradable**.
- Automatically rotates a dustbin to appropriate compartments using a servo motor.
- Uses multiple sensors for accurate detection and classification.

## 🛠️ Hardware Components

- 8051 Microcontroller (AT89C51)
- Moisture Sensor – detects bio-waste
- IR Sensor – detects presence of waste
- Metal Sensor – detects metallic waste
- Servo Motor – rotates dustbin by 120° for sorting
- Buzzer – feedback indicator
- Voltage Regulator – stable power supply


## 🧠 How It Works

1. **Detection**: Waste is detected using the IR sensor.
2. **Classification**:
   - If moisture is detected → Bio-waste
   - If metal is detected → Metal waste
   - Otherwise → Non-biodegradable waste
3. **Sorting**: Based on the detection result, the servo rotates the dustbin to the appropriate section.
4. **Reset**: After placing the waste, the servo returns to its default position.


This project is for educational and prototype purposes. Feel free to fork and improve it!



