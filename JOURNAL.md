---
title: Mini RC Ibishu Pigeon
author: Jonathan Itoh
description: A mini 3d-printed RC car based off of the Ibishu Pigeon from BeamNG.drive. It has rear independent suspension and a single front wheel. It's powered by a 7.4V battery and the H-bridge PWM DC esc is built from scratch. It can maybe drift too.
created_at: 2025-06-25
---
**Total Time Spent: 18h**


# July 28th:
Thought of this project, found motors, micro servos, and batteries from old projects, and decided to make the motor controller from scratch. I first thought only 1 transistor was needed, but after research I found out that it needed 4. I modeled the basic chassis, imported the Pigeon body, made most of the rear drivetrain, and designed some wheel iterations. The Ibishu Pigeon from the game has solid-axle suspension, but I chose to use independent suspension because it's better on RC cars (although probably useless on a 3-wheeled one, but still fun to design). Small moving parts are held together with staples, strong mechanical parts have plastic rods/pegs, and rigid parts are connected with glue or melted together. The dogbone joints also use flattened staples as pins and they slot into the half-shafts. The wheels are held in with short screws and the hub has a shaped indent to lock in.

<img width="967" height="509" alt="image" src="https://github.com/user-attachments/assets/b4e8eeff-43bd-4c2f-ac9e-b8f8e9ed0460" />

**time spent: 7h**



# July 29th:
Researched more about the motor controller. Found out that 2 P-channel and 2 N-channel MOSFETS are needed for reverse in an H-bridge. NPN transistors are also needed for handling higher volts and stuff. I also found flyback diodes and resistors and tested their current handling. I researched how to get them without ordering, but found some on a broken esc laying around. I took them off and searched their numbers and they're exactly what I need.

**time spent: 3h**



# July 30th:
I did more research and made the wiring diagram. I had the idea to use rubber bands for suspension, so I added that to the model. Then, I finished the front steering and chassis. The steering was simple with a pivot inside the front wheel and actuated by a lever connected to a tiny servo.

<img width="1052" height="682" alt="image" src="https://github.com/user-attachments/assets/a7282fac-7858-416f-81c6-90bec8415700" />
<img width="611" height="477" alt="image" src="https://github.com/user-attachments/assets/ea4a28ee-53af-44ce-8f3c-5eee6431bea1" />


**time spent: 5h**

# August 3rd:
I remodeled the front suspension arm and added places for the electronics. For more torque and better acceleration, I added a gearbox for reduction.

<img width="943" height="468" alt="image" src="https://github.com/user-attachments/assets/21ae6341-6eb2-4ca7-8cf7-ff2a54065f28" />

**time spent: 3h**
