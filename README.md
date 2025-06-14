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

<h2>Step 1: Create Tickets as End-User (Karen or Ken)</h2>
<ul>
  <li>Ticket 1: “Entire mobile/online banking system is down.”</li>
  <li>Ticket 2: “Accounting department needs Adobe upgrade; currently broken.”</li>
  <li>Ticket 3: “CFO’s laptop will no longer turn on.”</li>
</ul>

<p align="center">
  <img src="https://i.imgur.com/pBGk9xV.png" width="80%" alt="Ticket Creation Example" />
</p>

<h2>Step 2: Assign Properties as Help Desk Agent (John)</h2>
<ul>
  <li><strong>Ticket 1:</strong> Sev-A (1hr, 24/7) — Department: Online Banking<br />Note: Observe if ticket becomes inaccessible after escalation.</li>
  <li><strong>Ticket 2:</strong> Sev-B (4hr, 24/7) — Department: Support</li>
  <li><strong>Ticket 3:</strong> Sev-B (4hr, 24/7) — Department: Support</li>
  Too assign SLA click on defult SLA and assign the approptiate SLA
  Too assign a help topick click the link nect to help topic
  Too assign a agent or team click on unassigned assign too
</ul>

<p align="center">
  <img src="https://i.imgur.com/RuH4u0Z.png" width="80%" alt="Ticket Assignment" />
   <img src="https://i.imgur.com/BKNPDk9.png" width="80%" alt="Ticket Assignment" />
   <img src="https://i.imgur.com/TCwXxxz.png" width="80%" alt="Ticket Assignment" />
</p>

<h2>Step 3: Work Tickets to Completion</h2>
<ul>
  <li>Ticket 1: Resolved by Jane</li>
  <li>Ticket 2: Resolved by John</li>
  <li>Ticket 3: Resolved by John</li>
  Too resolve a ticket click on the link next to status then resolve
</ul>

<p align="center">
  <img src="https://i.imgur.com/j8d8sh4.png" width="80%" alt="Ticket Resolution" />
</p>

<h2>Best Practices & Reminders</h2>

<h3>Email Functionality</h3>
<p>Most ticketing systems send email notifications to users whenever a ticket is updated. Users can respond directly through email.</p>

<h3>Real-World Intake</h3>
<p>
  Tickets can be created through phone calls, chat apps, email, web forms, or even casual hallway conversations.  
  It’s okay to fix things on the spot, but you should always create a ticket to track work for reporting and metrics.
</p>



