<h1>IT Service Management (ITSM) & Jira Workflow Project</h1>


<h2>Description</h2>
This project demonstrates the design and management of a professional IT Support environment using Jira Service Management. It simulates a high-volume help desk, showcasing my ability to categorize technical issues, prioritize urgent business needs, and document resolutions for a technical knowledge base.
<br />


<h2>Tools Used</h2>

- Jira (Atlassian): Issue tracking, workflow customization, and priority management.
- Kanban Methodology: Used for continuous delivery and request flow.
- Troubleshooting: Hardware, Software (SaaS), and Network connectivity.

<h2>Environments Used </h2>

- <b>(Host) Windows 11 Pro </b>(23H2)

<h2>Key Takeaways 📝</h2>

- Implementing a structured ticketing hierarchy (Incidents vs. Service Requests) ensures that critical system failures are addressed with high urgency while routine administrative tasks are managed without disrupting core operations.
- Maintaining detailed resolution logs and root-cause documentation transforms closed tickets into a searchable knowledge base, significantly reducing time to resolution for recurring technical issues.
- The project strengthened hands-on skills in IT Service Management (ITSM) frameworks, workflow customization within Jira, and the professional communication required between IT departments and end-users.
- 
<h2>Project Gallery:</h2>

<p align="center">
<b>Main Ticket Queue (List View)</b> <br/>
<img width="1890" height="891" alt="image" src="https://github.com/user-attachments/assets/c121975f-02bb-4b29-b535-eb6954e7646d" />
<br />
<br />
<b>Create Resource Group:</b>  <br/>
<img width="874" height="456" alt="image" src="https://github.com/user-attachments/assets/3473a336-8a7c-4551-a376-370a65805f26" />
<br />
<br />
<b>Create a Virtual Network:</b>  <br/>
<img width="813" height="718" alt="image" src="https://github.com/user-attachments/assets/75520e3a-0329-41c5-81fb-b9801abe98fe" />
<br />
<br />
<b>Create Virtual Machine:</b>  <br/>
<img width="757" height="598" alt="image" src="https://github.com/user-attachments/assets/0281dfb7-f114-4845-8bfd-b8529105d411" />
<img width="954" height="751" alt="image" src="https://github.com/user-attachments/assets/d45a950f-27f2-463e-97aa-f90ac9c487e2" />
<br />
<br />
<b>Configure VM Settings:</b>  <br/>
<img width="1144" height="782" alt="image" src="https://github.com/user-attachments/assets/018e6bf2-a506-44a5-b4dc-735057448013" />
<br />
<br />
<b>Set Up VM Username and PW:</b>  <br/>
<img width="804" height="555" alt="image" src="https://github.com/user-attachments/assets/c4beafc0-e9bb-497d-9998-77d35dd43d1a" />
<br />
<br />
<b>Create a New Network Security Group:</b>  <br/>
<img width="800" height="702" alt="image" src="https://github.com/user-attachments/assets/50753420-4759-450e-b062-594cc7bc81d8" />
<br />
<br />
<b>Allow Anyone To Ping the VM:</b>  <br/>
<img width="1901" height="860" alt="image" src="https://github.com/user-attachments/assets/b15841ad-5a56-4caa-9e99-e2e9f2cbb4f6" />
<br />
<br />
<b>Disable the Windows Firewall on VM so it can be pinged publicly:</b>  <br/>
<img width="1084" height="799" alt="image" src="https://github.com/user-attachments/assets/87543762-4ace-424f-a79a-c299159b7fb0" />
<br />
<br />
<b>Ping VM Using Host PC to make sure it is reachable over the public internet:</b>  <br/>
<img width="647" height="305" alt="image" src="https://github.com/user-attachments/assets/04cca0e2-bf48-4f3b-9c78-14560eebe3cc" />
<br />
<br />
<b>Open Event Viewer to view Windows processes on VM:</b>  <br/>
<img width="786" height="697" alt="image" src="https://github.com/user-attachments/assets/87b9204d-c720-4402-812e-8ea950e2844a" />
<br />
<br />
<b>Attempt to login again, however enter incorrect credentials:</b>  <br/>
<img width="396" height="241" alt="image" src="https://github.com/user-attachments/assets/0c4fd82f-6411-4a96-8619-1fa83bd8f142" />
<br />
<br />
<b>These "failed" attempts will identify as "Audit Failure" with the code "4625," future login attempts from brute forcers around the world will register as the same code:</b>  <br/>
<img width="1309" height="372" alt="image" src="https://github.com/user-attachments/assets/4fdf3ed2-d002-480a-af56-5eab1690a793" />
<br />
<br />
<b>Create Log Analytics Workspace:</b>  <br/>
<img width="769" height="665" alt="image" src="https://github.com/user-attachments/assets/e6989b61-0647-41a3-83f7-0b109b48535d" />
<br />
<br />
<b>Add Microsoft Sentinel to the Workspace:</b>  <br/>
<img width="1682" height="367" alt="image" src="https://github.com/user-attachments/assets/ef27148b-1b80-4de5-a8ce-2c7e0a91e98e" />
<br />
<br />
<b>Configure the Azure monitoring agent using security event connector:</b>  <br/>
<img width="1898" height="845" alt="image" src="https://github.com/user-attachments/assets/e93a5b62-e489-4955-98b7-ff4fb7ccadd6" />
<img width="838" height="350" alt="image" src="https://github.com/user-attachments/assets/25b6a3ee-3184-4302-9a6d-89d917244d86" />
<br />
<br />
<b>Showing All Security Events through Log Analytics Workspace:</b>  <br/>
<img width="1586" height="789" alt="image" src="https://github.com/user-attachments/assets/a91885ee-5548-4214-ab76-15cbeca832b0" />
<br />
<br />
<b>Create a Watchlist to compile and organize the data collected:</b>  <br/>
<img width="1694" height="668" alt="image" src="https://github.com/user-attachments/assets/ccd536da-8807-4146-a580-c00b29539c9b" />
<img width="1599" height="603" alt="image" src="https://github.com/user-attachments/assets/776789a6-8336-47c1-a730-8bc608839220" />
<br />
<br />
<b>Using this query, now we can see where the attackers are attacking from:</b>  <br/>
<img width="1204" height="662" alt="image" src="https://github.com/user-attachments/assets/619de9cc-6fba-4335-9ec7-0cb9908f192e" />
<br />
<br />
<b>Map of attackers geolocations:</b>  <br/>
<img width="1611" height="545" alt="image" src="https://github.com/user-attachments/assets/3d1227bd-f5d2-4af6-a62c-0adc9f3e1635" />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
