# NeuroGuardian - Smart Stroke & Seizure Detection System

## Summary
NeuroGuardian is a wearable health monitoring solution designed to detect early signs of neurological emergencies like seizures and strokes. It uses EMG and GSR sensors to monitor muscle activity and stress levels in real-time. If any abnormal pattern is detected, an alert is triggered and sent to the caregiver via SMS using a GSM module. The system can operate in both live and simulated environments, making it ideal for demos, prototyping, and clinical trials.

## TRL-8 Goals (Technology Readiness Level 8)
- Complete system integration with ESP32
- Real-time patient data capture (EMG + GSR)
- Automated alert system via GSM
- Fully functional breadboard prototype
- Demo-ready simulation for evaluation teams
- Ready for clinical validation/testing phase

## Setup Steps
1. Connect sensors to ESP32 as per pin_mapping.txt
2. Insert a micro SIM card into SIM800L GSM module
3. Power the system using USB or 5V battery
4. Upload firmware.ino using Arduino IDE
5. Open Serial Monitor (9600 baud) to view status
6. Watch for live EMG & GSR values and alerts
7. SMS sent to caregiver number on abnormal conditions

## Sensors Used
- EMG sensor (muscle activity)
- GSR sensor (sweat/conductance)
- GSM module (SIM800L)
- ESP32 microcontroller
