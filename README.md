# 🔋 BatteryBar – ESP32 LED Charging Indicator

Simulates a 5-LED battery charging animation using an ESP32 and basic LEDs.

## 📹 Demo Video

[🎬 Watch on YouTube](https://youtu.be/O3AxyqJpUgo)

---

## 🔌 GPIO Pin Mapping

| LED Color | GPIO Pin | ESP32 Label | Resistor | Notes                    |
|-----------|----------|-------------|----------|--------------------------|
| Red       | GPIO 2   | G2          | 220Ω     | Anode (+) to GPIO pin    |
| Yellow    | GPIO 4   | G4          | 220Ω     |                          |
| Green     | GPIO 5   | G5          | 220Ω     |                          |
| Blue      | GPIO 15  | G15         | 220Ω     |                          |
| White     | GPIO 18  | G18         | 220Ω     | Indicator / blink LED    |

---

## 🛠️ Setup Instructions

1. Insert 5 LEDs into the breadboard.  
2. Connect a **220Ω resistor** from each ESP32 GPIO pin to the **anode (+)** leg of the LED.  
3. Connect all LED **cathodes (–)** together to the **GND rail** on the breadboard.  
4. Connect the breadboard **GND rail** to an ESP32 **GND pin**.  
5. Connect the ESP32 to your computer via USB and upload the `BatteryBar.ino` sketch using Arduino IDE.  
6. Watch the LEDs light up one by one, simulating battery charging.

---

## 📁 Files Included

- `BatteryBar.ino` — Main charging indicator Arduino sketch  
- `.gitignore`, `LICENSE`, `README.md`

---

## 📃 License

MIT License — free to use, modify, and share.

---
