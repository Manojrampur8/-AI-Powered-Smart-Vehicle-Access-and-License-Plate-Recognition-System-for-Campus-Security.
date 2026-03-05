# AI-Powered Smart Vehicle Access and License Plate Recognition System for Campus Security

## Project Overview

This project presents an **AI-powered smart vehicle access control system** designed to enhance security and automate vehicle entry management in restricted environments such as educational institutions, residential complexes, and secured facilities.

The system uses **computer vision and optical character recognition (OCR)** to automatically detect and recognize vehicle license plates in real time. A camera captures vehicle images, the system detects the license plate region, and the plate number is extracted using OCR techniques.

The detected license plate is then verified against a **database of authorized vehicles**. Based on the verification result, the system automatically determines whether to **grant access or deny entry**.

Authorized vehicles are allowed to pass through the gate, while unauthorized vehicles trigger security alerts, ensuring improved **campus safety, monitoring, and automated vehicle management**.

---

## Real-Time Deployment

This project has been **selected for real-time deployment at Jain Institute of Technology Engineering College, Davanagere, Karnataka, India**, where it will be used to enhance campus security by automating vehicle access control and monitoring.

---

## System Workflow

The following diagram illustrates the operational workflow of the **AI-Powered Smart Vehicle Access and License Plate Recognition System**.

![System Workflow](docs/system_workflow.png)

---

## Technologies Used

This system integrates technologies from **Artificial Intelligence, Computer Vision, and Automation**:

- **Python** – Core programming language for system development  
- **OpenCV** – Image processing and license plate detection  
- **NumPy** – Numerical computations and array processing  
- **EasyOCR / OCR** – Optical Character Recognition for extracting license plate numbers  
- **Machine Learning Techniques** – Supporting intelligent detection processes  
- **IP Camera / Webcam Integration** – Real-time vehicle image acquisition  

---

## Key Features

- Real-time vehicle detection using camera input
- Automatic license plate detection using computer vision
- Text extraction from license plates using OCR
- Verification of vehicle numbers with an authorized database
- Automated vehicle access control system
- Unauthorized vehicle detection with alert mechanism
- Real-time monitoring and logging of vehicle entries
- Integration with hardware components such as LCD display, LEDs, and buzzer

---

## System Outputs

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

## Applications

This system can be implemented in multiple real-world environments:

- **University and College Campus Security**
- **Smart Parking Management Systems**
- **Automated Toll Gate Systems**
- **Restricted Area Vehicle Access Control**
- **Residential Security Gate Automation**
- **Smart City Surveillance Systems**

---
## Project Structure

AI-Powered-Smart-Vehicle-Access-and-License-Plate-Recognition-System
│
├── dataset
│ └── registered_vehicles.csv
│
├── docs
│ └── system_workflow.png
│
├── results
│ ├── webcam_detection.png
│ ├── ocr_detection_output.png
│ ├── vehicle_verified_lcd.png
│ ├── access_denied_lcd.png
│ ├── green_led_access.png
│ ├── red_led_alert.png
│ └── vehicle_log_entries.png
│
├── src
│ └── license_plate_recognition.py
│
└── README.md
---

---

## How to Run the Project

### 1. Clone the Repository
git clone https://github.com/Manojrampur8/AI-Powered-Smart-Vehicle-Access-and-License-Plate-Recognition-System.git


### 2. Navigate to the Project Directory
cd AI-Powered-Smart-Vehicle-Access-and-License-Plate-Recognition-System


### 3. Install Required Libraries
pip install opencv-python numpy easyocr pandas


### 4. Run the System
python src/license_plate_recognition.py

---

The system will start capturing vehicle images, detecting license plates, verifying them with the registered vehicle database, and controlling access accordingly.

---

## Author

**Manoj S**  
AI & Machine Learning 
Enthusiast  

