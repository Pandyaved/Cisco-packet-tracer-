# 🌐 Cisco Packet Tracer — Network Simulation

**A network simulation project demonstrating packet transmission, routing configuration, and end-to-end connectivity between devices using Cisco Packet Tracer.**

> Built by [Ved Pandya](https://github.com/Pandyaved) | B.Tech Cyber Security | Parul University | CCNAv7 Certified

---

## 📌 About This Project

This project uses Cisco Packet Tracer to simulate real-world network scenarios. It demonstrates how routers forward packets between devices, how IP addressing works, and how routing protocols establish communication paths — core concepts from the CCNAv7 curriculum.

---

## 🔬 What Was Simulated

| Scenario | Description |
|----------|-------------|
| Packet Transmission | Data flow between two end devices via router |
| IP Addressing | Static IP configuration on all devices |
| Routing | Router configuration for inter-network communication |
| Connectivity Test | Ping tests to verify end-to-end communication |
| Network Topology | Star and point-to-point topologies |

---

## ⚙️ Tools Used

| Tool | Purpose |
|------|---------|
| Cisco Packet Tracer | Network simulation |
| Cisco IOS | Router/Switch configuration |
| CCNAv7 Knowledge | Networking fundamentals |

---

## 🖧 Network Topology

```
[PC-A] ──────── [Router] ──────── [PC-B]
192.168.1.1    192.168.1.254    192.168.2.1
               192.168.2.254
```

---

## 📋 Router Configuration Used

```bash
Router> enable
Router# configure terminal
Router(config)# interface GigabitEthernet0/0
Router(config-if)# ip address 192.168.1.254 255.255.255.0
Router(config-if)# no shutdown
Router(config-if)# exit
Router(config)# interface GigabitEthernet0/1
Router(config-if)# ip address 192.168.2.254 255.255.255.0
Router(config-if)# no shutdown
```

---

## ✅ Results

- Successfully transmitted packets between two devices on different networks
- Verified connectivity using `ping` command
- Demonstrated how routers forward packets based on routing tables
- Configured static IP addressing on all network devices

---

## 📁 Project Structure

```
Cisco-packet-tracer-/
├── topology/
│   └── network_simulation.pkt    ← Open in Cisco Packet Tracer
├── screenshots/
│   └── ping_success.png
├── configs/
│   └── router_config.txt
└── README.md
```

---

## 🎓 Skills Demonstrated

- Cisco IOS router configuration
- IP addressing and subnetting
- Static routing
- Network topology design
- End-to-end connectivity verification

---

## 📬 Connect

- GitHub: [github.com/Pandyaved](https://github.com/Pandyaved)
- LinkedIn: [linkedin.com/in/ved-pandya-2b32bb387](https://linkedin.com/in/ved-pandya-2b32bb387)
