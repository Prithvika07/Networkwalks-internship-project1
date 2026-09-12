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

## 💾 Backup and Recovery Setup

A backup point was created for the Kali Linux virtual machine to provide a recovery option during cybersecurity lab activities.

### Backup Steps

1. Complete the basic Kali Linux configuration.
2. Shut down the virtual machine safely.
3. Create a snapshot of the configured Kali Linux virtual machine in VirtualBox.
4. Verify that the snapshot was created successfully.
5. Use the snapshot as a recovery point if the virtual machine configuration needs to be restored.

The snapshot helps maintain a stable version of the lab environment while experimenting with different cybersecurity tools and configurations.
