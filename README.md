# Inter-VLAN Routing - Cisco Packet Tracer Project

## 📚 Project Overview
This project demonstrates **Inter-VLAN Routing** using the **Router on a Stick** method in **Cisco Packet Tracer**. It allows devices in **different VLANs** to communicate using **router subinterfaces**.

---

## 🔧 Files in the Repository
| File                    | Description |
|------------------|----------------|
| `basic-intervlan.pkt` | Cisco Packet Tracer file with the full topology. |
| `vlan_config.txt` | All configuration commands applied to the switch and router. |
| `README.md` | Project documentation. |

---

## 🚀 How to Use
1. Open `basic-intervlan.pkt` in Cisco Packet Tracer.
2. Review `vlan_config.txt` to understand the configurations.
3. Use these commands to verify:
    - `show vlan brief` (on switch)
    - `show ip interface brief` (on router)
4. Test **ping** between devices in **different VLANs** to confirm Inter-VLAN communication is working.

---

## 🛠️ Key Concepts Covered
- VLAN creation and port assignment
- Trunk link configuration between switch and router
- Router subinterface creation for each VLAN
- Assigning IP addresses to subinterfaces
- Verification commands and testing with pings

---

## 📌 Commands Covered
- `vlan` creation and naming
- `switchport mode access` & `switchport access vlan`
- `switchport mode trunk`
- `interface g0/0.X` (router subinterfaces)
- `encapsulation dot1q`
- `ip address`
- `show vlan brief`
- `show ip interface brief`
- `wr` (save config)

---

## 📷 Topology Snapshot
*(You can add a screenshot if needed)*

---

## ✅ Ideal For
- Networking students
- Beginners learning Inter-VLAN Routing
- CCNA preparation

---

## ✨ Author
-Kaushalya Jayasekara
- Created as part of practical networking exercises.

---

