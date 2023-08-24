# ticket-lifecycle
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
<img src="https://github.com/elTuTico/ticket-lifecycle/assets/137955237/bb51409f-3f4f-4474-9a9d-d0bd096c2e78"/>
</p>
<p>
We will now be playing around in the environment that we have created on our osTicket database. Using the “End User” login URL (http://localhost/osTicket/ )we will be creating a handful of spoof tickets with varying severity, have them looked over by varying departments/agents, and lastly solved to allow the end user to return to whatever tasks they had prior to their technical issues. 
</p>
<br />

<p>
<img src="https://github.com/elTuTico/ticket-lifecycle/assets/137955237/ec6f2c0b-16f5-4959-ac7e-b1b63e83f942"/>
</p>
<p>
Click “Open a New Ticket”. Fill in the information for “Email Address” and “Full Name” with the information we created in the previous section of this practical. Select one of the help topics we created from the previous section of this practical. Lastly, create a little description of what this specific issue is for this end user. 
</p>
<br />

<p>
<img src="https://github.com/elTuTico/ticket-lifecycle/assets/137955237/48a72528-be82-4340-b64a-135b38fdc069"/>
</p>
<p>
Now we will actively work towards solving this ticket by signing in as one of our agents created from the previous section of this practical. 
</p>
<br />

<p>
<img src="https://github.com/elTuTico/ticket-lifecycle/assets/137955237/aca19d74-3c87-4a14-89bd-5ea11c901a5f"/>
</p>
<p>
As an agent you should be able to view all of the tickets that have rolled in for your Department. From there you should be able to select one of the tickets and inquire a bit more information on the ticket submitted by the end user. Which might prompt you to change the qualities of the ticket itself to properly quantify its impact. 
</p>
<br />

<p>
<img src="https://github.com/elTuTico/ticket-lifecycle/assets/137955237/d672d18f-9d2b-4ba9-8ca4-ad121d1c5260"/>
</p>
<p>
For this example an issue affecting the customers access to the banking application is pretty severe. Go about adjusting the department over to “System Administrator” and the priority to “Emergency”. All of these changes could be found on the thread at the bottom of the ticket itself that outlines the work that has been put into solving the issue at hand. This is also a great place to jot down notes, queries, and information from department/agent to department/agent. 
</p>
<br />

<p>
<img src="https://github.com/elTuTico/ticket-lifecycle/assets/137955237/3cee8c4c-253c-45ad-b0e1-b79611404f75"/>
</p>
<p>
Log out as the agent you currently are within and log back in as the system administrator to start working on the ticket. Upon logging into the system administrator account you should be able to get a brief breakdown of the ticket that has been passed over to your department. 
</p>
<br />

<p>
<img src="https://github.com/elTuTico/ticket-lifecycle/assets/137955237/162f9f80-e862-4e3b-8cce-17ab1aa0042f"/>
</p>
<p>
Play around with the thread attached to this ticket and create a bit of a trail as to the kind of attempts that are being made towards fixing the issue at hand. Once you feel like enough back and forth has occurred go ahead and close out the ticket while labeling the kind of solution that was done to resolve the ticket. 
</p>
<br />

<p>
<img src="https://github.com/elTuTico/ticket-lifecycle/assets/137955237/f11fa888-019a-4763-8bcd-345df3732c6d"/>
</p>
<p>
Continue to play around with the environment you’ve created by making more tickets with your end users. Having your System Admin assign them to other agents/departments, and create a bit of a recurring log showing the kind of work was thrown at solving the tickets. Until then your System Admin and Agents should have a clean ticket dashboard, just waiting for the next ticket to come their way. 
</p>
<br />
