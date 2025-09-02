<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 1 – Access osTicket and Prepare Departments

Admin/Analyst Login Page:
http://localhost/osTicket/scp/login.php

End Users osTicket URL:
http://localhost/osTicket

Change SysAdmins Department → Make it a Top Level Department.

Delete the Maintenance Department (not archive).
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 2 – Create & Work Tickets (Scenario 1)

As an End-User:

Create a ticket: “entire mobile/online banking system is down”.

As Agent John:

Observe ticket properties (Priority, Department, SLA, Assigned To).

Set properties:

SLA: Sev-A (1 hour, 24/7)

Department: Online Banking

Attempt to observe ticket again as John → check if you can view/change.

As Agent Jane: Work the ticket to completion.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 3 – Create & Work Tickets (Scenarios 2 & 3)

Ticket 2 (End-User): “accounting department needs adobe upgrade, broken”

As John: set properties → SLA: Sev-B (4 hours, 24/7), Dept: Support

Work to completion as John.

Ticket 3 (End-User): “CFO’s laptop will no longer turn on”

As John: set properties → SLA: Sev-B (4 hours, 24/7), Dept: Support

Work to completion as John.
<br />


<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 4 – Escalation & Permissions

Set properties for all tickets.

Make SysAdmins ticket Sev-A last → notice ticket becomes inaccessible to John.

Switch to Admin Panel → Assign yourself View-access to SysAdmins.

Switch back to Agent Panel → Observe escalated ticket.

Confirm you cannot make changes once escalated.

Solve all tickets.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 5 – Real-World Ticketing Practices

Note: Most ticketing systems (including osTicket) support email notifications.

Users get updates when tickets are modified.

Users can reply to emails, which update the ticket.

Ticket intake IRL (phone, chat app, email, web form, in-person).

Always create tickets for all work done → helps with metrics and tracking.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 6 – Finishing Up & Practice

Encourage re-doing the lab multiple times.

Explore additional features like the email module.

Emphasize technical skill-building and repeated practice.

Goal: Build intuition until this becomes second nature.
</p>
<br />
