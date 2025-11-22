# BioFuel-Gas
AN IOT SOLUTION FOR DETECTING HARMFUL BIOFUEL GASES INSIDE GAS CHAMBERS

 🔬 Real-time monitoring of methane & toxic gases in a biofuel chamber

---
 📘 **Project Description**

This project ensures **safety in biofuel generation** by continuously monitoring hazardous gases like **Methane (CH₄)**, **Carbon Monoxide (CO)**, and **Air Quality (CO₂ / VOCs)** using **MQ-4, MQ-7, and MQ-135** gas sensors.
The system detects harmful concentrations in real-time and alerts the user using an **LCD display** and **buzzer**.

The goal is to make **agriculture-based biofuel units safer** by preventing gas leakage hazards.

---

 🚨 **Problem Statement**

Biofuel production from agricultural waste produces toxic and explosive gases.
Manual monitoring is unsafe and inefficient.
A **low-cost IoT-based smart alert system** is required for rural and industrial biofuel chambers.

---
🎯 **Objectives**

* Prevent accidents caused by excess methane buildup
* Protect workers with alert notifications
* Ensure efficient hydrogen/biofuel generation
* Provide low-cost safety solution for farmers

---

🛠 **Hardware Components**

| Component                        | Purpose                 |
| -------------------------------- | ----------------------- |
| Arduino Uno                      | Main controller         |
| MQ-135 Sensor                    | Air Quality / VOC / CO₂ |
| MQ-7 Sensor                      | Carbon Monoxide         |
| MQ-4 Sensor                      | Methane Detection       |
| 16x2 LCD                         | Live display output     |
| Buzzer                           | Alert system            |
| Potentiometer, Wires, Breadboard | Circuit connection      |

---

 ⚙ Working Principle

1️⃣ Sensors detect gas concentration
2️⃣ Arduino converts sensor values → ppm
3️⃣ If gas > safety threshold → Alert ⚠
4️⃣ LCD displays real-time data
5️⃣ Buzzer activates for danger condition

---

 📊 System Flow

```mermaid
flowchart TD
A[Start] --> B[Sensor Data Reading]
B --> C{Gas Level Safe?}
C -->|Yes| D[Display NORMAL Status]
C -->|No| E[Activate Buzzer & Show ALERT]
E --> F[Continuous Monitoring]
D --> F
F --> B
```

---

 🎥 Demo Video

📌 https://drive.google.com/drive/folders/1GU0N4ZCKR_kVSVW_M5eahLlHOltW-Kbb

---

 🌱 Future Scope

* Cloud data logging (Firebase/ThingSpeak)
* Mobile app + SMS alerts
* Automatic ventilation controls
* AI-based gas leakage prediction

---

 👩‍💻 Authors

**Pavni Singh &
Kumkum Chauhan**

---

 📄 License

This project is part of an academic submission.
Open for improvement and educational use.

---
 📬 Contact

If you want to collaborate or improve this system:

📧 [singhpavni2006@gmail.com]
📧 [kumkumchauhan32625@gmail.com]

---

⭐ If you like this project, don't forget to star ⭐ the repository!

---

