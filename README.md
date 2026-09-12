## 🔐 About the Project

This project involves creating a **virtual cybersecurity laboratory using Kali Linux and Oracle VirtualBox**. The lab provides a dedicated environment for learning and practicing cybersecurity concepts without affecting the main computer system.

Kali Linux is configured as a virtual machine and connected to a virtual network through VirtualBox. The environment can be used to explore security tools, understand network communication, perform basic security testing, and carry out future cybersecurity exercises in a controlled setup.

The main focus of this project is to understand the process of building, configuring, and validating a functional cybersecurity lab environment.

## 🎯 Lab Goals

The main goals of this project are:

- To set up a virtual cybersecurity laboratory using Kali Linux.
- To understand the basic configuration of a virtual machine using VirtualBox.
- To configure networking between the host system and the Kali Linux virtual machine.
- To learn basic Linux and network configuration commands.
- To verify network connectivity and internet access from Kali Linux.
- To create a safe and controlled environment for practicing cybersecurity concepts.
- To document the complete lab setup and configuration process.

## 🖥️ Cybersecurity Lab Environment

The cybersecurity lab was created using **Oracle VirtualBox** and **Kali Linux**. Kali Linux is installed as a virtual machine, allowing cybersecurity activities to be performed in a separate and controlled environment.

The virtual lab provides a safe setup for learning and practicing cybersecurity concepts without directly affecting the main operating system.

### Lab Components

- **Host System:** Main computer
- **Virtualization Software:** Oracle VirtualBox
- **Guest Operating System:** Kali Linux
- **Network:** Virtual network configured through VirtualBox
- **Purpose:** Cybersecurity learning, network testing, and security practice

## 🌐 Virtual Machine and Network Details

The cybersecurity lab uses Kali Linux as a virtual machine inside Oracle VirtualBox. The virtual machine is configured with suitable system resources and connected to a VirtualBox virtual network for communication and testing.

### Virtual Machine Configuration

| Component | Configuration |
|---|---|
| Virtualization Software | Oracle VirtualBox |
| Guest Operating System | Kali Linux |
| Virtual Machine Type | Linux Virtual Machine |
| Network Configuration | VirtualBox Virtual Network |
| Network Mode | NAT Network |
| Purpose | Cybersecurity learning and network testing |

The NAT Network configuration allows the Kali Linux virtual machine to communicate through the configured virtual network while maintaining a controlled laboratory environment.

## 🐧 Kali Linux Installation

Kali Linux was installed as a virtual machine using Oracle VirtualBox. The installation provides a dedicated Linux-based environment for learning cybersecurity concepts and working with security tools.

### Installation Steps

1. Open Oracle VirtualBox.
2. Create or import the Kali Linux virtual machine.
3. Configure the required virtual machine resources.
4. Start the Kali Linux virtual machine.
5. Complete the Kali Linux installation and initial setup.
6. Log in to the Kali Linux desktop.
7. Verify that the operating system is working correctly.
8. Prepare the virtual machine for network configuration and cybersecurity exercises.

## 🌐 Virtual Network Configuration

The Kali Linux virtual machine was connected to a virtual network using the networking options available in Oracle VirtualBox. The network configuration allows the virtual machine to communicate with other systems in the laboratory environment and access required network services.

### Network Configuration Steps

1. Open the Kali Linux virtual machine settings in VirtualBox.
2. Open the **Network** section.
3. Configure the network adapter.
4. Select **NAT Network** as the network mode.
5. Connect the Kali Linux virtual machine to the configured virtual network.
6. Start Kali Linux and check the network interface.
7. Configure the required network settings.
8. Test the connection to verify that the network is working correctly.

## 🌐 Virtual Network Configuration

The Kali Linux virtual machine was connected to a virtual network using the networking options available in Oracle VirtualBox. The network configuration allows the virtual machine to communicate with other systems in the laboratory environment and access required network services.

### Network Configuration Steps

1. Open the Kali Linux virtual machine settings in VirtualBox.
2. Open the **Network** section.
3. Configure the network adapter.
4. Select **NAT Network** as the network mode.
5. Connect the Kali Linux virtual machine to the configured virtual network.
6. Start Kali Linux and check the network interface.
7. Configure the required network settings.
8. Test the connection to verify that the network is working correctly.

## 🔍 Network Testing and Validation

After configuring the Kali Linux network, connectivity was tested to make sure the virtual machine could communicate correctly with the network.

### Testing Performed

