
<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo" />
</p>

<h1 align="center">osTicket - Ticket Lifecycle: Intake Through Resolution</h1>

<p>
  This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.
</p>

<h2>Environments and Technologies Used</h2>
<ul>
  <li>Microsoft Azure (Virtual Machines/Compute)</li>
  <li>Remote Desktop</li>
  <li>Internet Information Services (IIS)</li>
</ul>

<h2>Operating Systems Used</h2>
<ul>
  <li>Windows 10 (21H2)</li>
</ul>

<h2>Ticket Lifecycle Stages</h2>
<ul>
  <li>Intake</li>
  <li>Assignment and Communication</li>
  <li>Working the Issue</li>
  <li>Resolution</li>
</ul>

<h2>Access Links</h2>
<ul>
  <li><strong>Admin/Analyst Login:</strong> <a href="http://localhost/osTicket/scp/login.php">http://localhost/osTicket/scp/login.php</a></li>
  <li><strong>End User Portal:</strong> <a href="http://localhost/osTicket">http://localhost/osTicket</a></li>
</ul>
We will be creating a sample ticket as a end user (Karen or Ken) then assigning as a agent (Jane or John) and resolving as a agent(Jane or John).
<h2>Step 1: Create a Ticket as End-User (Karen or Ken)</h2>
<ul>
  <li>Ticket: “Entire mobile/online banking system is down.”</li>
</ul>

<p align="center">
  <img src="https://i.imgur.com/pBGk9xV.png" width="80%" alt="Ticket Creation Example" />
</p>

<h2>Step 2: Assign Properties as Help Desk Agent (John)</h2>
<ul>
  <li><strong>Ticket 1:</strong> Sev-A (1hr, 24/7) — Department: Online Banking<br />Note: Observe if ticket becomes inaccessible after escalation.</li>
</ul>

<p>
  To assign an SLA, click on the "Default SLA" and select the appropriate one.<br />
  To assign a Help Topic, click the link next to "Help Topic."<br />
  To assign an agent or team, click on "Unassigned" and select the appropriate assignee.
</p>

<p align="center">
  <img src="https://i.imgur.com/RuH4u0Z.png" width="80%" alt="Assign SLA" />
  <img src="https://i.imgur.com/BKNPDk9.png" width="80%" alt="Assign Help Topic" />
  <img src="https://i.imgur.com/TCwXxxz.png" width="80%" alt="Assign Agent or Team" />
</p>

<h2>Step 3: Work Ticket to Completion</h2>
As jane who is a part of the online banking team you can either assign the ticket to yourself or leave it in the online banking team. for this exsample we are assigning it to jane and adding a comment as if we are talking to are team.
  <img src="https://i.imgur.com/XeLtMZi.png" width="80%" alt="Ticket Resolution" />
</p>
 you can add comments to keep your team updated on progress of the ticket.
 
 
 <img src="https://i.imgur.com/8vxuX9X.png" width="80%" alt="Ticket Resolution" />
 
<ul>
 As this is a exsample we are going to pretend we check the system found that the new update to the system is whats cuaseing the issues and we are rolling back the update.
</p>
  <img src="https://i.imgur.com/Mk2gCRV.png" width="80%" alt="Ticket Resolution" />
</p>
  <li>
</ul>

<p align="center">

Now set the ticket to resolved
Ticket: Resolved by Jane</li>
<p>
  To resolve a ticket, click the link next to "Status" and select "Resolved."
</p>
<img src="https://i.imgur.com/j8d8sh4.png" width="80%" alt="Ticket Resolution" />
</p>
  
<h2>Best Practices & Reminders</h2>

<h3>Email Functionality</h3>
<p>Most ticketing systems send email notifications to users whenever a ticket is updated. Users can respond directly through email.</p>

<h3>Real-World Intake</h3>
<p>
  Tickets can be created through phone calls, chat apps, email, web forms, or even casual hallway conversations.<br />
  It's okay to help immediately, but you should always create a ticket to track work for reporting and metrics.
</p>


