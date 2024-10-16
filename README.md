# Smart Glasses for the Visually Impaired

## Overview
The Smart Glasses for Visually Impaired project aims to enhance the independence and safety of individuals with visual impairments through advanced wearable technology. Traditional mobility aids, such as white canes, provide limited tactile feedback. Our solution integrates real-time obstacle detection, GPS-based navigation, and emergency alerts to offer visually impaired users improved spatial awareness and hands-free assistance.

## Key Features
### 1. Real-Time Obstacle Detection
The glasses are equipped with an **OV2640 camera** for continuous video capture, enabling real-time detection of both dynamic and static obstacles using computer vision techniques.
- **Dynamic Objects**: Detects vehicles, bicycles, and moving animals, triggering high-priority alerts.
- **Static Objects**: Identifies stationary obstacles such as traffic signs, barriers, and fire hydrants, providing low-priority alerts.

### 2. GPS Navigation Assistance
A **GPS module** tracks the user’s location, delivering real-time audio cues on nearby landmarks, intersections, and potential hazards. This feature enhances the user’s ability to navigate both familiar and unfamiliar environments confidently.

### 3. Emergency Alert System
In the event of a fall or accident, the system automatically checks on the user and, if no response is detected, sends emergency alerts to pre-designated contacts. This feature provides an additional layer of security for both the user and their caregivers.

### 4. Hands-Free Audio Feedback
Using a **wireless audio system**, the glasses provide real-time auditory alerts without requiring any manual interaction, allowing the user to remain focused on their surroundings.

## System Components
- **OV2640 Camera**: Mounted on the glasses, it captures the user’s surroundings in real-time.
- **Raspberry Pi**: Serves as the central processing hub, analyzing video data and managing GPS tracking.
- **ESP32-S3**: Facilitates image processing and wireless data transmission between the camera and Raspberry Pi.
- **GPS Module**: Provides real-time location tracking for navigation assistance.
- **Wireless Audio System**: Delivers hands-free auditory alerts and navigation cues.
- **3D-Printed Frame**: The glasses are designed to be lightweight and ergonomic, ensuring comfort during prolonged use.

## System Architecture
The smart glasses consist of three core subsystems:
1. **Video Capture & Processing**: Captures real-time video of the surroundings, identifies objects using computer vision, and classifies them by priority.
2. **GPS Navigation**: Provides location-based auditory feedback, ensuring users are informed about their environment.
3. **Emergency Alert System**: Automatically triggers alerts if a fall is detected, ensuring timely assistance from caregivers or emergency contacts.

## Object Detection & Classification
- **Dynamic Objects**: Fast-moving objects, such as vehicles and bicycles, are classified as high-priority threats and trigger immediate warnings.
- **Static Objects**: Objects like traffic signs or poles are identified and communicated to the user, ensuring safe navigation without urgent intervention.

## Audio Feedback System
The system delivers alerts through a wireless audio module, providing:
- **High-priority alerts** for imminent dangers such as moving vehicles.
- **Low-priority alerts** for static objects such as poles or traffic lights.

This hands-free feedback ensures that visually impaired users can respond promptly to their environment without the need for manual interaction.

## Future Enhancements
- **Indoor Path Planning**: Development of an indoor navigation system using verbal instructions and clock-based directions for guiding users through indoor environments.
- **Enhanced Emergency Alerts**: Further refinement of the fall detection system to ensure immediate notification of nearby individuals and family members.

## Contributors
- **Yasiru Basnayake**
- **Pulindu Vidmal**
- **Januka Surendra**

## License

