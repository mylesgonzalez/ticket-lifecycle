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
<img src="https://i.imgur.com/5Ojr65u.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this guide, we will go over the skills required to create and resolve a ticket within osTicket. To begin, let's log in as an end user so we can create a sample ticket that we will look at later when we log into our agent account. When creating a ticket, the end user can select a help topic, which can help speed up the assignment process. Of course, the admin or agent with the proper permissions can change who the ticket is assigned to and can even add more help topics for the end user to select. In this ticket, we will have the user make a ticket stating that the entire online banking system is down.
</p>
<br />

<p>
<img src="https://i.imgur.com/TVJUJDA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
So now, let's log in to osTicket using our agent account so we can view the different aspects of the ticket. As a service agent, you need to be able to route the ticket to the correct department, and the best way to accomplish this is by contacting the end user so more information on the problem can be obtained. After talking to the user, we can then assign an SLA to this ticket and route it to the correct department. If truly everyone in the banking department is experiencing an outage, this would be classified as SEV-A, which we defined to be the most impactful SLA in a previous project. After doing this, we can assign the ticket to the online banking team by switching the department. When working as a service agent, it is imperative that you keep the customer updated with every action you take to try and resolve the issue. Let's pretend the online banking team was able to resolve the ticket by rolling back an update, so now we can update the end user and close the ticket by explaining the cause of the issue and how the update was responsible for the outage.
</p>
<br />

<p>
<img src="https://i.imgur.com/XpELtIK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Let's work on a second ticket, but this time it will be the CFO reporting that their laptop is not turning on. When assigning the SLA, make sure you do so based on business impact and not the person who is submitting the ticket. Sometimes, meeting the client in person can help better identify the type of issue they are experiencing. In this example, let's assume that after replacing the CFO’s charger, the laptop was able to turn on because the battery was no longer dead. Inside osTicket, we can post a reply stating the exact reasons why the laptop was dead, and now we can safely close the ticket as we resolved it ourselves.
</p>
<br />

<p>
As a side note, tickets may not always be reported through the service, and as a service desk agent, you need to obtain all the information required to create a ticket through a phone call.
</p>
