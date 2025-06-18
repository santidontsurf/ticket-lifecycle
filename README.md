<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle Examples</h1>
This tutorial simulates end-user creation of a ticket and the agent side of ticket response.<br />


<h2>Ticket Creation & Response</h2>

<p>
</p>
<p>First, we will be creating a ticket from the end-user perspective by going to the Support Center Ticketing System with the link: http://localhost/osTicket and in there we can click "Open A New Ticket".</p>
<p align="center"><img alt="Screenshot 2025-06-18 at 10 43 48 AM" src="https://github.com/user-attachments/assets/3bf2f141-23f1-411d-a1eb-070c9f94cd19" height=80% width=80%/>
</p>
<br />
<p>In this new page, we will submit a ticket as Ken, one of the users we created. Add Ken's email address and name, and choose "Report a Problem/Business Critical Outage" as the Help Topic. For the Issue Summary type "Entire online banking system is down" and for the notes type "My employees are reporting that users are no longer able to access the online banking system, and that those who do can't log in" then click "Create Ticket" at the bottom.</p>
<p align="center"><img alt="Screenshot 2025-06-18 at 10 51 29 AM" src="https://github.com/user-attachments/assets/b7d1a498-107e-44a3-a6ea-a259b4931eab" height=80% width=80%/>
</p>
<br />
<p>Now that we have a ticket to work on, we will log in as an Jane, the agent we created. We will use the admin/agent login page (http://localhost/osTicket/scp/login.php ) and use the username and password created for Jane, once you've logged in yout main page should look like this:</p>
<p align="center"><img alt="Screenshot 2025-06-18 at 11 11 03 AM" src="https://github.com/user-attachments/assets/83303cd1-1e69-4758-b375-9d076b39c084" height=80% width=80% />
</p>
<br />
<p>We can see the ticket we just created at the top of the list of open tickets. If we click on it we'll be able to further examine its properties.</p>
<p align="center"><img alt="Screenshot 2025-06-18 at 11 18 15 AM" src="https://github.com/user-attachments/assets/311d3c1d-140a-4131-a96e-507a5acb014e" height=80% width=80%/>
</p>
<br />
<p>If you look at the top of the ticket, the status says "Open" and the priority "Normal". Seeing that this is a ticket reporting an issue that is severly damaging the company, we want to change the priority by click on "Normal" a new tab is open where we can change the priority level to "Emergency" and for the reason for this change we can write "Reported issue is affecting hundreds of users" then click "Update".</p>
<p align="center"><img alt="Screenshot 2025-06-18 at 11 23 21 AM" src="https://github.com/user-attachments/assets/b56f52a0-03b0-4181-ae25-9c6a8c23d072" height=80% width=80% />
 </p>
 <br />
 <p>Now that we have properly set the priority of the ticket, we can further examine the ticket and see that next to the "Assigned To:" section it says "Unassigned" which means that there is no one currently in charge of working on this ticket. To change that, we will click on Unassigned and choose ourselves as the Assignee (if there were more agents working on the company we could choose one of them) then click "Assign".</p>
 <p align="center"><img alt="Screenshot 2025-06-18 at 11 28 44 AM" src="https://github.com/user-attachments/assets/32d3334f-dff5-4f88-ab34-185744fbf8c3" height=80% width=80%/>
</p>
<br />
<p>The next thing we need to change is the chosen SLA for the ticket. Right now it's under "Default SLA", but we want to move it to "Sev-A" as it is a ticket of the highest severity and needs to be resolved as soon as possible. Click on "Default SLA" and change it to "Sev-A".</p>
<p align="center"><img alt="Screenshot 2025-06-18 at 11 31 09 AM" src="https://github.com/user-attachments/assets/30dd82a6-097b-4f23-9996-af7d2e0e90a9" height=80% width=80%/>
</p>
<br />
<p>Now that we've done all these changes to the ticket, we can click the refresh icon right next to the "Ticket #" at the top to see how the system logs every change we've made so far.</p>
<p align="center"><img alt="Screenshot 2025-06-18 at 11 34 09 AM" src="https://github.com/user-attachments/assets/c06c8cf1-405d-41e8-86e8-3c4f7dabd3ba" height=80% width=80%/>
</p>
<br />
<p>Since we now know that we as Jane Doe  will be working on this ticket, we can do our due dilligence and send a message to the end-user to let them know that their ticket has been assigned to an agent and that they will be kept updated with any progess on this issue. To do this, scroll down to the "Post Reply" section and type a response like this: "Hello Ken, an agent of ours is currently working on solving the ticket you just submitted and is in communication with our Level II Support team. We will keep you updated on the progress." then click "Post Reply".</p>
<p align="center"><img alt="Screenshot 2025-06-18 at 11 43 05 AM" src="https://github.com/user-attachments/assets/98f1daac-9539-4d0c-9194-35716cc4fd5d" height=80% width=80%/>
</p>
<br />
<p>You have now reached thend of this osTicket tutorial, congrats! You now have a concrete understanding of what dependenceis osTickets needs, how to configurate it based on your organizations requirements, and what working a ticket looks like. This tutorial only showed a small portion of what osTicket is capable of, and I encourage you to explore its interface further and to not be afraid to ask for assistance online or watch more tutorials on it. Best of luck out there!</p>
