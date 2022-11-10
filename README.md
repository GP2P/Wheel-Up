# WheelUp
 
WheelUp is a collaborative research project between [Worcester Polytechnic Institute (WPI)](https://www.wpi.edu/) and [University of Massachusetts Lowell](https://www.uml.edu/). The overall objective of the study is to co-design a high-fidelity VR wheelchair simulator for diverse body. It uses participatory design to engage local communities with alternate-abilities for the development of a wheelchair training simulator with multimodal input interfaces for wheelchair guidance and control. Simulated and virtual reality (VR) training allows users to practice difficult or stressful tasks in a safe environment. The virtual environment will integrate joystick, muscle signals (EMG), and eye gaze (EOG). Aesthetic attributes of the simulator such as color, texture, and layout will be considered to enhance the overall visual experience, making the user experience more enjoyable and appealing. The simulated environment includes standardized hospital or home; variable environments with changing obstacles such as shopping centers or workplaces. (PI: Dr. kelilah wolkowicz)
 
## Game Engine
Unreal Engine 5
 
## Platform
Windows
 
## Virtual Reality
Given the issues related to VR devices such as VR sickness or neck muscle strength, the virtual environment created by this project will be for both "flat-screen" VR and head-mounted VR.
 
When the game starts, it automatically configures the in-game camera for the current display settings. If a VR headset is connected and the VR streaming service is on, the in-game camera is associated with the headset positions. If not, the camera will also face forward, and projects 3 views for 3 monitor displays. 
 
 ## Electric Wheelchair Specifications
(Gravity = 9.81 m/s <sup>2</sup>)

Current simulator uses Jazzy® Select wheelchair models. Details can be found [here](https://www.pridemobility.com/jazzy-power-chairs/jazzy-select/manuals.asp). 

Component Weights: Jazzy Select Base: 94 lbs. (42.5 kg) Standard Seat: 50.75 lbs. (23 kg) Batteries: 25.25 lbs. (11.5 kg)

Overall Size: Length: 44 in. (1118 mm) Width: 23.75 in. (603 mm)

Drive Wheels: 10 in. (254 mm), solid (Middle)

Caster Wheels: 5.75 in. (146 mm), solid, rear-mounted 

Anti-tip Wheels: 5 in. (129 mm), solid, front-mounted 

Anti-tip wheels can help prevent the wheelchair from tipping backwards. A caster is a non-powered wheel that is designed to be fitted to the bottom of a bigger object and used to move it.

## Calucate the Torque

$$
Torque = Wheel Radius * Mass * gravity * sin(slope) 
$$
$$
(Unit: N*m)
$$
![wheelchair)render](/images/Wheel_Chair_Render.gif)

