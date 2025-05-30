# Windows Firewall Task – Cybersecurity Lab

## 🔐 Task 4: Setup and Use a Firewall on Windows

### 🎯 Objective
Configure and test basic firewall rules to allow or block traffic using **Windows Defender Firewall**.

---

### 🛠️ Tools Used
- Windows Defender Firewall with Advanced Security
- Telnet client (Windows Feature)

---

### 📝 Steps Performed

1. Opened Windows Defender Firewall.
2. Viewed existing inbound and outbound rules.
3. Added an inbound rule to **block TCP traffic on Port 23** (Telnet).
4. Tested the rule using the `telnet` command.
5. Created a rule to **allow Port 22 (SSH)** as a simulation.
6. Deleted the test rule to restore original state.
7. Documented steps with screenshots.
8. Summarized firewall filtering behavior.

---

### 📂 Files Included

- `Add_Rule/` – Folder containing step-by-step screenshots
- `Rules_txt/` – Exported list of existing firewall rules [inbound and outbound filtered to connection type public]
- `README.md` – This documentation

---

### 📌 Outcome
Gained hands-on experience with configuring Windows Firewall, understanding how firewall rules are applied, and learned how to control inbound traffic using port-based filtering.

---

### 🧠 Key Concepts
- Port-based traffic blocking
- Inbound vs Outbound rule configuration
- Rule testing using Telnet
- Restoring firewall state
