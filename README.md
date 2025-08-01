# DAVA SEVA – Automated Ayush Medicine Dispensing System

**DAVA SEVA** (Drug Automated Vending Aparatus – Swayamchalit E-Aushadhi Vikri Aalay) is an innovative, Smart India Hackathon (SIH) project that aims to revolutionize healthcare accessibility by providing an **automated dispensing solution for Ayurvedic medicines**. It functions like an ATM machine, simplifying medicine distribution using modern embedded systems, user-friendly mobile UI, and secure digital verification.

---

## 🩺 Problem Statement

In rural and remote regions, access to authentic **Ayush (Ayurvedic)** medicines is limited. DAVA SEVA provides a **self-operable dispensing ATM** that ensures:

* Authenticity
* Convenience
* Accuracy
* Affordability
* Availability in regional languages (20+)

---

## 🚀 Features

* 🔒 **Secure QR-Based Prescription**: Patients receive a unique QR code after prescription by a certified Ayush doctor.
* 📱 **Mobile App Integration**: Patient receives and stores prescription QR securely.
* 🧾 **Instant Verification**: QR code is scanned at the ATM for instant verification.
* 💊 **Automated Dispensing**: Dispensing mechanism delivers the exact medicines.
* 💳 **UPI-Based Payment**: Simple, cashless transaction interface.
* 🌐 **24/7 Availability**: Machines can operate around the clock.

---

## 🧠 System Architecture

### 1. **Software Module**

* **Prescription Upload**: Doctor saves prescription on web portal → stored in patient profile.
* **QR Generation**: System generates a unique QR and sends it to the patient.
* **Patient App**: Securely stores and manages the QR for use at DAVA SEVA ATM.

### 2. **Hardware Module**

* **QR Scanner & Display Unit**: Raspberry Pi-based system scans the QR and displays prescription.
* **Availability Check**: System checks inventory and calculates cost.
* **Payment Gateway**: UPI QR code or ID options for seamless payment.
* **Medicine Dispensing Mechanism**:

  * **X & Y Axis Movement** using Lead Screw Linear Actuators.
  * Tray-based medicine outlet guided by microprocessor-controlled motors.

---

## 🛠️ Technologies Used

* **Embedded System**: Raspberry Pi
* **Mechanics**: Lead Screw Linear Actuator
* **Frontend**: Android App for Patients
* **Payment Integration**: UPI (QR Code and ID)
* **Database**: Patient Prescription Records
* **Programming**: Python / Embedded C / Android XML

---

## 📱 UI Preview

| Login Screen              | Prescription Details      | Payment Options           | Dispensing Screen         |
| ------------------------- | ------------------------- | ------------------------- | ------------------------- |
| ![UI 1](.3D_Design/3D_design1.jpg) | ![UI 2](.3D_Design/3D_design3.jpg) | ![UI 2](.3D_Design/3D_design3.jpg) | ![UI 1](.3D_Design/3D_design1.jpg) |

---

## ⚙️ Installation & Setup (Demo)

> *For demonstration only; actual deployment involves hardware integration.*

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/DAVA-SEVA.git
   cd DAVA-SEVA
   ```

2. Run UI locally:

   * Android Studio for Mobile App
   * Python scripts for QR & hardware logic (if available)

3. Upload prescriptions through the doctor’s portal (simulated).

4. Use test QR to simulate ATM flow.

---

## 📋 Future Scope

* Cloud connectivity for real-time medicine stock management.
* Integration with government Ayush databases.
* Expansion to home-delivery based on prescription verification.
* Full-scale pilot in rural healthcare centers.

---

## 💡 Team Note

> This project was developed during **Smart India Hackathon (SIH)** with the goal to make **Ayush healthcare more accessible, affordable, and automated**. We deeply believe in this idea’s potential to solve real-world challenges and are working toward real-world deployment.

---

## 🤝 Contributions

We welcome collaboration to enhance hardware mechanisms, improve software stability, and integrate with national health databases.



