---
title: Mini RC Ibishu Pigeon
author: Jonathan Itoh
description: A mini 3d-printed RC car based off of the Ibishu Pigeon from BeamNG.drive. It has rear independent suspension and a single front wheel. It's powered by a 7.4V battery and the H-bridge PWM DC esc is built from scratch. It can maybe drift too.
created_at: 2025-06-25
---



# July 28th:
Thought of this project, found motors, micro servos, and batteries from old projects, and decided to make the motor controller from scratch. I first thought only 1 transistor was needed, but after research I found out that it needed 4. I modeled the basic chassis, imported the Pigeon body, made most of the rear drivetrain, and designed some wheel iterations.

<img width="967" height="509" alt="image" src="https://github.com/user-attachments/assets/b4e8eeff-43bd-4c2f-ac9e-b8f8e9ed0460" />

**Total time spent: 6h**



# July 29th:
Researched more about the motor controller. Found out that 2 P-channel and 2 N-channel MOSFETS are needed for reverse in an H-bridge. NPN transistors are also needed for handling higher volts and stuff. I also found flyback diodes and resistors and tested their current handling. I researched how to get them without ordering, but found some on a broken esc laying around. I took them off and searched their numbers and they're exactly what I need.

<img width="967" height="509" alt="image" src="https://github.com/user-attachments/assets/b4e8eeff-43bd-4c2f-ac9e-b8f8e9ed0460" />

**Total time spent: 3h**

# July 30th:
I did more research and made the wiring diagram. I had the idea to use rubber bands for suspension, so I added that to the model. Then, I finished the front steering and chassis.

<img width="1052" height="682" alt="image" src="https://github.com/user-attachments/assets/a7282fac-7858-416f-81c6-90bec8415700" />
<img width="611" height="477" alt="image" src="https://github.com/user-attachments/assets/ea4a28ee-53af-44ce-8f3c-5eee6431bea1" />


**Total time spent: 6h**
