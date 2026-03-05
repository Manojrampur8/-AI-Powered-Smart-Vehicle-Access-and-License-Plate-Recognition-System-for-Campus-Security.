# AI-Powered Smart Vehicle Access and License Plate Recognition System for Campus Security

## Project Overview

This project implements an **AI-driven smart vehicle access control system** designed to enhance security in controlled environments such as university campuses, residential communities, and restricted facilities.

The system automatically captures vehicle images using a camera, detects the license plate using **computer vision techniques**, and extracts the license plate number through **Optical Character Recognition (OCR)**. The recognized license plate is then verified against a **database of authorized vehicles**.

Based on the verification outcome, the system intelligently determines whether to **grant or deny access**. Authorized vehicles are allowed entry, while unauthorized vehicles trigger alerts and access restrictions. This automated process helps improve **security monitoring, access management, and operational efficiency**.

---

## System Workflow

The following diagram illustrates the working process of the **AI-Powered Smart Vehicle Access and License Plate Recognition System**.

![System Workflow](docs/system_workflow.png)

---

## Technologies Used

The system integrates several technologies from the fields of **Artificial Intelligence, Computer Vision, and Automation**:

* **Python** – Core programming language used for system development
* **OpenCV** – Image processing and license plate detection
* **NumPy** – Efficient numerical computations and data processing
* **EasyOCR / OCR** – Optical Character Recognition for extracting license plate numbers
* **Machine Learning Techniques** – Supporting intelligent detection and recognition tasks
* **IP Camera / Webcam Integration** – Real-time vehicle image capture

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

### Access Granted Indicator
![Green LED](results/green_led_access.png)

### Security Alert System
![Red LED](results/red_led_alert.png)

### Vehicle Entry Log
![Log](results/vehicle_log_entries.png)

---

## Project Features

* Automatic vehicle detection using a camera
* License plate detection using computer vision techniques
* Character recognition using Optical Character Recognition (OCR)
* Verification of detected license plates with an authorized vehicle database
* Automated access control based on verification results
* Unauthorized vehicle detection and alert generation
* Logging of vehicle entry information for monitoring and security
---
## Applications

This system can be applied in various real-world scenarios, including:

* **University and College Campus Security**
* **Smart Parking Management Systems**
* **Automated Toll Gate Systems**
* **Restricted Area Vehicle Access Control**
* **Smart City Surveillance and Security Infrastructure**

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
│   └── example_outputs
│
├── src
│   └── license_plate_recognition.py
│
└── README.md
```
## How to Run the Project

1. Clone the repository

```
git clone https://github.com/Manojrampur8/AI-Powered-Smart-Vehicle-Access-and-License-Plate-Recognition-System.git
```

2. Navigate to the project directory

```
cd AI-Powered-Smart-Vehicle-Access-and-License-Plate-Recognition-System
```

3. Install required libraries

```
pip install opencv-python numpy easyocr
```

4. Run the license plate recognition script

```
python src/license_plate_recognition.py
```

The system will start detecting license plates and verifying them with the authorized vehicle database.

---
## Author

**Manoj S**
AI & Machine Learning Enthusiast
