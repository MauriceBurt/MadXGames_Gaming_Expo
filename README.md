<p align="center">
  <img src="https://raw.githubusercontent.com/MauriceBurt/Modular-Networks/main/Transparent_PNG.png" width="350"/>
</p>

# MadX Games – Gaming Expo Infrastructure Design

## 🎮 Overview

The audience came for the tournament.

Modular Networks engineered the experience behind it.

This project showcases a segmented gaming expo infrastructure designed for a large-scale esports and entertainment convention environment.

The design focuses on more than connectivity alone — emphasizing operational movement, controlled access, tournament stability, wireless segmentation, and layered security across a high-density public venue.

The environment simulates real-world event operations including:

- Guest wireless access
- Vendor payment systems
- VIP & competitor isolation
- Tournament infrastructure
- Staff coordination
- Security operations
- AV and stage production systems

---

## 🧭 Repository Structure

🔧 **[Configs](./Configs)**  
🗺️ **[Topology](./Topology)**  
📸 **[Screenshots](./Screenshots)**  
🏢 **[Floor Plan](./Floor_Plan)**  

---

## 🧩 Network Segmentation

The environment is segmented using VLANs to separate operational zones across the convention floor.

| VLAN | Purpose |
|------|---------|
| VLAN 10 | Guest Access |
| VLAN 20 | Security Operations |
| VLAN 30 | Vendor Access |
| VLAN 40 | VIP / Competitor Access |
| VLAN 50 | Employee Operations |
| VLAN 60 | Tournament Gaming Systems |
| VLAN 70 | Tournament & AV Infrastructure |

---

## 🔐 Security Design

The network uses ACL enforcement and access-layer protections to restrict unnecessary communication between environments.

### ACL Enforcement

Examples include:

- ❌ Guest users restricted from internal VLANs
- ❌ Vendors isolated from operational infrastructure
- ❌ Security segmented from VIP systems
- ✅ Employees permitted broader operational access
- ✅ Tournament systems isolated from public traffic

---

### Access Layer Security

Additional protections include:

- Port security enabled on active access ports
- Sticky MAC learning configured
- Unused interfaces administratively shut down
- Segmented wireless SSIDs for operational separation

---

## 🏟️ Infrastructure Zones

The venue includes:

- Main Tournament Stage
- Preliminary Battle Stations
- VIP Lounge
- Vendor Hall
- Employee Operations
- Security Checkpoints
- Tournament AV Infrastructure
- Public Guest Wireless Access

The floor plan was designed to reflect both logical segmentation and real-world movement throughout the venue.

---

## 🌐 Wireless Infrastructure

Dedicated wireless environments were created for:

- Guest attendees
- Employees
- Security teams
- Vendors
- VIP competitors
- AV / stage production systems

This allows operational traffic to remain isolated while maintaining usability throughout the event.

---

## 🛠️ Technologies Used

- Cisco Packet Tracer
- Cisco IOS CLI
- VLAN Segmentation
- Router-on-a-Stick (ROAS)
- DHCP
- ACL Enforcement
- Port Security
- Administrative Port Shutdown
- Wireless Segmentation
- Canva (Floor Plan Visualization)

---

## 🏢 Floor Plan

![Floor Plan](Floor_Plan/MadXGames_Floor_Overview.png)

---

## 🖼️ Screenshots

### Final Topology

![Topology](Screenshots/01_Final_Topology.png)

### DHCP Lease Validation

![DHCP](Screenshots/02_DHCP_Lease_Validation.png)

### Subinterface Verification

![Subinterfaces](Screenshots/03_Subinterface_Verification.png)

### ACL Restrictions

![ACL](Screenshots/04_ACL_Restriction.png)

### Port Security

![Port Security](Screenshots/05_Port_Security.png)

---

## 🎯 Outcome

This design demonstrates how Modular Networks approaches event infrastructure engineering through:

- Segmentation
- Operational awareness
- Layered security
- Controlled wireless access
- Tournament infrastructure protection
- Public venue traffic management

The focus extends beyond connectivity and into real-world event operations, crowd movement, restricted access control, and infrastructure protection within a high-density entertainment environment.

---

## 📦 Modular Networks

Part of the  
👉 [Modular Networks Design Library](https://github.com/MauriceBurt/Modular-Networks)

<p align="center">
  <img src="https://raw.githubusercontent.com/MauriceBurt/Modular-Networks/main/Transparent_PNG.png" width="350"/>
</p>
