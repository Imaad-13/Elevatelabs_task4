# 🔒 Block Inbound Traffic on Port 23 (Telnet) – Windows Firewall

This guide documents the process to create a rule in **Windows Defender Firewall** to block inbound TCP traffic on **Port 23**, which is commonly used by **Telnet**.

---

## 🚀 Steps to Create the Rule

1. Open **Windows Defender Firewall with Advanced Security**.
2. In the left pane, select **Inbound Rules**.
3. Click on **New Rule…** in the right-hand Actions pane.

### Configure the New Rule:

- **Rule Type**: `Port`
- **Protocol**: `TCP`
- **Specific Local Port**: `23`
- **Action**: `Block the connection`
- **Profile**: `Domain`, `Private`, `Public` (All selected)
- **Name**: `Block Telnet (Port 23)`

Click **Finish** to apply the rule.

---

## 🧪 Testing the Rule

To test if the firewall rule is working:

1. Enable the **Telnet Client** (if not already):
   - Go to:  
     `Control Panel → Programs → Turn Windows features on or off`
   - Check **Telnet Client** → Click **OK**

2. Open Command Prompt and run: "telnet localhost 23".

3. You should see a "Could not open connection" error indicating the port is blocked.