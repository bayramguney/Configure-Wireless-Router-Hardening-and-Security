# Configure-Wireless-Router-Hardening-and-Security
# 🔒 Wireless Router Security Configuration Lab

## 📌 Overview

This Cisco Packet Tracer lab demonstrates how to secure a home wireless network by configuring router administration settings, implementing WPA2 wireless security, creating an isolated guest network, connecting wireless clients and IoT devices, and verifying secure connectivity.

The project focuses on wireless network hardening, access control, and best practices for protecting home network infrastructure.

---

## 🎯 Objectives

- Configure basic wireless router security settings.
- Change default administrative credentials.
- Disable remote management.
- Configure secure wireless networks.
- Create and secure a guest wireless network.
- Connect wireless clients and IoT devices.
- Verify wireless connectivity.
- Prevent guest devices from accessing the internal network.

---

## 🛠️ Technologies Used

- Cisco Packet Tracer
- Wireless Router
- WPA2-Personal Security
- AES Encryption
- DHCP
- SSID Configuration
- Wireless Clients
- IoT Devices
- ICMP (Ping)
- TCP/IP Networking

---

## 🖥️ Lab Topology

The lab consists of:

- Home Wireless Router
- Home Office PC
- Home Laptop 1
- Home Laptop 2
- Home Webcam
- Home Siren
- Smart Home Doors
- Internet / Public Web Server

---

## 🔐 Security Configuration

### Router Hardening

- Changed default administrator password
- Disabled Remote Management
- Saved and verified new configuration

---

### Home Wireless Network

| Setting | Value |
|---------|-------|
| SSID | HomeNet |
| Security | WPA2-Personal |
| Encryption | AES |
| Passphrase | ciscorocks |

---

### Guest Wireless Network

| Setting | Value |
|---------|-------|
| SSID | GuestNet |
| Security | WPA2-Personal |
| Encryption | AES |
| Passphrase | guestpass |

Additional Security:

- Enabled Guest Profile
- Broadcast SSID Enabled
- Disabled guest access to local network
- Prevented communication between guest and home devices

---

## 💻 Wireless Client Configuration

### Home Laptop 1

- Connected to HomeNet
- Authenticated using WPA2
- Received IP address via DHCP
- Verified Internet connectivity

### Home Laptop 2

- Connected to GuestNet
- Authenticated using WPA2
- Received IP address via DHCP
- Verified Internet connectivity

---

## 🏠 IoT Device Configuration

Configured the following smart devices:

- Home Webcam
- Home Siren
- Smart Home Doors

Each device:

- Connected to HomeNet
- Configured for WPA2-PSK
- Used AES encryption
- Obtained IP address through DHCP

---

## ✅ Verification

Connectivity tests included:

- Successful connection to wireless networks
- DHCP IP address assignment
- Internet connectivity verification
- Ping testing
- Guest network isolation verification

### Before Isolation

Guest Laptop ➜ Home Laptop

✅ Ping Successful

### After Isolation

Guest Laptop ➜ Home Laptop

❌ Ping Failed

This confirms that guest devices are prevented from accessing the private home network.

---

## 🔍 Security Best Practices Implemented

- Changed default credentials
- Disabled remote administration
- Enabled WPA2-Personal security
- Used AES encryption
- Configured strong wireless passphrases
- Created separate guest network
- Enabled SSID broadcast
- Isolated guest devices from local network
- Verified secure connectivity

---

## 📈 Skills Demonstrated

- Wireless Network Security
- Router Administration
- WPA2 Configuration
- DHCP Configuration
- SSID Management
- Guest Network Isolation
- IoT Network Configuration
- Network Troubleshooting
- Connectivity Testing
- Cisco Packet Tracer

---

## 📸 Screenshots

Add screenshots here after completing the lab.
<img width="945" height="572" alt="image" src="https://github.com/user-attachments/assets/db9bfc0d-b54c-4179-afdc-7baba56142d3" />

Example:

```
images/
├── enviroment.png

```

---

## 📂 Repository Structure

```
Wireless-Router-Security-Lab/
│
├── Instructions-Configure-Wireless-Router-Hardening-and-Security.docx
├── README.md
└── images/
    ├── enviroment.png
    
```

---

## 🎓 Learning Outcomes

After completing this lab, I gained hands-on experience with:

- Securing wireless routers
- Implementing WPA2 wireless security
- Configuring secure SSIDs
- Managing wireless clients
- Connecting IoT devices securely
- Implementing guest network isolation
- Verifying network security through connectivity testing
- Applying wireless security best practices

---

## 🚀 Future Improvements

- Configure WPA3 security
- Enable MAC Address Filtering
- Configure Firewall Rules
- Implement Access Control Lists (ACLs)
- Configure VPN Remote Access
- Enable Network Monitoring
- Configure Intrusion Detection/Prevention

---

## 🏷️ Tags

`Cisco` `Packet Tracer` `Wireless Security` `Networking` `Cybersecurity` `WPA2` `DHCP` `IoT` `Router Configuration` `Home Network` `Guest Network` `AES Encryption`
