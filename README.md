# Great HR Software

## Overview
Great HR Software is an advanced HR management system designed to track and analyze employee attendance and performance using RFID and fingerprint devices connected to the hospital server. The system will notify employees of their attendance timings and provide comprehensive analytics.

## Features
- **Attendance Tracking**: Accurate logging of employee attendance using RFID and fingerprint verification.
- **Notifications**: Employees receive attendance notifications via email and WhatsApp.
- **Analytics**: Detailed reports on attendance, working hours, performance, bonuses, etc.
- **Rating System**: Includes "Employee of the Week" and "Employee of the Month" features.
- **Remote Access**: Accessible from any device (mobile, laptop, PC) with a user-friendly interface.
- **Performance and Statistics**: Employees can check their performance and statistics in graphical representation. Admins can track the entire system graphically and download performance data from anywhere.
- **Automatic Sleep Mode**: The system automatically goes into sleep mode when not in use and wakes up to take attendance when it detects human presence.
- **Main Server Storage**: Data will be stored directly on CP hospital's main server, ensuring we do not rely on external platforms for server services.

## Hardware Components
- ESP32
- RFID Module
- OLED Display
- Fingerprint Module
- Other necessary electronic components

## Software Stack
- **Backend**: Python, Django
- **Frontend**: React.js (with a focus on a good-looking UI)
- **Database**: PostgreSQL or MySQL
- **Notifications**: Email and WhatsApp or Application

## Implementation Plan
1. **Hardware Integration**: Assemble and test the hardware components.
2. **Backend Development**: Set up the Django server, create models for attendance and notifications.
3. **Frontend Development**: Develop a responsive and attractive UI using React.js.
4. **Notification System**: Integrate email and WhatsApp for notifications.
5. **Automatic Sleep Mode**: Implement the sleep mode and wake-up functionality.
6. **Main Server Setup**: Ensure data storage directly on CP hospital's main server.
7. **Testing**: Thorough testing of the entire system.
8. **Deployment**: Deploy the system on the hospital server and ensure secure access.

## Future Enhancements
- Integration with payroll systems.
- Advanced analytics and reporting features.
- Mobile app development for enhanced accessibility.

## Contact
For any queries or suggestions, please contact Paritosh Barman at barmanpari163@gmail.com.
