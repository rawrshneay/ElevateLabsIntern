# ElevateLabsIntern
I used Nmap to perform a TCP SYN scan on my local network (10.0.2.0/24) to identify active devices and the open ports on each. This helped me understand which services are exposed on the network, which could pose potential security risks.
![image](https://github.com/user-attachments/assets/f31bd754-7dfa-4d0a-b7ae-aaa7d87d12d6)
i proceeded to save it in a text file
![image](https://github.com/user-attachments/assets/5dadbd4d-c86f-430a-a40c-e004fc98e179)
While the scan was running, I used Wireshark to capture and analyze the live network traffic. By applying filters like tcp.flags.syn == 1 and tcp.flags.ack == 0, I could see the SYN packets sent by Nmap and the SYN-ACK or RST responses from target hosts. This gave me a deeper understanding of how Nmap interacts with network devices and how ports respond based on their state.
![image](https://github.com/user-attachments/assets/92f276a4-ba55-47ce-8ba6-cfbf6134ddc4)

