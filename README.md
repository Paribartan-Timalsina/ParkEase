# ParkEase - Smart Parking System

## Description
ParkEase is a smart parking system that allows users to book parking spots and receive real-time updates on available spaces using object detection models. The system leverages computer vision techniques to enhance the parking experience, reducing congestion and improving efficiency.

## Features
- **Real-time Parking Availability**: Uses object detection models to monitor parking spaces.
- **Reservation System**: Users can book parking spots in advance.
- **Cross-platform Mobile Application**: Built with Flutter for seamless experience.
- **Backend API**: Developed with Flask and Node.js for efficient data handling.
- **YOLOv8 Integration**: Enables object detection for parking space monitoring.

## Tech Stack
- **Frontend**: Flutter
- **Backend**: Flask, Node.js
- **Computer Vision**: YOLOv8
- **Programming Languages**: Python, Dart, JavaScript

## Installation & Execution

### Prerequisites
- Python 3.x
- Flutter SDK
- Node.js & npm
- Virtual environment (optional but recommended)

### Clone the Repository
```bash
git clone https://github.com/Paribartan-Timalsina/ParkEase.git
cd parkease
```

### Backend Setup
1. Install dependencies:
```bash
pip install -r requirements.txt
```
2. Start the Flask backend:
```bash
flask run
```

### Frontend Setup
1. Navigate to the Flutter project directory:
```bash
cd mobile_app
```
2. Install dependencies:
```bash
flutter pub get
```
3. Run the mobile app:
```bash
flutter run
```

