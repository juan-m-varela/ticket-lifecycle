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
<img src="https://i.imgur.com/a45Zcn3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Creating a ticket from the end user perspective...

Go to http://localhost/osTicket/ then click "Open a New Ticket" then enter an email address, full name, select a help topic, then enter the issue summary, then add a description of problem, then click "Create Ticket"

</p>
<br />

<p>
<img src="https://i.imgur.com/75vtOOH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Resolving a ticket from the agent perspective...

Go to http://localhost/osTicket/scp/login.php then log into Jane Doe's account to resolve this particular issue.

Click "Mobile Banking App is Offline" ticket, then click on the Priority field then change the Priority Level to "High" or "Emergency", then click "Update"

Change the Department from Support to System Administrators by clicking "Support" that is highlighted in blue and then selecting "System Administrators" from the Department: drop menu, then select "Transfer"

Change the SLA Plan from Default SLA to "Sev-A" by clicking on "Default SLA" that is highlighted in blue and select "Sev-A" from the drop menu, then click "Update"

Post a reply from Jane, the System Administrator, updating Karen on what is happening because of the high SLA. Then send an update message that the issue is resolved. Then select "Resolved" from the Ticket Status Box, then click "Post Reply"

You'll notice the ticket has disappeared from the Open tickets section.

Congrats! You now know how to make mock tickets from end customers and how they are handled from a help desk professional.

</p>
<br />

