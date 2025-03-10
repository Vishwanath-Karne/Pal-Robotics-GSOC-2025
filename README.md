# Google Summer of Code 2025 – PAL Robotics Project Plan


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
We encourage applicants to **engage with the community early**, contribute to discussions, and refine their project proposals. A strong proposal includes **prior contributions**, a **clear understanding of the problem**, and a **well-thought-out implementation plan**.

### **Steps to Contact Mentors and Contribute Early**
1. **Join Discussions**: Engage in discussions on PAL Robotics' GitHub.
2. **Explore Open Issues**: Contribute to related open-source repositories.
3. **Reach Out to Mentors**: Discuss your ideas and get feedback.
4. **Prepare a Strong Proposal**: Follow GSoC's official proposal writing guide.

### **Tips for Writing a Successful Google Summer of Code Application**
1. **Follow GSoC’s Writing a Proposal Guidelines**: Read and adhere to the official [GSoC proposal writing guide](https://google.github.io/gsocguides/student/writing-a-proposal.html).
2. **Include Your GitHub Profile**: Provide a link to your GitHub to showcase your previous contributions.
3. **Point Us to Your Open Source Contributions**: Highlight any contributions you have made to open-source projects.
4. **Provide Contact Information**: Ensure we have a way to reach you for any communication regarding your application.
5. **Specify Your Technical Background**: Mention your programming skills, experience with relevant technologies, and any coursework you have taken.
6. **Describe Your Background in Robotics and ROS 2**: Provide insights into your experience and knowledge of robotics and ROS 2.
7. **Specify Your Project of Interest**: Clearly mention the project you are applying for and explain why you are interested in it.
8. **Explain Your Goals for GSoC**: Share what you hope to achieve and learn from your Google Summer of Code experience.
9. **Engage with Mentors**: Feel free to reach out to the project mentors on GitHub to discuss your ideas and seek guidance.

For further questions, please contact [Sai Kishor Kothakota](sai.kishor@pal-robotics.com).



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

## **Overview**

#### See below for a list of projects ideas for [Google Summer of Code 2025](https://summerofcode.withgoogle.com/programs/2025/organizations/pal-robotics).
#### The currently proposed projects are:

1. Payload Visualization and Metrics
2. ROS 2 Action Multiplexer (Action Mux)
3. RFID Simulation Plugin for Gazebo Harmonic
4. ROS 2 Control Ecosystem Visualization
5. ROS 2 Python-Launch LSP Server



## **Project Ideas Table**

| Project Name | Difficulty | Project Size | Description | Skills Required | Mentors |
|-------------|------------|-------------|-------------|----------------|---------|
| Payload Visualization & Metrics | Medium | 175 hours | Develop a ROS 2 tool to visualize robot payload capabilities | C++/Python, ROS 2, URDF, RViz, Rigid Body Dynamics | [Luca Marchionni](https://github.com/lucamarchionni) |
| ROS 2 Action Mux | Medium/Hard | 175 hours | Middleware tool for prioritizing multiple action servers in ROS 2 | C++, ROS 2 Basics | [Sai Kishor Kothakota](https://github.com/saikishor) |
| RFID Simulation for Gazebo Harmonic | Medium | 175 hours | Develop an RFID simulation plugin for Gazebo | C++, ROS 2, Gazebo, RFID Systems | [Oscar Martinez](https://github.com/OscarMrZ) |
| ROS 2 Control Ecosystem Visualization | Medium/Hard | 350 hours | Develop an RQT or web-based tool to visualize ROS 2 Control | Qt, JavaScript, ROS 2 Actions/Services | [Sai Kishor Kothakota](https://github.com/saikishor) |
| ROS2 Python-Launch LSP Server | Medium | 175 hours | Develop a Language Server Protocol (LSP) tool for analyzing ROS 2 launch files | Rust, ROS 2, LSP, AST | [Thomas Ung](https://github.com/tomkimsour) |

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
- [Luca Marchionni](https://github.com/lucamarchionni)  

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
- [Sai Kishor Kothakota](https://github.com/saikishor) 

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
- [Oscar Martinez](https://github.com/OscarMrZ)  

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
- [Sai Kishor Kothakota](https://github.com/saikishor) 

#### **Project Size & Difficulty**
- **350 hours**
- **Medium/Hard**

## 5. ROS 2 Python-Launch LSP Server

### **Summary**
Develop a **Language Server Protocol (LSP) tool** for analyzing **ROS 2 Python-based launch files**, improving code navigation, validation, and development efficiency.

### **Detailed Description**
- The ROS 2 launchfile system is responsible for managing the launch and configuration of multiple processes and nested launchfiles.
- Python launchfiles utilize **launch descriptions**, composed of ordered lists of **actions and action groups**.
- These descriptions often include **substitutions**, allowing for dynamic configuration, but making it difficult to track parameter usage and executable launches.
- Due to this complexity, **understanding and debugging ROS 2 launch files** before runtime is challenging.
- A **Language Server Protocol (LSP) tool** will address these issues by enabling **static analysis, error detection, and intelligent navigation**.
- This tool will assist developers in large-scale ROS 2 projects by providing:
  - **Go-to-definition** for navigating ROS 2 launch files.
  - **Code completion** for Actions and Substitutions.
  - **Find references** for improving traceability across files.
  - **Executable argument suggestions** for better configuration.
  - **Syntactic error diagnostics** to catch issues early.
  - **Pre-processing ROS 2 substitutions** for structured validation.

### **Expected Outcomes**
- A working **ROS 2 Python-Launch LSP server**.
- Features such as **go-to-definition, auto-completion, and reference tracking**.
- **Executable argument suggestions** for improved usability.
- **Error diagnostics** for syntax validation.
- **Comprehensive documentation** on how to integrate the tool with LSP-compatible editors (VS Code, Vim, etc.).

### **Relevant Skills**
- Rust
- ROS 2 Basics
- Familiarity with **LSP (Language Server Protocol)**
- **AST (Abstract Syntax Tree) Processing**

### **Possible Mentors**
- [Thomas Ung](https://github.com/tomkimsour) 

### **Project Size & Difficulty**
- **175 hours**
- **Medium**


