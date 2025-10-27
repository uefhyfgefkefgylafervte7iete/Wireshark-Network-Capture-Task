# Wireshark-Network-Capture-Task
I have done a Network Capture using Wireshark. this is my report on it. and gained Hands-on packet analysis skils and protocol awareness.
# 🧠 Wireshark Network Capture and Analysis (Windows)

## 🎯 Objective
To perform live packet capture using Wireshark, analyze different network protocols, and summarize findings for network troubleshooting and monitoring.

---

## ⚙️ Steps Performed

### **1. Install Wireshark**
1. Download Wireshark from [https://www.wireshark.org/download.html](https://www.wireshark.org/download.html)
2. Install it along with **Npcap** (required for packet capture).



---

### **2. Start Capturing on Your Active Network Interface**
1. Open Wireshark.
2. Select your **active network interface** (Wi-Fi or Ethernet) that shows live traffic.
3. Click the **blue shark fin (▶️)** icon to begin capturing packets.



---

### **3. Browse a Website or Ping a Server to Generate Traffic**
- Visit websites like `https://www.google.com` or `https://www.wikipedia.org`
- Or open **Command Prompt** and run:
```cmd
ping google.com
```
This generates traffic for DNS, TCP, ICMP, and HTTP/HTTPS protocols.



---

### **4. Stop Capture After a Minute**
- Click the **red square stop button (⏹️)** on the toolbar to stop capturing.
- You can now analyze the captured packets.



---

### **5. Filter Captured Packets by Protocol**
Use Wireshark’s **Display Filter** bar to show specific traffic.

| Protocol | Filter Command |
|-----------|----------------|
| HTTP | `http` |
| DNS | `dns` |
| TCP | `tcp` |
| ICMP | `icmp` |

Type the filter and press **Enter** to view only that protocol’s packets.



---

### **6. Identify at Least 3 Different Protocols**
During the capture, you should observe multiple protocols such as:
- **DNS** – Domain name queries and responses
- **TCP/UDP** – Data transmission
- **HTTP/HTTPS** – Web communication
- **ICMP** – Ping packets (if you used ping)



---

### **7. Export the Capture as a .pcap File**
1. Go to **File → Save As...**
2. Save the capture as `network_capture.pcap`



---

### **8. Summarize Findings and Packet Details**

> **Summary Example:**
> During the Wireshark capture, several protocols were detected including DNS, TCP, and HTTP traffic.  
> - **DNS** packets resolved domain names like `google.com`.  
> - **TCP** packets established connections and transferred data.  
> - **HTTP** packets showed website requests and responses.  
> The capture confirmed normal browsing behavior with successful communication between client and servers.  
>
> **Total Packets Captured:** ~1000  
> **Active Protocols:** DNS, TCP, HTTP, ICMP  
> **Capture File:** `network_capture.pcap`

📸 **Screenshot:**  
<img width="1920" height="1080" alt="Screenshot 2025-10-27 105255" src="https://github.com/user-attachments/assets/9d871b9b-aebe-492a-9aea-84c08052369f" />
<img width="1920" height="1080" alt="Screenshot 2025-10-27 105339" src="https://github.com/user-attachments/assets/bc0ca964-a076-43bd-b79d-d7185e3f1dd5" />
<img width="1920" height="1080" alt="Screenshot 2025-10-27 105449" src="https://github.com/user-attachments/assets/0d5118cb-719f-4cf5-abd1-100c2daf731c" />
<img width="1920" height="1080" alt="Screenshot 2025-10-27 105514" src="https://github.com/user-attachments/assets/347e0832-2c2f-4daf-b3d8-4889e042851c" />
<img width="1920" height="1080" alt="Screenshot 2025-10-27 105555" src="https://github.com/user-attachments/assets/2b3b1056-fc76-43bb-af03-0297567909a7" />
<img width="1920" height="1080" alt="Screenshot 2025-10-27 105612" src="https://github.com/user-attachments/assets/bd65e370-8a18-4daf-98be-951760a4df34" />
<img width="1920" height="1080" alt="Screenshot 2025-10-27 105633" src="https://github.com/user-attachments/assets/048a3dfe-2918-4b54-b636-30823bd925f4" />


---

## 📋 Summary Table

| Step | Action | Output |
|------|---------|---------|
| 1 | Install Wireshark | Application installed successfully |
| 2 | Start Capture | Live packets displayed |
| 3 | Generate Traffic | Packets captured during browsing/ping |
| 4 | Stop Capture | Capture saved for analysis |
| 5 | Apply Filters | Displayed specific protocol traffic |
| 6 | Identify Protocols | Found DNS, TCP, HTTP |
| 7 | Export File | `.pcap` file saved |
| 8 | Summary | Documented findings |

---

### ✅ Author
**Name:** Karthik  
**Task:** Internship Task – Wireshark Network Capture  
**Platform:** Windows  
**Date:** October 2025
<img width="1920" height="1080" alt="Screenshot 2025-10-27 105633" src="https://github.com/user-attachments/assets/ece5efd4-4bd4-469d-9ad3-3b9e18eb6c7b" />
<img width="1920" height="1080" alt="Screenshot 2025-10-27 105644" src="https://github.com/user-attachments/assets/69163016-376d-4985-accb-f8d4dbc49b2a" />
<img width="1920" height="1080" alt="Screenshot 2025-10-27 110004" src="https://github.com/user-attachments/assets/02826836-7b85-4493-a5c9-1791fb208fca" />
