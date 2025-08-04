# -IoT-Air-Quality-Monitor

COMPANY: CODTECH IT SOLUTION

NAME: SANJAY KUMAR M

INTERN ID: CT04DH1577

DOMAIN:Internet Of Things

DURATION:4 WEEKS

MENTOR:Neela Santhosh

DESCRIPTION:

Objective: Build a basic IoT system that monitors environmental parameters like air quality (gas level) and temperature/humidity, and displays the readings via Serial Monitor.

We’ll simulate this using:

MQ135 Gas Sensor → air quality (CO2 level)

DHT22 Sensor → temperature & humidity

Arduino UNO

Wokwi Serial Monitor to display values



---

🛠️ Step-by-Step Instructions (Wokwi)


---

✅ Step 1: Open Wokwi Simulator

Go to https://wokwi.com

Click “New Project”

Select Arduino UNO



---

✅ Step 2: Add Components

Click the pink “+” button, and add:

1 x Arduino UNO

1 x DHT22 Sensor (or DHT11 if you prefer)

1 x MQ135 Gas Sensor

Jumper Wires



---

✅ Step 3: Wiring Connections

🔵 DHT22 Sensor:

DHT22 Pin	Connects To

VCC	5V
GND	GND
DATA	Arduino Pin 2


🔴 MQ135 Gas Sensor:

MQ135 Pin	Connects To

VCC	5V
GND	GND
AO	Arduino Pin A0

#OUTPUT:
<img width="1919" height="914" alt="Image" src="https://github.com/user-attachments/assets/1052c8ff-c950-4e0a-8abd-12002c12afab" />
<img width="1919" height="910" alt="Image" src="https://github.com/user-attachments/assets/b2c6b4f9-ee23-451c-b2bc-92dbb87e7b71" />


---

✅ Step 4: Install DHT Library

Before writing the code, Wokwi already supports the DHT library — so no need to install anything manually.
