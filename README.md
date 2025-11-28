# Automated-Fire-Detection-and-Extinguishing
This is an embedded systems project done on the Nucleo board (LG476RG). The project is a fire detection system that will periodically sense the environment using two sensors, flame and smoke. Once a fire is present, the tasks will release a semaphore to alert the actuators. A buzzer will actively alert the user, a relay will control a water pump to spray water, and a servo motor will actively sweep at angles between 0 and 180 to extinguish the detected area. 
All components are coded and scheduled as tasks using FreeRTOS.
