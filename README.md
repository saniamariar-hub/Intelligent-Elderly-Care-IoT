# Intelligent Elderly Care and Fall Detection System

## Project Overview
This project implements an IoT-based elderly care system designed to monitor vital health parameters and detect fall events. The system is simulated using Tinkercad and follows the logic of a real-world wearable IoT solution.

The device continuously monitors body temperature and heart rate, displays the data on an LCD, and triggers an emergency alert when a fall is detected.

---

## Tinkercad Simulation Link
🔗 https://www.tinkercad.com/things/cUvBE64sOQS-elderly-care-fall-detection

---

## Components Used
- Arduino UNO  
- TMP36 Temperature Sensor  
- Potentiometer (Heart Rate Simulation)  
- Tilt Sensor (Fall Detection)  
- LCD 16×2 Display  
- LED and Resistor  
- Li-ion Batteries (for real-world use, not connected in simulation)

---

## System Working
- The **potentiometer** simulates heart rate values.
- The **TMP36 sensor** measures body temperature.
- The **LCD 16×2** displays heart rate and temperature in real time.
- The **tilt sensor** detects fall conditions.
- When a fall is detected:
  - The LCD displays a **FALL ALERT**
  - The LED turns ON
  - An emergency message is printed on the Serial Monitor
- The Serial Monitor output represents **cloud-based caregiver alerts** in a real IoT deployment.

---

## Simulation Note
Due to Tinkercad limitations, the system is powered using USB and cloud communication is simulated using the Serial Monitor. Li-ion batteries are intended for real-world wearable deployment.

---

## Tools Used
- Tinkercad (Web-based simulation)
- Arduino IDE logic (embedded in Tinkercad)

---

## Conclusion
This project demonstrates a simple, effective, and scalable approach to elderly health monitoring and fall detection using IoT concepts. The design can be extended to real hardware with Wi-Fi and cloud integration.

---

## Authors
Sania Maria Raju, Praveen V S, Rudraksh Mittal, Rakesh Solanki 
CSE – Applied IoT  
CIA 3 – Mid Term Project
