---
title: Project Requirements
---

## Project Objective Overview

The objective of this project is to create a subterranean rover that uses a motor‑driven drilling system to penetrate the ground and collect samples from different subsurface environments. The rover will rely on a Hall effect sensor to detect variations in magnetic fields beneath the surface. These magnetic readings help the rover identify metallic objects or shifts in underground materials, allowing it to determine which areas are most promising for sampling.
The rover will also include a human‑machine interface that allows the operator to set operating conditions, monitor sensor feedback, and define routes for the rover to follow. In addition, a wireless communication system will enable the rover to receive commands and transmit data remotely, ensuring fully untethered operation during exploration.



## Table: Requirements

The tables below shows the minimum acceptable performance levels, target values, associated rover features, and stretch‑goal indicators for each requirement in the final subterranean rover design. It includes all major system constraints—such as power limits, drilling capability, sensor accuracy, wireless communication reliability, and human‑machine interface functionality—and ensures that every subsystem of the rover is represented so each team member has at least one key functional requirement tied to their module.

| Requirements  | Description | Feature | Target Measurement | Stretch Goal | 
|----|------|------|---|---|
| Sensor   | Rover will be equipped with Sensors for dirt composition and magnetism sensing   | Hall effect sensor inside Rover Container | sense magnetic fields |  no
|  Motor | Motors will be used to drill into ground     | Drill attached to Rover | Drills into different soil compositions |  no
|   Human Interface | Operator will be able to interact with Rover giving it driving and drilling instructions     | LCD display and command pad | Rover obeys different commands based on intruction |  no
|   Wirless Communication | Rover Will be able to recieve commands without wired connections     | Remote control | Rover follow commands of operator without being directly connected |  no
|    DriveTrain | Rover Will be able to drive in reverse    | Dual Motor Functionality | Rover Is able to drive backwards |  Yes
|   Ultrasonic | Rover will be able to sense distance from objects    |Ultrasonic sensor  |Rover will be able to avoid obstacles |  yes



## Table: Power Usage

| **Requirement Description** | **Measure of<br> Threshold** | **Target<br>Measure** |**Stretch<br>Requirement<br>(Y-N)**|
|-----------------------------| ----------------- | ----------------- | :-----: |
| Surface mounted, 3.3V switching power regulatore | 3.2 Volts | 3.3 Volts | No |
| Surface mounted microcontroller | 1 PIC or ESP | 8-bit PIC | No |
| Wireless Communication | Able to send or receive a Wi-Fi data | Send and receive Wi-Fi Data to MQTT | Yes |






## Team Member assignment

The table below shows what team Member will be responsible for what function of the Rover.

The mimnimum Funtionalities for our rover being:

* Human Interface 
* Sensor 
* Wireless Connection
* Motor

##

| **Team Member**          | **Assignment**                                                                                                                                |
| :---------------- | :---------------------------------------------------------------------------------------------------------------------------------------- |
| Terry Williams    |    Sensor                                |
| Keith Payne  |     Motor                |
| Vannessa Morgan |     Wireless connection                  |
| Charlie Klotz  | Human Interface |



## Features 

**Motor:** 

Our subterranean rover will need to drill into a variety of soil compositions to collect samples. This will be achieved using motor‑driven mechanisms that rotate the drill bit and extract material from beneath the surface 

**Wireless Connection:** 

The rover must be capable of receiving commands without any wired connection. To support this, it will include wireless communication capabilities that allow the operator to send movement instructions, adjust settings, and monitor rover status remotely.

**Sensor:**

The subterranean rover will use a Hall effect sensor to detect variations in magnetic fields beneath the surface. By measuring changes in magnetic flux, the sensor can identify the presence of metallic objects or shifts in subsurface materials. These readings help the rover determine areas of interest and guide its sampling decisions, ensuring it collects data from locations most likely to yield meaningful results.

**Human Interface:**
 
A human‑machine interface will be integrated to allow the operator to issue commands based on real‑time sensor readings. This interface will provide clear feedback about soil conditions, drilling progress, and rover status, enabling the user to make informed operational decisions.

