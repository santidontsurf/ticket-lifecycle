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
 <p>Now that we have properly set the priority of the ticket, we can further examine the ticket and see that next to the "Assigned To:" section it says "Unassigned" which means that there is no one currently in charge of working on this ticket. </p>
