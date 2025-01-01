
# Plastic Collector Machine with Dog Food Reward System (PCM-DFR-System) 🐶

Welcome to the **Plastic Collector Machine with Dog Food Reward System** repository! This innovative project aims to promote recycling by rewarding users with dog food for disposing of plastic bottles. By combining eco-friendly behavior with IoT technology, this system is designed to encourage sustainable practices while catering to pet owners.

---

## 🚀 **Project Overview**

The PCM-DFR-System is a reverse vending machine (RVM) prototype that detects, collects, and rewards users for recycling plastic bottles. It uses sensors, microcontrollers, and a web-based monitoring system to achieve its goals.

---

## 📋 **Key Features**

1. **Plastic Bottle Detection:**
   - Accepts PET bottles of various sizes (295ml, 500ml, 1L).
   - Detects bottles using inductive sensors and a load cell sensor.

2. **Dog Food Reward System:**
   - Dispenses a dog food sausage for each bottle deposited.
   - Tracks user points using RFID cards.

3. **Admin Monitoring System:**
   - A web-based dashboard for managing user accounts and monitoring system performance.

4. **Full-Bin Detection:**
   - Alerts admin when the bin is 100% full using IR sensors.

---

## 🛠️ **System Architecture**

**BLOCK DIAGRAM**

**![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXcE74XeArd_qzuTaHRsEkC0hsW_qzjc5TDARkavpA4ABnXsPfHZ1YSYljWhXWe-hTzlRWJYyODmudi76Kh14ZTi-FGZxmsVBj1-B7pOUWMx4wytH2yPzc85oQDMG9Y6JQvhw4kdygm4KJj23euRtNY?key=wAnhi_jwVwyVVq5B01u1w5JG)**

----
**BREADBOARD DIAGRAM**
**![No description available.](https://lh7-rt.googleusercontent.com/docsz/AD_4nXdC9ii6J8eyqT8RtG8VOzoGo2xp9Mwqi1K9VAe49sfgyUwVosRG504rt4sffat2Q0qN0hnzJDpcJYN_746Yrd_rTvKKLAMEf3vt4G2rIIub9Th9pXEwUGCgJ75NaskOsqBC6keJutg5s8d4D2pAvA?key=wAnhi_jwVwyVVq5B01u1w5JG)**
### Hardware Components:
- **Arduino Uno:** Microcontroller for managing operations.
- **NodeMCU:** For wireless communication.
- **Inductive Proximity Sensor:** Detects plastic materials.
- **Servo Motors:** Operate the dispensing mechanism.
- **IR Sensors:** Detect bin capacity levels.
- **Load Cell Sensor:** Measures the weight of bottles.

### Software Components:
- **MySQL Database:** Tracks user data and bin status.
- **PHP:** Backend programming for the admin panel.
- **RFID System:** Identifies users and tracks their points.

---

## 🌟 **Highlights**

| Feature                     | Description                               |
|-----------------------------|-------------------------------------------|
| **Plastic Detection**       | Accepts PET bottles and rejects metals.  |
| **Reward Mechanism**        | Dispenses dog food based on deposits.    |
| **Web-Based Admin Panel**   | Tracks usage and manages accounts.       |
| **Capacity Monitoring**     | Alerts admin when the bin is full.       |

---

## 📊 **Performance Metrics**

- **Usability Testing:**
  - Measured using the Post-Study System Usability Questionnaire (PSSUQ).
  - Parameters:
    - System Usefulness
    - Information Quality
    - Interface Quality

- **Success Rate:**
  - 94% acceptance for supported bottle types.
  - Response time: 8–13 seconds per bottle.

---
## 🔧 **Setup Instructions**

1. Clone the repository:
   ```bash
   git clone https://github.com/RadiantCatto/PCM-DFR-System.git
   ```
2. Install required dependencies:
   ```bash
   npm install
   ```
3. Configure the database in `config.php`.
4. Run the web panel:
   ```bash
   php -S localhost:8000
   ```

---

## 💡 **Future Enhancements**

- Expand bottle compatibility.
- Integrate solar power for sustainability.
- Add mobile notifications for users.
- Include additional reward options.

---

## 📂 **Repository Structure**

```
PCM-DFR-System/
├── Main/                         # Main project files
│   ├── css/                      # CSS stylesheets
│   ├── database/                 # Database-related files
│   ├── img/                      # Image files
│   ├── includes/                 # PHP include files
│   ├── js/                       # JavaScript files
│   ├── scripts/                  # Custom scripts
│   ├── scss/                     # SCSS files
│   ├── vendor/                   # Third-party libraries and packages
│   ├── UIDContainer.php          # PHP file for UID container functionality
│   ├── adminpanel.sql            # SQL script for admin panel setup
│   ├── code.php                  # Main code file
│   ├── code1.php                 # Additional code file
│   ├── displayUID.php            # PHP file to display UID
│   ├── getUID.php                # PHP file to get UID
│   ├── index.php                 # Main landing page
│   ├── login.php                 # Login page
│   ├── logout.php                # Logout functionality
│   ├── profile.php               # User profile page
│   ├── profile_edit.php          # Edit user profile
│   ├── profile_manage.php        # Manage user profiles
│   ├── register.php              # User registration page
│   ├── register_edit.php         # Edit user registration details
│   ├── security.php              # Security-related settings
│   └── user_index.php            # User index page
│
├── Arduino/                      # Arduino-related code
│   └── ThesisArduinoCode.ino     # Main Arduino code for the project
│
├── IOT/                          # IoT-related code
│   └── ThesisIOTCode.ino         # Main IoT code for the project
│
├── RFID/                         # RFID-related code
│   └── ThesisIotCodeRFID_register.ino  # RFID registration code
│
└── README.md                     # Project overview and instructions
```

---
## 📞 **Contact**

For questions or feedback, please reach out to us via [GitHub Issues](https://github.com/RadiantCatto/PCM-DFR-System/issues).
