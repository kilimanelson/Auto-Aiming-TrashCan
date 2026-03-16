# 1. Auto-Aiming-TrashCan
AI-powered TrashCan that predicts the trajectory of incoming trash and automatically moves to catch it. Using computer vision with a camera and LiDAR, the system detects, tracks, and estimates the trash’s path in real time, allowing a motorized bin to position itself and intercept it.
## 2. Hardware Components

The following hardware components are used to build the **Auto-Aiming Trash Can** system.

### Core Computing

- **Raspberry Pi 5 Kit**
    <p align="center">
  <img src="Assets/Images/Raspberry%20Pi%205%20Kit.png" width="500">
</p>
    Includes the Raspberry Pi board, memory card, charger, and cooling fan.
    
Serves as the **main controller** and runs the computer vision and trajectory prediction algorithms.
    

### Perception System

- **Raspberry Pi Camera Module 3**
    <p align="center">
  <img src="Assets/Images/Raspberry%20Pi%20Camera%20Module%203.png" width="500">
</p>
Used for **computer vision** to detect and track the trash while it is in the air.
    
- **LiDAR Scanner**
   <p align="center">
  <img src="Assets/Images/LiDAR%20Scanner.png" width="500">
</p> 
Helps the system **measure distance and detect obstacles**, allowing the trash can to navigate safely and position itself correctly.
    

### Motion System

- **M3H256 Triple Motor Controller (Pololu)**
    
    Controls the motors that move the robot platform. This controller was selected because it provides the required three-channel output to independently manage each of the three **DC motors** on the robot's chassis.
    
- **Omni Wheels (Robot Chassis)**
    
    Used as the primary locomotion method because they allow the platform to **move smoothly in multiple directions**, improving positioning speed and accuracy.
    

### Cooling

- **Raspberry Pi Cooler**
    
    Maintains an optimal temperature for the Raspberry Pi during computation-heavy tasks, such as real-time vision processing.
    

### AI Acceleration

- **Raspberry Pi AI Kit**
    
    Provides hardware acceleration to improve the performance of machine learning models used for object detection and trajectory prediction.
    

### Mechanical Structure

- **Robot Chassis**
    
    Purchasing a pre-built chassis for the robot platform is recommended because it simplifies assembly and improves stability.
