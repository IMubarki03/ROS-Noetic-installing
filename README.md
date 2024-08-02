# ROS Noetic installing
## Introduction
_ROS Noetic_ is a middleware(_middleware_ is the software layer between operating system and applicatiolns), the 13th release of the Robot Operating System (ROS), a flexible framework for writing robot software.

![image](https://github.com/user-attachments/assets/26734206-9bec-45c5-8227-606c4012d95f)

ROS Noetic is specifically designed to work with Ubuntu 20.04 (Focal Fossa) and is the last release of ROS 1, as the focus has shifted towards ROS 2. Some key features of ROS Noetic include:

1. **Compatibility**
2. **Long-Term Support**(it will be supported until May 2025)
3. **Upgrades and Improvements**
4. **Community and Ecosystem**

## Procedure
**Step1:** As we need Linux operating system, and must of us have Windows operating system installed on our laptops, we will need something called "Virtual Box Machine(VM)" to install the Linux on it.<br>

**Step2:** After that, we will install the Linux Ubuntu 20.04 Focal version to set it up in the VM.<br>

**Step3:** Lastely, we will install the ROS Noetic on the Ubuntu and run it.<br>

![image](https://github.com/user-attachments/assets/a25ac080-7db8-4b0c-8fd5-b09692f5d33f)


## Virtual Box Machine
1. Download the latest version of VM, via the link:<br>
https://www.virtualbox.org/wiki/Downloads<br>
2. do the setup and follow the steps.
## Ubuntu 20.04 Focal
1. Here, you can download either _Ubuntu 20.04_ or _Ubuntu 20.04 mate_. I highely recommend downloading the main version "_Ubuntu 20.04_", click the link:<br> https://releases.ubuntu.com/20.04/ 
2. Follow the steps on the next Youtube video:<br>
https://youtu.be/hYaCCpvjsEY?si=ZiAYB-mKulNLfXb7
## ROS Noetic
1. Go to the website:<br>
https://wiki.ros.org/noetic/Installation/Ubuntu<br>
and follow the steps by coping the command lines, and paste it in the "Terminal" as follows:<br>
- 1.2 Setup your sources.list<br>
- 1.3 Set up your keys<br>
<img width="450" alt="1 2" src="https://github.com/user-attachments/assets/5fada56e-eb32-4f64-a5d0-759b09666c70"><br><br>
- 1.4 Installation: execute "sudo apt update", then download the Desktop full-install as follows
<img width="476" alt="install" src="https://github.com/user-attachments/assets/b7840865-72fe-47ca-8678-c7aae72e5c51"><br><br>
- Then continue the "1.5 Environment setup" and the rest line commands.<br>
<img width="446" alt="python" src="https://github.com/user-attachments/assets/9db94f92-acf1-4923-b3d7-e2cb9d1e7a58"><br><br>
<img width="493" alt="last output" src="https://github.com/user-attachments/assets/999fa99d-1bed-40fb-ad5e-b566cbcce5e9"><br>
As we can see, ROS Noetic is running well.
