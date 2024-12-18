<img src=https://github.com/user-attachments/assets/5343bd46-54fb-4ee6-94c1-b4c0bad1cec3>
<br />
<br />

<h1>osTicket - Post-Install Configuration</h1>

Having installed osTicket in a previous project, this section involves setting up roles, departments, and permissions. It also covers how to configure SLA policies and help topics to ensure tickets are categorized and prioritized correctly. This configuration mirrors real-world scenarios, enabling participants to customize the system based on organizational needs.<br />
<br />
<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)
- Remote Desktop
- Internet Information Services (IIS)
<br />
<br />

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)
<br />
<br />

<h2>Configuration Steps</h2>

1. Log into the Admin Panel and configure:
 - Roles: Define agent permissions by department.<br />
    <img src=https://github.com/user-attachments/assets/4a19173f-aecd-4f3d-b12d-3c92d58180bc>
 - Departments: Organize ticket visibility (e.g., SysAdmins, Support).<br />
    <img src=https://github.com/user-attachments/assets/4807935c-5bca-4bcf-949f-e0b3f8fe9b91>
 - Teams: Group agents for specific issues. We'll create a new team called "Online Banking".<br />
    <img src=https://github.com/user-attachments/assets/3d7b0ebd-3063-4874-bb89-4434f599ffaa>
 - SLA Plans: Define response time expectations (e.g., Sev-A: 1 hour, 24/7).<br />
    <img src=https://github.com/user-attachments/assets/17c6f4d1-c474-4385-a387-611f4e56c55f>
 - Help Topics: Pre-define categories for user tickets (e.g., Password Reset).<br />
    <img src=https://github.com/user-attachments/assets/746394a5-42dd-4855-b5bd-51e1537bc5ec>
<br />
<br />

2. Configure user and agent accounts:
 - Add agents to specific departments with primary roles.<br />
    <img src=https://github.com/user-attachments/assets/920d53d8-27e0-4bc9-b275-8994a368dbfc>
 - Create user accounts for end-users to submit tickets.<br />
    <img src=https://github.com/user-attachments/assets/6c3b6322-b57d-4f9c-b113-a13a2796292f>
<br />
<br />
