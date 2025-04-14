## SmartView Systems

### [Demo Video](https://drive.google.com/file/d/17eZBgUDK1DZ4LuyB96WZPyytZiaMd2u8/view?usp=sharing)

### Project Background
SmartView Systems started as a final project as part of BU's EC444 Smart and Connected Systems. After the completion of the class. Noah and Benji continued working on the project partnering with the BU Animal Science Center and Participating in the New Venture Competition. 

### Project Goal
Smartview Systems aims to empower our users with the information necessary to monitor their environments. We envision a future where companies can monitor the instruments, tools, machinery, and workspaces 24 hours a day, seven days a week. 

With our tools, companies will have the data to make proactive decisions regarding their environmental conditions. If a refrigerator door is left open, users can see a temperature drop in real-time rather than the effects the following day. If a power outage causes a heater to turn off, users can see exactly how much the temperature dropped rather than speculate and hope. 

Our products will also be valuable during experiments as well. By having the ability to monitor critical lab environments, we will empower our customers with data that proves consistent and reliable experimental conditions. Without accurate and reliable environmental condition data, individuals are blind to what is happening in their lab.

### Product Features
**1. The first feature of our system is a dashboard that we have built to allow the user to interact with the sensor network.**

Users can configure their devices through the dashboard, including changing the device name and data collection frequency. Users can create alarms that can detect changes in the environment. If users want to monitor a refrigerator, they can set a lower bound minimum temperature that will be triggered if it drops too low. Once an alarm has been reached, a notification system will notify the user with an alert via text messaging and Slack notification.


**2. The second feature of our system is physical sensor modules that can wirelessly connect to the sensor network.**
The module's central chip is an ESP32 development board allowing wifi connectivity with the system. The esp32 board is connected to a temperature and humidity sensor, which will measure and send temperature to the database periodically. On the board, we have developed proprietary software that enables the devices to be configured from the dashboard. If the user wants the device to sample faster, with the click of a button, the message will be sent to the sensor module, and the device will change its internal settings.



### Team Members
**Benji Gilbert ENG 2025**   
Benji has immense experience in full-stack development, specializing in Angular and ASP.NET. He is an incoming Summer Technology Analyst at Morgan Stanley after interning there last summer. Benji also has a strong background in leadership, serving as the Director of Technology Consulting at the Boston University TAMID chapter and the Vice President of Boston University's Alpha Epsilon Pi chapter. He is a Junior studying Computer Engineering at Boston University and is concentrating on Machine Learning.
 
**Noah Robitshek ENG 2025**
Noah has a background in full-stack development and embedded systems. Previously, Noah worked on ResearchRatings.com, developing the front end in React and the back end in Firebase. Additionally, Noah developed wireless heart rate monitors last summer as part of the SensorWeb Research Laboratory at the University of Georgia. Noah is currently a Junior studying Computer Engineering at Boston University.