1. Checked the network interface and IP address.
2. Verified the default gateway configuration.
3. Tested connectivity using the `ping` command.
4. Checked DNS resolution.
5. Verified internet connectivity from Kali Linux.
6. Confirmed that the network configuration was working correctly.

### Example Commands

```bash
ip addr
ip route
ping 8.8.8.8
ping google.com
```

These tests helped confirm that the Kali Linux virtual machine was properly connected to the configured virtual network.

## 💾 Backup and Recovery Setup

A backup point was created for the Kali Linux virtual machine to provide a recovery option during cybersecurity lab activities.

### Backup Steps

1. Complete the basic Kali Linux configuration.
2. Shut down the virtual machine safely.
3. Create a snapshot of the configured Kali Linux virtual machine in VirtualBox.
4. Verify that the snapshot was created successfully.
5. Use the snapshot as a recovery point if the virtual machine configuration needs to be restored.

The snapshot helps maintain a stable version of the lab environment while experimenting with different cybersecurity tools and configurations.

## Issues Faced During Setup

During the initial setup of the cybersecurity lab environment, I faced a few challenges while configuring Kali Linux and VirtualBox.

### 1. Understanding the Kali Linux File

Initially, I was unsure which downloaded Kali Linux file needed to be used for the VirtualBox setup. I learned that Kali Linux can be distributed in different formats, such as ISO images and compressed archives, depending on the installation method.

### 2. Extracting the Kali Linux Archive

The Kali Linux VirtualBox package was provided as a compressed archive. I initially needed to understand why the file had to be extracted before using it. Using 7-Zip, I extracted the archive and obtained the required VirtualBox files.

### 3. Understanding Virtual Machines

As a beginner, I initially found the concept of a Virtual Machine (VM) confusing. I learned that a VM allows an operating system such as Kali Linux to run inside my main computer without replacing the existing operating system.

### 4. Understanding NAT Networking

Another challenge was understanding NAT (Network Address Translation) and how it works with VirtualBox. I learned that NAT allows a virtual machine to communicate with external networks through the host computer's network connection.

### 5. Configuring the VirtualBox NAT Network

I also needed to understand how to configure a NAT Network for communication between virtual machines. The selected private network was:

`10.0.0.0/24`

This provides a private network in which the virtual machines can communicate while using NAT for external network access.

### Resolution

By researching the VirtualBox networking concepts and understanding the purpose of each configuration step, I was able to complete the initial lab setup and better understand virtualization and networking fundamentals.

### 6. Registering and Unregistering the Virtual Machine

During the VirtualBox setup, I also encountered confusion regarding the registration and unregistration of the virtual machine.

I learned that VirtualBox keeps track of virtual machines through its configuration files. When a VM is manually moved or imported, it may need to be registered with VirtualBox before it appears correctly in the VirtualBox Manager.

I also learned about the difference between **unregistering** a VM and deleting its files. Unregistering removes the VM from VirtualBox's list, while the actual virtual disk and related files may still remain on the system.

After understanding the registration process and checking the VM configuration, I was able to properly manage the Kali Linux virtual machine in VirtualBox.

## 📚 Skills and Concepts Gained

This project helped in developing practical knowledge of Linux, virtualization, and basic networking concepts.

### Key Learning Outcomes

- Learned how to create and manage a virtual machine using VirtualBox.
- Gained experience with Kali Linux installation and configuration.
- Understood basic Linux networking commands.
- Learned how to configure a virtual network using NAT Network.
- Learned how to check IP addresses, routes, and network connectivity.
- Understood the importance of testing network configuration.
- Learned how to create and use virtual machine snapshots.
- Gained practical experience in setting up a controlled cybersecurity laboratory.

## 🔐 Responsible Security Practice

This cybersecurity lab is intended for **educational purposes and authorized security testing only**.

All network testing and cybersecurity activities should be performed only on systems, virtual machines, and networks where permission has been given.

The isolated virtual lab provides a controlled environment for learning cybersecurity concepts while reducing the risk of affecting unauthorized systems.

### Key Practices

- Perform security testing only with proper authorization.
- Use the lab environment for educational and testing purposes.
- Do not scan, attack, or access systems without permission.
- Protect sensitive information and credentials.
- Follow ethical and responsible cybersecurity practices.

## 🛠️ Software Used

The following software and technologies were used to create and configure the cybersecurity laboratory:

| Software / Technology | Purpose |
|---|---|
| Oracle VirtualBox | Creating and managing the virtual machine |
| Kali Linux | Cybersecurity-focused operating system and testing environment |
| Linux Terminal | Performing system and network configuration |
| VirtualBox NAT Network | Providing virtual network connectivity |
