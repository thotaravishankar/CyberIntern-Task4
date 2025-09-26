# CyberIntern-Task4



##  Objective
Configure and test basic firewall rules to allow or block network traffic on Windows Firewall / UFW (Linux).



##  Tools Used
- Operating System: [Windows / Linux (Ubuntu/Debian)]  
- Firewall: [Windows Firewall / UFW]  

---

##  Steps Performed

### 1️. Check Firewall Status
----> in kali linux:
sudo iptables -L -v -n
<img width="904" height="212" alt="Screenshot From 2025-09-26 12-31-37" src="https://github.com/user-attachments/assets/33b604ed-1be8-4eb2-8138-3ef3c0c16926" />
----> in windows
<img width="1920" height="1080" alt="Screenshot (15)" src="https://github.com/user-attachments/assets/67b6ddbc-0341-4d2a-a64e-5fb1d5450545" />

2. Block inbound traffic on port 23(telnet):
   ------> kali linux
   <img width="904" height="272" alt="Screenshot From 2025-09-26 12-31-56" src="https://github.com/user-attachments/assets/5dd63d49-7b64-4c6b-88ea-f1487862eb88" />

   ------> in windows
   ![Uploading Screenshot (5).png…]()

4. Allow port 22(ssh):
   ------> in kali linux
   <img width="904" height="290" alt="Screenshot From 2025-09-26 12-32-20" src="https://github.com/user-attachments/assets/06192230-3b2b-4459-8bed-fa2c14d0e811" />

   -------> in windows
   <img width="1920" height="1080" alt="Screenshot (11)" src="https://github.com/user-attachments/assets/f7933ed5-085c-4047-a2a9-534755ea89cc" />

5. Verify Rules:
  ----> kali linux
   <img width="904" height="290" alt="Screenshot From 2025-09-26 12-32-20" src="https://github.com/user-attachments/assets/1a69d961-ead0-4116-8d60-27f14675d754" />

6. Test Rule
Attempt to connect to port 23 (Telnet) → Should fail.
   <img width="1920" height="1080" alt="Screenshot (16)" src="https://github.com/user-attachments/assets/5d73b026-6c5f-40e2-9305-2157a3d12f4e" />

7. Remove Test Rule
  ------> kali linux
   <img width="904" height="290" alt="Screenshot From 2025-09-26 12-32-30" src="https://github.com/user-attachments/assets/449556b3-50ec-433b-a483-30b09b743466" />

   ------> windows
   <img width="1920" height="1080" alt="Screenshot (14)" src="https://github.com/user-attachments/assets/081d8d57-fc0d-4639-bae0-606b96573672" />



 A firewall filters inbound and outbound traffic based on rules.

Blocking Telnet (port 23) prevents insecure access.

Allowing SSH (port 22) enables secure remote management.

This task demonstrates basic firewall management and network traffic filtering.






