 Robotic Vacuum Cleaner using Arduino

For many people, returning home after a stressful day at work to a relaxing evening can be a major relief. However, the realization that they have chores to do, such as cleaning, can be daunting. Cleaning is a necessary requirement for personal hygiene, especially for those with dust allergies and illnesses like asthma. Busy schedules or fatigue can make it difficult for people to carry out cleaning tasks daily.

Having a robotic little friend that can automatically detect dust and clean the floor with the press of a button can provide a big convenience. Robotic vacuum cleaners are able toclean places that regular vacuums can't reach, such as under furniture and in corners that are blocked off to traditional vacuums. They are dust bunny eradicators. These gadgets are particularly useful for busy individuals who desire a clean home even when they don't have the time to do the work themselves. Additionally, watching these robots at work can be enjoyable.
The use of robotics in everyday life has been growing rapidly in recent years, and one area where this technology is becoming increasingly popular is in the realm of cleaning. Robotic vacuum cleaners have been on the market for several years, but advances in sensor technology and microcontrollers are enabling the development of increasingly sophisticated and capable devices.

This project aims to develop a robotic vacuum cleaner using ultrasonic sensors and an Arduino Uno microcontroller to navigate around obstacles and walls in a room while efficiently cleaning the floor. The ultrasonic sensors provide accurate distance measurements, allowing the vacuum cleaner to detect and avoid obstacles and walls. The Arduino Uno serves as the brain of the robotic vacuum cleaner, processing the sensor data and sending signals to the motor to change direction as needed.

Block and Circuit Diagram

![Capture](https://github.com/user-attachments/assets/057b6df0-76e6-4cfb-868a-b774c944389d)


![image](https://github.com/user-attachments/assets/69c0ceec-4363-4c0c-93e5-565f925ff470)

Methodology

The methodology for creating an Arduino-based smart  Vacuum  cleaner  entails defining the cleaning requirements, selecting the necessary hardware  components, such as motors, sensors, and batteries, writing the software  code using  the Arduino IDE, assembling the components in accordance  with  the  design,  testing  and debugging the system to ensure it satisfies the requirements, improving the design to add features, and documenting the design and code for later use.  To  produce  a practical and effective tool that can carry out particular cleaning activities automatically or manually, this requires a mix of hardware and software design and testing.
When the robot is switched ON, both the motors of robot will run normally and the robot moves forward. During this time the ultrasonic sensor continuously calculate the distance between the robot and the reactive surface. This information is processed by the arduino; if the distance between the robot and the obstacle is less than 20 cm the left wheel motor is reversed in direction and right wheel motor operate normally. This will rotate the robot towards right. This rotation continues until the distance between the robot and obstacle is greater than 20cm.This process continues forever and the robots keeps on moving without hitting any obstacles.

Working

![image](https://github.com/user-attachments/assets/02ca81b6-1500-49e0-b862-a304e1b8fa79)

As shown in the above figure, when there is a pressure difference between two places, materials flow from one place to another. The fundamental operating principle of the perfect vacuum cleaner is this phenomena. A centrifugal fan moves the air by introducing external kinetic energy to it while it turns. Negative pressure is created behind the fan as air is drawn in from behind and forced forward with it. This centrifugal fan, which is attached to a motor, is found in the ultimate vacuum cleaner. This device has connections for suction and discharge; on the suction side, a filter bag is installed prior to the hose connection. The discharge is open to the atmosphere and features a second air purifier filter. The motor and centrifugal fan both rotate when electricity is applied. All airborne particles, including cat allergen, mist, dirt, and minute solid particles, are delivered to the suction filter together with the air that is drawn into the device from the suction side. Filtered air is forced out of the discharge aperture while the particles are trapped in the filter.

Result

![image](https://github.com/user-attachments/assets/b086a94d-0306-4bb5-84bb-2a90dde2a119)

The result of using arduino based vacuum cleaner is that it is less cost compared to theregular automatic vacuum cleaners, and it can do the cleaning of the surroundings effectively. The speed of the motors is 40rpm,the suction power the vacuum cleaner is 5000pa to absorb small things such as dust,hair etc.It can absorb the dust particles range in size from 1 to 400 mm.
The following are some benefits of arduino based smart vacuum cleaner.


1. Cost-effective: Arduino-based smart vacuum cleaners are relatively inexpensive compared to commercially available vacuum cleaners, making it a cost-effective option for those on a budget.
   
2. Customizable: Arduino provides a platform for developers to customize their smart vacuum cleaner, allowing them to add features that meet their specific needs.
   
3. User-friendly: Arduino's programming environment is user-friendly, making it easier for non-programmers to create their own smart vacuum cleaner.
   
4. Scalability: The modular design of Arduino boards allows users to easily upgrade or addnew features to their smart vacuum cleaner as needed.
   
5. Flexibility: With an Arduino-based smart vacuum cleaner, users can choose to use different sensors, motors, and other components, allowing for greater flexibility in terms of design and functionality.




