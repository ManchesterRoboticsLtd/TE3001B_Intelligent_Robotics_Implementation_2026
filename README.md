<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/ManchesterRoboticsLtd/MR3001B_Design_and_Development_of_Robots_I/blob/main/Misc/Logos/Logotipo%20Vertical%20Bco_Transparente.png">
  <source media="(prefers-color-scheme: light)" srcset="https://github.com/ManchesterRoboticsLtd/MR3001B_Design_and_Development_of_Robots_I/blob/main/Misc/Logos/Logotipo%20Vertical%20Azul%20transparente.png">
  <img alt="Shows ITESM logo in black or white." width="160" align="right">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/ManchesterRoboticsLtd/MR3001B_Design_and_Development_of_Robots_I/blob/main/Misc/Logos/MCR2_Logo_White.png">
  <source media="(prefers-color-scheme: light)" srcset="https://github.com/ManchesterRoboticsLtd/MR3001B_Design_and_Development_of_Robots_I/blob/main/Misc/Logos/MCR2_Logo_Black.png">
  <img alt="Shows MCR2 logo in black or white." width="150" align="right">
</picture>


---

---
# TE3001B: Intelligent Robotics Implementation 2025

  ## Introduction
* This course, developed by Manchester Robotics ltd. (MCR2), introduces the basic concepts and general knowledge of the ROS environment to the user.
* This course is divided into five sessions, carefully designed for the user to learn about the different aspects of ROS2, from topics and messages to control and simulation using ROS2.
* This course will be based on challenges to make the student aware of ROS basics and ROS communication with hardware.


   
## General Information
*	MCR2 Person in Charge: Dr Mario Martinez
*	Tecnológico de Monterrey Person in Charge: Dr Luis Alberto Munoz
*	Duration 5 Weeks.
*	Starting: 10th Feb

## Zoom:
  
Topic: TE3001B

Meeting ID: 822 7617 8487

Passcode: MCR2


## Live sessions (Recordings)

