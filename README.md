<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo" />
</p>

<h1 align="center">osTicket - Ticket Lifecycle: Intake Through Resolution</h1>

This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk system **osTicket**.

---

## 🧰 Environments and Technologies Used

- Microsoft Azure (Virtual Machines / Compute)
- Remote Desktop Protocol (RDP)
- Internet Information Services (IIS)

---

## 💻 Operating System Used

- Windows 10 (21H2)

---

## 🛠 Ticket Lifecycle Stages

1. **Intake**
2. **Assignment and Communication**
3. **Working the Issue**
4. **Resolution**

---

## 🌐 Access Links

> These links work if you are running osTicket locally. Replace `localhost` with your machine’s IP address if needed.

- **Admin/Analyst Login:**  
  [`http://localhost/osTicket/scp/login.php`](http://localhost/osTicket/scp/login.php)

- **End User Portal:**  
  [`http://localhost/osTicket`](http://localhost/osTicket)

---

## 📝 Walkthrough

### Step 1: Create a Ticket as End User (Karen or Ken)

- Log in to the End User Portal.
- Submit a new ticket.  
  Example issue:  
  **“Entire mobile/online banking system is down.”**

<p align="center">
  <img src="https://i.imgur.com/pBGk9xV.png" width="80%" alt="Ticket Creation Example" />
</p>

---

### Step 2: Assign Ticket Properties as Help Desk Agent (John)

- Log in as John (help desk agent).
- Find the new ticket and assign the following:
  - **Severity:** Sev-A (1-hour SLA, 24/7)
  - **Department:** Online Banking
  - Assign to the appropriate **agent or team**.
  - Select a relevant **Help Topic**.

> Note: After escalation, check whether the ticket becomes inaccessible due to permission settings.

<p align="center">
  <img src="https://i.imgur.com/RuH4u0Z.png" width="80%" alt="Assign SLA" />
  <img src="https://i.imgur.com/BKNPDk9.png" width="80%" alt="Assign Help Topic" />
  <img src="https://i.imgur.com/TCwXxxz.png" width="80%" alt="Assign Agent or Team" />
</p>

---

### Step 3: Work the Ticket (Agent: Jane)

- Log in as **Jane**, a member of the Online Banking team.
- Assign the ticket to yourself, or leave it under the team’s queue.
- Add internal comments to communicate with your team.

<p align="center">
  <img src="https://i.imgur.com/XeLtMZi.png" width="80%" alt="Internal Comments" />
  <img src="https://i.imgur.com/8vxuX9X.png" width="80%" alt="Progress Update" />
</p>

#### Example Internal Note:

> “Update: We've investigated the outage. The issue was caused by a recent system update. We're rolling back the update to restore functionality.”

<p align="center">
  <img src="https://i.imgur.com/Mk2gCRV.png" width="80%" alt="Troubleshooting Notes" />
</p>

---

### Step 4: Resolve the Ticket

Once the issue is resolved:

1. Update the ticket status to **Resolved**.
2. Add a resolution note (e.g., "Issue resolved by Jane. Update rollback restored service.").

<p align="center">
  <img src="https://i.imgur.com/j8d8sh4.png" width="80%" alt="Mark as Resolved" />
</p>

---

## 🧠 Best Practices & Tips

### Email Notifications

- osTicket can send automatic email updates to users when their ticket is updated.
- End users can reply to emails to continue communication.

### Real-World Ticket Intake

Tickets can be created from:
- Phone calls
- Emails
- Web forms
- Chat apps
- Walk-ins or verbal requests

> Even if you resolve an issue immediately, always document it in a ticket. This helps with metrics, tracking, and team visibility.

---


