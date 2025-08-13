# Wirelss-Notice-Board
Wireless Notice Board system using Arduino Uno, RTC module, and I2C communication for real-time message and date display.
# Wireless Notice Board

**Status:** ✅ Completed – 2025  

## Overview
This project presents the development of a Wireless Notice Board System using a single Arduino Uno, an RTC module (DS3231), and a 20x4 LCD display connected via the I2C communication protocol. The system displays real-time messages along with the current date and time, offering an efficient and low-cost solution for dynamic message display.

By utilizing I2C for communication, the system simplifies wiring and integration of components, eliminating the need for additional wireless communication modules. It is ideal for environments such as schools, offices, and public spaces where timely updates and announcements are essential.

## Features
- Real-time message display on a 20x4 LCD
- Accurate date and time display via RTC (DS3231)
- I2C protocol for minimal wiring and efficient communication
- Cost-effective and reliable design
- Easy to operate and maintain

## Tools & Technologies
- **Microcontroller:** Arduino Uno
- **Modules:** DS3231 RTC module
- **Display:** 20x4 LCD with I2C module
- **Programming Language:** C++ (Arduino IDE)
- **Communication Protocol:** I2C

## Working Principle
- The Arduino Uno retrieves real-time date and time from the RTC module.
- Based on pre-programmed conditions, it sends messages to the LCD display over I2C.
- The display shows the message along with the current date and time.
- The system operates continuously, ensuring real-time updates.

## Results
1. **Real-Time Message Display:** Clear and legible text for announcements.
2. **Accurate Time and Date:** Maintained by the DS3231 RTC.
3. **Efficient Communication:** Smooth and reliable I2C data transfer.
4. **Cost-Effective:** No need for complex wireless modules.
5. **Ease of Use:** Simple to operate and maintain.

## Future Enhancements
- **Remote message updates** via Bluetooth or Wi-Fi
- **Multiple message storage** with auto cycling
- **User input devices** like keypad or touchscreen
- **Advanced scheduling** for time-sensitive announcements
- **Wireless synchronization** for multiple boards

## Team Members
Ananya Acharya, Deepthi, Jathan Shraddha Vasantha, Poornitha  
**Guide:** Ms. Pavithra Poornima S  
**Co-Guide:** Mr. Raghunatha  
Shri Madhwa Vadiraja Institute of Technology and Management, ECE Dept., Batch No. 12
