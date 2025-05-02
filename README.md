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

**Capturing Traffic in Wireshark**

1. Open Wireshark and start capturing on the active interface (Wi-Fi/Ethernet).

2. Perform activities like opening a website or sending an email through a client (e.g., Gmail via browser or Thunderbird).

4. Stop the capture once done.

![image](https://github.com/user-attachments/assets/04f9e42a-15ca-4cc2-a81c-97b889bb176b)

**Analyze DNS Queries:**

o Filter: dns

o Reveal domains the browser tried to resolve.

![image](https://github.com/user-attachments/assets/eb10207d-d377-448d-beef-9985f73ae7ff)

**Email Header Analysis**

1. Apply relevant filters:
 
o For POP3: tcp.port == 110

o For SMTP: tcp.port == 25 or 587

o For IMAP: tcp.port == 143 or 993

2. Locate email data:

o Look for SMTP packets to see sender/receiver email addresses.

o Use "Follow TCP Stream" to view the full email headers and body if unencrypted.

**Extract Email Header Fields:**

o Analyze From, To, Subject, Date, Message-ID, and relay servers used in sending the email.

## OUTPUT:

Captured Packets with Protocol Analysis and Detailed Packet Info

![Screenshot 2025-04-21 223935](https://github.com/user-attachments/assets/0bd101fe-2793-4eb1-b064-3ccaffd3ee3d)

![Screenshot 2025-04-21 224213](https://github.com/user-attachments/assets/37843833-560e-4dfa-ad86-8f3a4d0f53b2)

![Screenshot 2025-04-21 224344](https://github.com/user-attachments/assets/32698667-c3a1-4720-a813-56f94cf3da69)

## RESULT:

Network traffic was successfully captured and analyzed using Wireshark.
