# 🌡️ Analog Temperature Sensor Project  
### **Andrew Cortez**

---

## 📘 Description
The **Keyestudio Analog Temperature Sensor (KS0033)** is a simple module that measures temperature and outputs an **analog voltage** that changes with temperature.  
When it is connected to an **Arduino**, the board can read this voltage on an analog pin and convert it into a temperature value that can be displayed or used to trigger other actions.

---

## ⚙️ Functions
The main function of the sensor is to **sense the surrounding temperature** and provide a signal that the Arduino can read.  

With this sensor and an Arduino, you can:
- Measure the **current temperature** of the environment.  
- Monitor **temperature changes over time**.  
- Use temperature readings to **control other devices**, like fans, LEDs, or buzzers (for example, when it gets too hot or too cold).

---

## 🔌 How It Works
The sensor uses a temperature‑sensitive component (a thermistor) whose resistance changes with temperature.  
The module converts this change in resistance into a changing **analog voltage**. 

The Arduino reads this voltage using one of its analog input pins (for example, **A0**), then uses a formula in the code to estimate the temperature (usually in degrees Celsius).  
By reading this value repeatedly, the Arduino can track how the temperature goes up or down.

---

## 🛠️ How to Use It

### 🧾 Components You’ll Need
- Arduino Uno
- Keyestudio Analog Temperature Sensor (KS0033)  
- Jumper wires

### 🔧 Circuit Connections
| KS0033 Pin | Connects To        |
|------------|--------------------|
| VCC        | 5V on Arduino      |
| GND        | GND on Arduino     |
| OUT        | A0 on Arduino      |

