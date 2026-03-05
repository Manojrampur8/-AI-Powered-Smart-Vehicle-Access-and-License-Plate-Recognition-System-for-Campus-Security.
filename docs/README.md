# AI-Powered Smart Vehicle Access and License Plate Recognition System for Campus Security

![Python](https://img.shields.io/badge/Python-3.9-blue)
![Computer Vision](https://img.shields.io/badge/Computer%20Vision-OpenCV-green)
![OCR](https://img.shields.io/badge/OCR-EasyOCR-orange)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-AI-red)
![Status](https://img.shields.io/badge/Project-Real--World%20Deployment-success)
![Platform](https://img.shields.io/badge/Platform-Campus%20Security-purple)

🚀 **Real-Time Deployment:**  
This project has been **selected for real-time deployment at Jain Institute of Technology Engineering College, Davanagere, Karnataka, India**, to strengthen campus vehicle access security and automate entry monitoring.

---

# Project Overview

This project introduces an **AI-powered Smart Vehicle Access Control System** designed to automate and enhance security in restricted environments such as **university campuses, residential communities, and secure facilities**.

The system captures vehicle images using a camera and processes them using **Computer Vision techniques** to detect license plates. The detected plate is then processed using **Optical Character Recognition (OCR)** to extract the vehicle registration number.

The extracted license plate number is compared with a **database of authorized vehicles**. Based on the verification result, the system automatically decides whether to **grant or deny vehicle access**.

Authorized vehicles are allowed entry, while unauthorized vehicles trigger alerts and security notifications, ensuring **efficient access control, monitoring, and improved campus security**.

---

# System Workflow

The following diagram illustrates the operational workflow of the system.

![System Workflow](docs/system_workflow.png)

---

# Technologies Used

This system integrates technologies from **Artificial Intelligence, Computer Vision, and Automation**:

- **Python** – Core programming language used for development  
- **OpenCV** – Image processing and license plate detection  
- **NumPy** – Numerical operations and data processing  
- **EasyOCR** – Optical Character Recognition for extracting plate numbers  
- **Machine Learning Concepts** – Supporting intelligent recognition tasks  
- **IP Camera / Webcam Integration** – Real-time vehicle image capture  

---

# Key Features

- Real-time vehicle detection using camera input
- Automatic license plate detection using computer vision
- OCR-based extraction of vehicle registration numbers
- Verification with an authorized vehicle database
- Automated access control system
- Detection and alert for unauthorized vehicles
- Logging of vehicle entry records
- Hardware integration with LCD display, LEDs, and buzzer for alerts

---

# System Outputs

### Real-Time License Plate Detection
![Detection](results/webcam_detection.png)

### OCR Recognized License Plate
![OCR](results/ocr_detection_output.png)

### Registered Vehicle Verification
![Verified](results/vehicle_verified_lcd.png)

### Unauthorized Vehicle Alert
![Denied](results/access_denied_lcd.png)

### Access Granted Indicator (Green LED)
![Green LED](results/green_led_access.png)

### Security Alert System (Red LED + Buzzer)
![Red LED](results/red_led_alert.png)

### Vehicle Entry Log (Excel Record)
![Log](results/vehicle_log_entries.png)

---

# Applications

This system can be applied in several real-world scenarios:

- **University and College Campus Security**
- **Smart Parking Management Systems**
- **Automated Toll Gate Systems**
- **Restricted Area Vehicle Access Control**
- **Residential Security Gate Automation**
- **Smart City Security Infrastructure**

---

## Project Structure

```
AI-Powered-Smart-Vehicle-Access-and-License-Plate-Recognition-System
│
├── dataset
│   └── registered_vehicles.csv
│
├── docs
│   └── system_workflow.png
│
├── results
│   ├── webcam_detection.png
│   ├── ocr_detection_output.png
│   ├── vehicle_verified_lcd.png
│   ├── access_denied_lcd.png
│   ├── green_led_access.png
│   ├── red_led_alert.png
│   └── vehicle_log_entries.png
│
├── src
│   └── license_plate_recognition.py
│
└── README.md
```

---

## How to Run the Project

### 1. Clone the Repository

```
git clone https://github.com/Manojrampur8/AI-Powered-Smart-Vehicle-Access-and-License-Plate-Recognition-System.git
```

### 2. Navigate to the Project Directory

```
cd AI-Powered-Smart-Vehicle-Access-and-License-Plate-Recognition-System
```

### 3. Install Required Libraries

```
pip install opencv-python numpy easyocr pandas
```

### 4. Run the System

```
python src/license_plate_recognition.py
```

After running the script, the system will start capturing vehicle images, detecting license plates, verifying them with the registered vehicle database, and controlling vehicle access automatically.

---

## Author

**Manoj S**  
AI & Machine Learning 
Enthusiast  

