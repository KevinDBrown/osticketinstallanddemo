# 🎫 osTicket Full Installation & Usage Demo (End-to-End)

This project documents the full installation and configuration of **osTicket**, an open-source support ticket system. It covers everything from provisioning the virtual machine to resolving tickets via the agent panel. This is ideal for IT support, sysadmin, and helpdesk portfolio use.

---

## 📂 Project Structure


---

## 🛠️ Step-by-Step Setup

### 1. Provision Virtual Machine
- Created a **Windows Server VM** for osTicket hosting.
- [![VM Created](VM-Windows_osTicket_Created.png)](VM-Windows_osTicket_Created.png)

### 2. Install Prerequisites
- ✅ **IIS (Internet Information Services)**
  - [![IIS Admin](IIS%20Main%20Page%20as%20an%20Admin.png)](IIS%20Main%20Page%20as%20an%20Admin.png)
- ✅ **PHP Manager for IIS**
  - [![PHP Manager](PHP%20Manager%20Installed%20for%20IIS.png)](PHP%20Manager%20Installed%20for%20IIS.png)
- ✅ **PHP Extensions**
  - [![PHP Mods](PHP%20Extensions%20Modified.png)](PHP%20Extensions%20Modified.png)
- ✅ **MySQL Server**
  - [![MySQL](MySQL%20Server%20Installed.png)](MySQL%20Server%20Installed.png)
- ✅ **Visual C++ Redistributable**
  - [![Redistributable](Redistributable%20File%20Installed.png)](Redistributable%20File%20Installed.png)

### 3. osTicket Installation
- Extracted PHP files and configured the install.
- [![osTicket Install](osTicket%20Installed.png)](osTicket%20Installed.png)
- [![Install Confirmed](osTicket%20Installation%20Confirmation.png)](osTicket%20Installation%20Confirmation.png)

### 4. Configure Database
- Used **HeidiSQL** to connect and configure the osTicket database.
- [![HeidiSQL Running](Heidi%20Being%20Ran%20as%20Admin.png)](Heidi%20Being%20Ran%20as%20Admin.png)
- [![Database Created](osTicket%20Database%20Created.png)](osTicket%20Database%20Created.png)

### 5. Initial Setup in Web Portal
- Created agents, roles, departments, and teams.
- [![Roles/Agents](osTicket_TwoAgentsCreated%20%5B%20Ace%20%26%20Happy%20%5D%20.png)](osTicket_TwoAgentsCreated%20%5B%20Ace%20%26%20Happy%20%5D%20.png)
- [![Help Topics](osTicket_HelpTopicsCreatedForUsers.png)](osTicket_HelpTopicsCreatedForUsers.png)

---

## 🎟️ Ticket Creation & Workflow

### Ticket 1 Example (User Submitted → Resolved)
1. Ticket Created by User  
   [![Created](Ticket1_CreatedByUser.png)](Ticket1_CreatedByUser.png)
2. Assigned to Agent  
   [![Assigned](Ticket1_AssignedToAgent.png)](Ticket1_AssignedToAgent.png)
3. Help Topic + SLA Applied  
   [![SLA](Ticket1_SLAassigned.png)](Ticket1_SLAassigned.png)
4. Agent Updates Thread  
   [![Update](Ticket1_AgentUpdateToTicketThread.png)](Ticket1_AgentUpdateToTicketThread.png)
5. Resolved  
   [![Resolved](Ticket1_Resolved.png)](Ticket1_Resolved.png)

### Tickets 2 & 3 Workflow Highlights
- Multiple SLAs and assignments
- Different agents working tickets
- Final state: all closed/resolved
- [![Tickets Summary](Tickets_1_2_3_ReflectedInTicketHistory.png)](Tickets_1_2_3_ReflectedInTicketHistory.png)

---

## 💻 Programs & Tools Used

| Tool/Program | Purpose |
|--------------|---------|
| **Windows Server VM** | Hosting environment |
| **IIS** | Web server |
| **MySQL** | Backend DB |
| **PHP (via PHP Manager)** | Required for osTicket |
| **HeidiSQL** | GUI for managing database |
| **osTicket** | Ticket system |
| **Visual C++ Redistributable** | Dependency for PHP extensions |

---

## 🧠 Learning Outcomes

- ✅ Deploy osTicket from scratch in a Windows environment
- ✅ Configure IIS with PHP and MySQL backend
- ✅ Navigate ticket lifecycl


Feel free to reach out on [LinkedIn](https://www.linkedin.com/in/kevindeonbrown)!
