# Network-traffic-capture-and-analysis-with-Wireshark
## AIM:
To capture and analyze network traffic using Wireshark in order to observe protocols, packets, and potential anomalies.

## DESIGN STEPS:
### Step 1:
Install Wireshark using the command:

### Step 2:
Launch Wireshark and select the appropriate network interface for live traffic capture.

### Step 3:
Start the capture, apply filters (like http, tcp, ip.addr == x.x.x.x) to analyze specific traffic, and stop the capture after observing relevant data.

## PROGRAM:

Wireshark Packet Capture and Filter Usage

![image](https://github.com/user-attachments/assets/5fbb8163-2416-411f-8a70-925ab1ea49d7)


Start Capturing Packets

• Click the blue shark fin icon or double-click the interface.

• Wireshark will start capturing all real-time traffic.

![image](https://github.com/user-attachments/assets/7d3c586d-328e-41b9-9e29-8a45b7f68a4f)


Apply Filters to Focus on Specific Traffic

• Use filters like http, ip.addr == 192.168.1.1, or tcp.port == 80 in the top filter bar to narrow down results.

![image](https://github.com/user-attachments/assets/29bf6bf6-1b04-4675-93b0-eeaa2903a885)


Analyze Packet Details

• Click on a packet to view its detailed breakdown including frame, Ethernet,IP, TCP/UDP layers, and data payload.


## OUTPUT:

Captured Packets with Protocol Analysis and Detailed Packet Info

![image](https://github.com/user-attachments/assets/120958aa-276f-410b-8c26-b56e3b5368d2)


## RESULT:

Network traffic was successfully captured and analyzed using Wireshark.
