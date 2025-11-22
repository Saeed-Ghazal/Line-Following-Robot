# Line-Following Robot

An autonomous robot designed to follow a pre-defined track using a QTR-8RC Reflectance Sensor Array. It can navigate straight paths as well as curves and turns without manual intervention.

---

## 📸 System Preview
<div style="display: flex; gap: 10px; justify-content: center; flex-wrap: wrap;">
  <img src="https://raw.githubusercontent.com/Saeed-Ghazal/Line-Following-Robot/05215ca4e89082b7eabbee537367cef461a11572/Line1.JPG" alt="Line Robot 1" style="width: 300px; height: auto;" />
  <img src="https://raw.githubusercontent.com/Saeed-Ghazal/Line-Following-Robot/05215ca4e89082b7eabbee537367cef461a11572/Line4.JPG" alt="Line Robot 2" style="width: 300px; height: auto;" />
</div>
 <img src="https://raw.githubusercontent.com/Saeed-Ghazal/Line-Following-Robot/05215ca4e89082b7eabbee537367cef461a11572/Screenshot%202025-05-20%20190623.png" alt="Line Robot 3" style="width: 500px; height: auto;" />






---

## 🚀 Features
- Fully autonomous line following  
- Navigates curves and turns  
- High-torque N20 motors for reliable movement  
- Adjustable speed via motor driver and power supply  

---

## 🔧 Hardware Components

| Component | Description |
|-----------|-------------|
| QTR-8RC Reflectance Sensor Array | Detects line (black/white contrast) for navigation |
| 2× N20 6V 200 RPM High Torque DC Motors | One motor per wheel for movement |
| XL4015 DC-DC 5A Adjustable Step-down Module | Regulates input voltage (4–38V) for electronics |
| LiPower Lipo Battery 2S 7.4V 550mAh | Powers motors and controller |
| G6 1P2T Toggle Switch | Power switch for the robot |
| FingerTech Mini-Sumo Wheels (Red, pair) | Wheels for movement |
| Pololu DRV8833 Dual Motor Driver | Controls left and right motors |
| ESP32 NodeMCU ESP-WROOM-32E | Main microcontroller for sensor reading and motor control |
| Imax-B6AC Charger | Charges the LiPo battery |

---

## 🛠️ How It Works
1. **Line Detection:** The QTR-8RC sensor array continuously reads the line's position.  
2. **Processing:** ESP32 calculates the deviation from the line center.  
3. **Motor Control:** The DRV8833 driver adjusts the speed of each motor to correct the path.  
4. **Navigation:** The robot autonomously follows the track, smoothly handling curves and turns without manual intervention.  

---

## 📱 Notes
- Fully autonomous; no manual mode.  
- Optimized for small tracks with curves.  
- Uses high-torque motors and reliable sensors for stable performance.  

---

