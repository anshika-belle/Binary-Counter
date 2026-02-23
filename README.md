## 🔢 Binary Counter using Arduino

This project demonstrates a **Binary Counter** using Arduino and LEDs.  
The LEDs represent binary numbers and count sequentially with a fixed delay.

---

## 🚀 Features
- Displays binary counting using LEDs  
- Beginner-friendly Arduino logic project  
- Helps understand digital electronics & binary system  

---

## 🧰 Components Required
- Arduino UNO  
- LEDs (4 or more depending on bits)  
- Resistors (220Ω)  
- Breadboard  
- Jumper wires  

---

## 🔌 Circuit Connections
Connect LEDs to Arduino digital pins through resistors.

Example (4-bit counter):

| LED | Arduino Pin |
|-----|------------|
| LED1 (LSB) | Pin 2 |
| LED2 | Pin 3 |
| LED3 | Pin 4 |
| LED4 (MSB) | Pin 5 |

*(Pins can be changed in code)*

---

## 💻 How it Works
- Arduino generates numbers from 0 → 15  
- Each number is converted to binary  
- LEDs turn ON/OFF according to binary value  
- Sequence repeats continuously  

---

## ▶️ How to Run
1. Connect LEDs with resistors  
2. Open `BINARYCOUNTER.ino` in Arduino IDE  
3. Select board & port  
4. Upload code  
5. Observe binary counting on LEDs  

---

## 📊 Example Counting# Binary-Counter
