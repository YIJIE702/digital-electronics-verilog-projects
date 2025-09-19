# Digital Electronics Mini Project – Home Alarm System (Verilog)

## 📌 Introduction
The purpose of this project is to design and simulate a **Home Alarm System** using Verilog HDL.  
The system provides **24/7 monitoring** for houses, ensuring security by detecting suspicious movements and triggering an alarm until it is disarmed by the correct password.  

This project highlights the integration of **digital logic design**, **sensor simulation**, and **password-protected security mechanisms**.

---

## 🎯 Objectives
- Develop a password-protected home alarm system.  
- Use Verilog HDL to model and simulate real-world security mechanisms.  
- Provide a low-cost, efficient, and reliable digital design solution.  
- Improve understanding of hardware description languages (HDLs) through practical implementation.  

---

## 🛠️ System Overview
The system is implemented in **Verilog HDL** and simulates key components of a home alarm:

- **Inputs & Controls**:  
  - **Keypad** → Password entry (`1234` by default)  
  - **Switch** → Power ON/OFF  
  - **PIR Sensor** → Detects human movement  

- **Outputs**:  
  - **3 × Seven-segment displays** → Show "OFF" or "ON" status  
  - **Green LED** → Indicates secure state  
  - **Red LED** → Blinks during intrusion  
  - **Buzzer** → Sounds when unauthorized activity is detected  

---

## ⚙️ Methodology
1. **System Activation**:  
   - Switch turned ON → system initializes.  
   - User enters password on keypad (`1234`).  

2. **Password Verification**:  
   - If correct → PIR sensor activated.  
   - If incorrect → system stays locked.  

3. **Normal Operation**:  
   - No human detected → Display = "OFF", Green LED ON, Buzzer OFF.  
   - Human detected → Display = "ON", Red LED blinks, Buzzer sounds.  

4. **Disarming the System**:  
   - User must re-enter correct password.  
   - Wrong password → Alarm continues until correct input is provided.  

---

## ✅ Conclusion
- Successfully designed and simulated a **Home Alarm System** using Verilog HDL.  
- Demonstrated secure access with **password protection** and **PIR-based intrusion detection**.  
- Showcased practical use of LEDs, buzzer, and seven-segment displays for real-time feedback.  
- Provides a foundation for further **enhancements in IoT-based home security systems**.  

---

## 🚀 How to Run
1. Download the zip file.
2. Extract & open it in a Verilog simulation tool (e.g., Quartus**).  
3. Compile and run the project.
4. Observe:  
   - "OFF" or "ON" on seven-segment displays.  
   - LED status changes.  
   - Buzzer activation upon intrusion.  

---

## 📜 License

These projects are for educational purposes under Digital Electronics I and II coursework.
You may modify and use this project for learning, but proper credit to the author is appreciated.
---

## 🙌 Acknowledgements
- Developed as part of **Digital Electronics course project**.  
- Thanks to instructors and teammates for valuable feedback and collaboration.  
