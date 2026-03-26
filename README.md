🎥 3-Axis Self-Stabilizing Gimbal

This project focuses on building a **3-axis self-stabilizing gimbal** capable of keeping a camera or object stabilized regardless of user movement. Using an **MPU6050 (gyroscope + accelerometer)** and multiple **servo motors**, the system actively compensates for motion across all three axes (pitch, roll, and yaw) to maintain a steady orientation.

---

## ⚙️ Operating Modes

### 🟢 Automatic Mode
- Real-time stabilization using the MPU6050’s sensor readings  
- Continuous corrections to counteract unwanted motion  
- Smooth, accurate balancing across all axes  

### 🎮 Manual Mode
- User-controlled yaw adjustment via a potentiometer  
- Enables fine-tuning or creative movement when desired  

---

A dedicated **mode switch** toggles between automatic and manual control, while an **LED indicator** provides immediate feedback on system status and potentiometer activity.

---

## 🧠 What This Project Demonstrates
- Embedded systems integration  
- Sensor calibration and signal processing  
- Real-time control systems  
- Hardware-software co-design  

---

## 📸 Project Media

### 🔌 Hardware Setup
<img width="600" alt="hardware setup" src="https://github.com/user-attachments/assets/23930b80-9840-4824-b10d-521103c8d2ba" />

### 🧪 Breadboard + MPU6050 Wiring

![IMG_8431 2](https://github.com/user-attachments/assets/c7b1651d-cf20-4e96-88ad-ac86d623eaca)


### 📊 Live Gyroscope Data Output
<img width="1320" height="2352" alt="image" src="https://github.com/user-attachments/assets/92de2ccb-c06e-4875-9332-d0b36d60541e" />

---

## 🚀 Features
- 3-axis real-time stabilization  
- Dual-mode control system  
- Responsive servo-based correction  
- Expandable and modular design  

---

## 🛠️ Tech Stack
- Arduino (C/C++)  
- MPU6050 (I2C communication)  
- Servo motors (PWM control)  
- Potentiometer (analog input)  
