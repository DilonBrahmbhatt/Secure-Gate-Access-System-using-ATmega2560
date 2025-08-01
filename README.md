# 🔐 ATMega2560 Keypad Entry System

*Secure access control system with employee management*

---

## ✨ Key Features

| Feature                 | Description                      |
|-------------------------|---------------------------------|
| 👥 Employee Management  | Add/remove employee IDs          |
| 🔒 Security             | Password protection & ID blocking|
| 📱 User Interface       | LCD display & keypad input       |
| 🔔 Feedback             | Buzzer & LED indicators          |
| 🚗 Motor Control        | Motor-driven gate opening/closing|

---

## 🔧 System Components

| Component         | Description                | Function                      |
|-------------------|----------------------------|------------------------------|
| ATMega2560        | Main microcontroller       | System brain & processing     |
| 3×4 Keypad        | User input interface       | ID & password entry           |
| 16×2 LCD Display  | Visual feedback screen     | Show messages & status        |
| Buzzer            | Audio feedback device      | Sound alerts & confirmations  |
| Status LEDs       | Visual indicators          | Access granted/denied signals |
| Motor Driver & Motor | Gate actuation            | Opens/closes physical gate    |

---

## 🔄 How The System Works

1. ⚡ **Power On:** System initializes and displays welcome message  
2. 🔢 **Enter ID:** User inputs employee ID via keypad  
3. 🔍 **Verification:** System checks ID against database  
4. 🚗 **Motor Control:** Motor activates to open/close gate on access granted  
5. 🚪 **Access Control:** Grants or denies entry based on verification  

---

## ⚙️ Default Settings

| Setting            | Value                             |
|--------------------|----------------------------------|
| **Admin Password:** | `1234`                           |
| **Admin Access:**   | Press `*` + `#` then enter password |

---

## 💻 Installation Steps

1. **Hardware Setup:** Connect all components including motor and driver according to circuit schematic  
2. **Code Upload:** Flash the program to the ATMega2560 microcontroller  
3. **Power Connection:** Connect power supply and turn on the system  
4. **Initial Test:** Verify LCD, keypad, and motor functionality  

> **📝 Note:** Double-check motor power and wiring before powering on.

---

## 🛠️ System Operations

### 👨‍💼 Administrative Functions

| Operation           | Process                                | Result                       |
|---------------------|---------------------------------------|------------------------------|
| ➕ Add Employee      | Admin menu → Enter new employee ID    | ID added to authorized list   |
| ➖ Remove Employee   | Admin menu → Enter ID to remove        | ID removed from system        |
| 🔓 Unblock ID       | Admin menu → Enter blocked ID          | ID access restored            |
| 🔐 Change Password  | Admin menu → Enter new password        | Admin password updated        |

### 👤 User Operations

- **Normal Access:** Enter employee ID and press `#`, motor activates to open gate  
- **Access Denied:** Contact administrator if your ID is blocked  
- **Forgot ID:** Contact HR department for your assigned employee ID  

---

## 📊 System Specifications

| Parameter          | Details                         |
|--------------------|---------------------------------|
| **Microcontroller** | ATMega2560 (16MHz, 256KB Flash) |
| **Display**         | 16×2 Character LCD with backlight |
| **Input**           | 3×4 Matrix Keypad (12 keys)      |
| **Output**          | Buzzer + Status LEDs (Red/Green) |
| **Motor**           | DC Motor with driver for gate control |
| **Power Supply**    | 5V DC                           |
| **Memory**          | Stores up to 100 employee IDs    |

---

## 🎯 About This Project

Developed using Embedded C and simulated in Proteus, this enhanced keypad entry system now includes motor control for automated gate operation, providing secure and convenient access management.

---

*For more details or source code, please check the repository files.*

---
