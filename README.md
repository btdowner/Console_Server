[← Back to Home](https://github.com/btdowner)

<img src="20250525_061306.jpg" alt="Network Rack Setup" width="600"/>

---

## 📘 Project Overview

To support my CCNA studies and deepen my understanding of network device management, I built a custom console server using a Raspberry Pi, powered USB hub, APC PDU, and an Alexa smart plug. My Cisco lab and work office are located in a building behind my house, while most of my studying takes place indoors. This setup allows **remote serial access** to multiple Cisco routers, switches, and the APC PDU — offering real-world hands-on experience.

> While console access is usually secondary to SSH, this project gave me valuable exposure to the underlying equipment and was a genuinely fun challenge to set up.

---

## 🛠️ Tools & Technologies

- Raspberry Pi 2B running Raspberry Pi OS  
- `ser2net` for serial-to-network communication  
- Cisco 2851 (x2), 2950, 2960, and 3560 (x2) switches  
- APC PDU for remote power control  
- Powered USB hub with multiple Cisco console cables  
- pfSense router for VLAN segmentation and DHCP reservations  

<img src="20250525_061752.jpg" alt="Raspberry Pi with USB Console Hub" width="500"/>

---

## ✨ Key Features

- Remote SSH/Telnet access to all devices from desktop or laptop  
- Reliable access via **DHCP reservation**  
- Clean device labeling in `ser2net.conf`  
- Power control managed through a smart plug and APC PDU  
- Efficient, centralized management from a Raspberry Pi interface  

<img src="pic.jpg" alt="ser2net Configuration Screenshot" width="600"/>

---

## 🔧 Skills Demonstrated

- Cisco CLI configuration & troubleshooting  
- Linux service management and config editing  
- Serial communication using USB/RS232  
- Network design: VLANs, IP addressing, DHCP reservations  
- Home lab infrastructure planning & remote access  

---

## 📈 Next Steps

- Add **two WIC-2T serial interface cards** to increase router connectivity  
- Create a **smart serial crossover cable** to simulate WAN links  
- Continue building **CCNA labs** and explore **CCNP-level topologies**  
- Potential future automation (power cycle, device discovery, logging)
---

## 🔗 LinkedIn
💼 [Connect with me on LinkedIn](https://www.linkedin.com/in/brandonthomasdowner)

<style>
  /* Target the main containers used by Architect */
  .container-lg, .main-content, .wrapper, section {
    max-width: 95% !important;
    width: 95% !important;
    margin: 0 auto !important;
    padding: 2rem !important;
  }

  /* Make sure code blocks (Cisco configs) fill the new width */
  pre, .highlight {
    width: 100% !important;
    overflow-x: auto !important;
  }
</style>
