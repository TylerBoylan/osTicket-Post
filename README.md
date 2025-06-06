<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Help Topics
- Roles
- Service Level Agreements

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/n5i1ixW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this screenshot, I set up different roles for agents in osTicket. Creating roles like “All Access,” “Limited Access,” and “View Only” helps define what each user is allowed to do in the system.

This makes it easier for an admin to manage who can view tickets, make changes, or access sensitive settings. It’s a simple but important part of keeping the support system organized and secure — especially when different team members have different responsibilities.
</p>
<br />

<p>
<img src="https://i.imgur.com/AjNUzJ3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here, I set up different help topics in osTicket to make it easier for users to submit tickets. Each topic — like “Password Reset,” “General Inquiry,” or “Access Issue” — gives users a clear way to describe what they need help with.

This helps organize incoming tickets and makes it easier for the support team to know where to send them or how urgent they are.
</p>
<br />

<p>
<img src="https://i.imgur.com/GNRXwUT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This is where I added Service Level Agreements (SLAs) to the osTicket system. I set up different severity levels — Sev-A through Sev-C — so tickets can be prioritized based on how urgent they are.

For example, a Sev-A ticket might be something critical that needs a fast response, while Sev-C would be less urgent. Each level has its own time window to make sure issues are handled on time. This setup helps the support team stay organized and focused on what matters most.
</p>
<br />
