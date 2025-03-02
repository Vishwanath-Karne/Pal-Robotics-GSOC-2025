# Google Summer of Code 2025 – PAL Robotics Project Plan
https://www.google.com/url?sa=i&url=https%3A%2F%2Fsummerofcode.withgoogle.com%2F&psig=AOvVaw1MTGqSuXLrOZcrZ-i4vHDe&ust=1740983534896000&source=images&cd=vfe&opi=89978449&ved=0CBQQjRxqFwoTCMCP8Kbj6osDFQAAAAAdAAAAABAE


### **Welcome to PAL Robotics!**
Welcome to PAL Robotics' Google Summer of Code (GSoC) 2025 project ideas page! We are excited to offer multiple robotics-related projects for students who are passionate about **robotics, ROS 2, control systems, and simulation technologies**.

### **Useful Links**
- [Google Summer of Code Official Page](https://summerofcode.withgoogle.com/)
- [GSoC Proposal Writing Guidelines](https://google.github.io/gsocguides/student/writing-a-proposal.html)
- [PAL Robotics GitHub](https://github.com/pal-robotics)
- [PAL Robotics Website](https://pal-robotics.com)

### **About PAL Robotics**
PAL Robotics specializes in **humanoid robots, mobile manipulators, and AI-driven robotics solutions**. We are an active contributor to open-source robotics and a strong supporter of **ROS (Robot Operating System)**.

## **Prerequisites**

### **What is PAL Robotics?**
PAL Robotics is a **leading robotics company** focused on designing robots for **industrial, research, and service applications**. Our robots are used worldwide in research labs and commercial settings.

### **Skills Needed for Different Projects**
Each project requires a different skill set, ranging from **C++ and Python** programming to **ROS 2 development, Gazebo simulation, and visualization tools**. The specific requirements for each project are listed in the table below.

## **How to Apply**

### **Encouragement for Applicants**
We encourage applicants to **engage with the community early**, contribute to discussions, and refine their project proposals. A strong proposal includes prior contributions, a clear understanding of the problem, and a well-thought-out implementation plan.

### **Steps to Contact Mentors and Contribute Early**
1. **Join Discussions**: Engage in discussions on PAL Robotics' GitHub.
2. **Explore Open Issues**: Contribute to related open-source repositories.
3. **Reach Out to Mentors**: Discuss your ideas and get feedback.
4. **Prepare a Strong Proposal**: Follow GSoC's official proposal writing guide.

## **Mentors**

### **List of Available Mentors**
- [Luca Marchionni](https://github.com/lucamarchionni)  
- [Sai Kishor Kothakota](https://github.com/saikishor)  
- [Oscar Martinez](https://github.com/OscarMrZ)  
- [Thomas Ung](https://github.com/tomkimsour)  

### **Guidelines for Communication**
- Use **public forums** for discussions.
- Avoid sending private messages unless absolutely necessary.
- Be **respectful and professional** in communications.

## **Collaborations**

### **Related Open-Source Projects**
- **ROS 2**: Core robotics middleware.
- **Gazebo Harmonic**: Advanced robotics simulation environment.
- **Rigid Body Dynamics Libraries**: Pinocchio, RBDL, etc.

## **Project Ideas Table**

| Project Name | Difficulty | Project Size | Description | Skills Required | Mentors |
|-------------|------------|-------------|-------------|----------------|---------|
| Payload Visualization & Metrics | Medium | 175 hours | Develop a ROS 2 tool to visualize robot payload capabilities | C++/Python, ROS 2, URDF, RViz, Rigid Body Dynamics | Luca Marchionni |
| ROS 2 Action Mux | Medium/Hard | 175 hours | Middleware tool for prioritizing multiple action servers in ROS 2 | C++, ROS 2 Basics | Sai Kishor Kothakota |
| RFID Simulation for Gazebo Harmonic | Medium | 175 hours | Develop an RFID simulation plugin for Gazebo | C++, ROS 2, Gazebo, RFID Systems | Oscar Martinez |
| ROS 2 Control Ecosystem Visualization | Medium/Hard | 350 hours | Develop an RQT or web-based tool to visualize ROS 2 Control | Qt, JavaScript, ROS 2 Actions/Services | Sai Kishor Kothakota |

## **Detailed Project Descriptions**

### **1. Payload Visualization and Metrics**
#### **Summary**
This project aims to create a **ROS 2-based software tool** for assessing and visualizing the payload capacity of a robot, considering its kinematic and dynamic constraints.

#### **Detailed Description**
- Parses robot's **URDF** to extract kinematic data.
- Computes payload constraints based on actuation limits.
- Provides **visual representations** of payload capabilities.
- Develops a **joint requirement estimator** for torque, power, and stiffness.

#### **Expected Outcomes**
- Payload visualization tool with **RViz integration**.
- Custom RViz plugin for **dynamic payload display**.
- Documentation with **example use cases**.

#### **Relevant Skills**
- C++/Python, ROS 2, URDF, RViz Plugin Development, Rigid Body Dynamics.

#### **Possible Mentors**
- Luca Marchionni

#### **Project Size & Difficulty**
- **175 hours**
- **Medium**

---

### **2. ROS 2 Action Multiplexer (Action Mux)**
#### **Summary**
A middleware tool to handle multiple ROS 2 action servers with a **priority-based task management system**.

#### **Detailed Description**
- Develops a **multiplexer** to prioritize actions dynamically.
- Implements **preemption mechanisms** for high-priority actions.
- Provides a **user-friendly API** for integration with ROS 2.

#### **Expected Outcomes**
- A working **action multiplexer** with ROS 2 integration.
- Support for **multiple action message types**.
- Automated tests for **preemption and goal acceptance**.

#### **Relevant Skills**
- C++, ROS 2 Basics.

#### **Possible Mentors**
- Sai Kishor Kothakota

#### **Project Size & Difficulty**
- **175 hours**
- **Medium/Hard**

---

### **3. RFID Simulation Plugin for Gazebo Harmonic**
#### **Summary**
Develop an RFID simulation plugin to **support object tracking and localization** in Gazebo Harmonic.

#### **Detailed Description**
- Models RFID readers and tags using **physical wave transmission (Friis equation)**.
- Simulates real-world **noise, interference, and attenuation**.
- Validates the plugin with **PAL Robotics' open-source simulation packages**.

#### **Expected Outcomes**
- **Configurable RFID sensor plugin** for Gazebo.
- ROS 2 interface for **publishing detection messages**.
- Documentation and **API reference**.

#### **Relevant Skills**
- C++, ROS 2, Gazebo Plugin Development, RFID Systems.

#### **Possible Mentors**
- Oscar Martinez

#### **Project Size & Difficulty**
- **175 hours**
- **Medium**

---

### **4. ROS 2 Control Ecosystem Visualization**
#### **Summary**
Develop a visualization tool to **monitor and analyze ROS 2 Control systems** in real time.

#### **Detailed Description**
- Displays **controller states, hardware interfaces, and data flow**.
- Implements **filtering and customization** options.
- Provides a **user-friendly interface** as an RQT plugin or web-based tool.

#### **Expected Outcomes**
- Interactive visualization of **ROS 2 Control systems**.
- Seamless integration with **existing ROS 2 frameworks**.
- Performance debugging tools.

#### **Relevant Skills**
- Qt, JavaScript, ROS 2 Actions/Services.

#### **Possible Mentors**
- Sai Kishor Kothakota

#### **Project Size & Difficulty**
- **350 hours**
- **Medium/Hard**