[Live Sessions](https://tecmx-my.sharepoint.com/:f:/g/personal/mario_mtz_tec_mx/IgCoSC5UIkUQQLU1u6mo7qbUAbG4zfJ7rH5xofBRQWdZpgs?e=Kt1mjK)
    
## General Requirements
General requirements. Please be aware that a set of requirements specific to each session will be shown in each session subsection (Some items may be repeated).
* Computer with access to Teams (online classes).
* Computer with Ubuntu 22.04 and ROS2 Humble.
* MCR2 Virtual Machine
* Knowledge of ROS.
* Knowledge of Windows. 
* Basic knowledge of Ubuntu (recommended).
* Basic understanding of robotics (recommended).
* Access to the required hardware (Hardware section).

## Required Hardware (Session 3 onwards)
![image](https://github.com/user-attachments/assets/12766789-6044-4b48-bdf6-49275491b61c)


## Sessions

### Session 1: Fundamentals and control with ROS
  This session covers the basics of ROS.

  #### Topics:
 * Who are we? Introduction to MCR2.
 * Introduction to Robotics
 * Introduction to ROS
 * Overview of the ROS Environment
 * Topics, Messages, ROS.
 * Launch Files


  #### Activities

   * ##### Activity 1: ROS Nodes
     Talker

   * ##### Activity 2: ROS Nodes
     Listener

   * ##### Activity 3: ROS Nodes
     Launch Files

  #### Mini-challenge 1
    
   * Generate a node that sends a signal and another to process the signal.
       
  
  **Requirements:** 
  
  Computer with access to Zoom, Ubuntu 22.04 and ROS Humble Installed (Full installation) or  MCR2 Virtual Machine.

### Session 2: ROS Practicalities
  This session covers the topic of ROS in more depth.
  #### Topics:
 * ROS Namespaces
 * ROS Parameters
 * ROS Parameter Callbacks
 * ROS Services


  #### Activities

   * ##### Activity 1: Namespaces
        Generate Namespaces for individual nodes
   * ##### Activity 1.1: Namespaces2
        Generate Namespaces for groups of nodes
   * ##### Activity 2: Parameters (Launch File)
        Define Parameters for a node and set them using the launch file.
   * ##### Activity 2.1: Parameter Callbacks
        Use callbacks to change parameters at runtime.
   * ##### Activity 2.2: Parameter Files (Optional)
        Use YAML Files to define parameters.
   * ##### Activity 3: Services (Optional)
        Use Services to enable/disable nodes.

  #### Mini-challenge 2
    
   * Make a PID Controller for a simulated motor.

  **Requirements:** 

  Computer with access to Zoom, Ubuntu 22.04 and ROS Humble Installed (Full installation) or  MCR2 Virtual Machine.

  ### Session 3: Micro ROS
  This session covers micro-ros.
  #### Topics:
 * Micro ROS Basics
 * Micro ROS Program Structure
 * Executors
 * Micro ros transports (Optional)
 * WiFi (Optional)


  #### Activities

   * ##### Activity 1: Publisher
     Make a simple uros Publisher
   * ##### Activity 1.2: Publisher w/recconection
     Make a simple publisher w/recconection
   * ##### Activity 2: Subscriber
     Make a simple Subscriber
   * ##### Activity 2.2: Subscriber w/recconection
     Make a simple Subscriber w/recconection
   * ##### Activity 3: Large Project Handling (Optional)
     Publisher/Subscriber with interrupts
   * ##### Activity 4: WiFi Connection (Optional)
     WiFi AP with ESP32
    
  #### Mini-challenge 3
    
   * Motor Speed regulation using ROS.
        
  **Requirements:** 
  
  Computer with access to Zoom, Ubuntu 22.04 and ROS Humble Installed (Full installation), Hardware in Hardware section.


  ### Session 4: ROS Data Acquisition and Control
  This session covers control and dataacquisition modes in ROS
  #### Topics:
 * Encoder Basic Theory
 * Interrupts (Optional)
 * Control Theory
 * QoS
 * Real-time (Optional)


  #### Activities

   * ##### Activity 1: QoS
   QoS Connections

  #### Mini-challenge 4
    
   * Acquire data from the encoders using ESP32.
        
  **Requirements:** 
  
  Computer with access to Zoom, Ubuntu 22.04 and ROS Humble Installed (Full installation).

 ### Session 5: Final Challenge

  #### Final Challenge
    
   * Final Challenge Presentation
        
  **Requirements:** 

  Computer with access to Zoom, Ubuntu 22.04 and ROS Humble Installed (Full installation).


  ## Useful Links: 
  #### Ubuntu
   * [Ubuntu Installation](https://ubuntu.com/tutorials/install-ubuntu-desktop#1-overview)
  
  #### ROS
   * [ROS Installation](https://docs.ros.org/en/humble/Installation/Ubuntu-Install-Debians.html)
   * [ROS book](https://github.com/fmrico/book_ros2)
   * [ROS Packages](https://docs.ros.org/en/humble/Tutorials/Beginner-Client-Libraries/Creating-Your-First-ROS2-Package.html)
   * [ROS Workspace](https://docs.ros.org/en/humble/Tutorials/Beginner-Client-Libraries/Creating-A-Workspace/Creating-A-Workspace.html)
   * [ROS Nodes](https://docs.ros.org/en/humble/Tutorials/Beginner-CLI-Tools/Understanding-ROS2-Nodes/Understanding-ROS2-Nodes.html)
   * [Topics](https://docs.ros.org/en/humble/Tutorials/Beginner-CLI-Tools/Understanding-ROS2-Topics/Understanding-ROS2-Topics.html)
   * [Publisher and Subscribers](https://docs.ros.org/en/humble/Tutorials/Beginner-Client-Libraries/Writing-A-Simple-Py-Publisher-And-Subscriber.html)
   * [ROS Launch](https://docs.ros.org/en/humble/How-To-Guides/Launch-file-different-formats.html)
   * [ROS Custom Interfaces](https://docs.ros.org/en/humble/Tutorials/Beginner-Client-Libraries/Custom-ROS2-Interfaces.html)
   * [Parameters](https://docs.ros.org/en/humble/Tutorials/Beginner-Client-Libraries/Using-Parameters-In-A-Class-Python.html)

  #### Embedded Systems
   * [micro-ROS](https://micro.ros.org/)
   * [micro-ROS-Arduino](https://github.com/micro-ROS/micro_ros_arduino)
   * [DC Motor](https://en.wikipedia.org/wiki/DC_motor)
   * [H-Bridge](https://www.youtube.com/watch?v=fVgnUWIWzZ8&ab_channel=NorthwesternRobotics)
   * [Rotary Encoder](https://en.wikipedia.org/wiki/Rotary_encoder)
   * [Rotary Encoder](https://www.encoder.com/article-what-is-an-encoder)
   * [ESP32 Tutorials](https://randomnerdtutorials.com/projects-esp32/)
   * [Interrupts on ESP32](https://lastminuteengineers.com/handling-esp32-gpio-interrupts-tutorial/)
  
  #### Virtual Machine: 
   * [VM Ware](https://softwareupdate.vmware.com/cds/vmw-desktop/player/17.6.2/24409262/)
   * [ROS Preinstalled VM](https://manchesterrobotics-my.sharepoint.com/:u:/g/personal/mario_mtz_manchester-robotics_com/EWcRInLzqDZNpxqWlH3X0sQBGXgbTSj9Qp1VX7O_sGy4zQ?e=sIq2xd)

  #### Resources
   * [Introduction to Autonomous Mobile Robots](https://ieeexplore.ieee.org/book/6267528)
   * [PID Control](https://ieeexplore.ieee.org/document/1453566)
   * [Closed Loop Control](https://www.electronics-tutorials.ws/systems/closed-loop-system.html)
   * [Nonlineraities and robustness](https://ieeexplore.ieee.org/document/8603065)
   * [Open loop control Tutorial](https://www.electronics-tutorials.ws/systems/open-loop-system.html)
   * [Open Loop Control Tutorial](https://www.electronicshub.org/open-loop-system/)
   * [Open Loop Control Book](https://eng.libretexts.org/Bookshelves/Electrical_Engineering/Signal_Processing_and_Modeling/Introduction_to_Linear_Time-Invariant_Dynamic_Systems_for_Students_of_Engineering_(Hallauer)/14%3A_Introduction_to_Feedback_Control/14.02%3A_Definitions_and_Examples_of_Open-Loop_Control_Systems)
     
  
  ---
## Declaration

At Manchester Robotics, we firmly believe that innovation is driven by change, so we have made it our mission to change access to educational robotics. We hope you enjoy our products and support this revolution.

So, from the team at MCR2, we would like to say 

                                                          Thank you!
                                                   {Learn, Create, Innovate};
---
  ## Disclaimer
 *THE PIECES, IMAGES, VIDEOS, DOCUMENTATION, ETC. SHOWN HERE ARE FOR INFORMATIVE PURPOSES ONLY. THE DESIGN IS PROPRIETARY AND CONFIDENTIAL TO MANCHESTER ROBOTICS LTD. (MCR2). THE INFORMATION, CODE, SIMULATORS, DRAWINGS, VIDEOS PRESENTATIONS ETC. CONTAINED IN THIS REPOSITORY IS THE SOLE PROPERTY OF MANCHESTER ROBOTICS LTD. ANY REPRODUCTION OR USAGE IN PART OR AS A WHOLE WITHOUT THE WRITTEN PERMISSION OF MANCHESTER ROBOTICS LTD. IS STRICTLY PROHIBITED*

*THIS WEBSITE MAY CONTAIN LINKS TO OTHER WEBSITES OR CONTENT BELONGING TO OR ORIGINATING FROM THIRD PARTIES OR LINKS TO WEBSITES AND FEATURES IN BANNERS OR OTHER ADVERTISING. SUCH EXTERNAL LINKS ARE NOT INVESTIGATED, MONITORED, OR CHECKED FOR ACCURACY, ADEQUACY, VALIDITY, RELIABILITY, AVAILABILITY OR COMPLETENESS BY US.*

*WE DO NOT WARRANT, ENDORSE, GUARANTEE, OR ASSUME RESPONSIBILITY FOR THE ACCURACY OR RELIABILITY OF ANY INFORMATION OFFERED BY THIRD-PARTY WEBSITES LINKED THROUGH THE SITE OR ANY WEBSITE OR FEATURE LINKED IN ANY BANNER OR OTHER ADVERTISING.*
  


                                                   


