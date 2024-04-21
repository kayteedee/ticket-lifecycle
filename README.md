<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

# osTicket - Ticket Lifecycle: Intake Through Resolution
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source helpdesk ticketing system osTicket.<br/>

## Environments and Technologies Used

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop (macOS)
- Internet Information Services (IIS)

## Operating Systems Used

- Windows 10</b> (21H2)

## Ticket Lifecycle Stages

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

## Lifecycle Stages

### Stage 1. ) Intake - Creating Tickets

- Open osTicket: http://localhost/osTicket/

- Select: `Open a New Ticket`

<img src="https://i.imgur.com/Hocs7bO.png"/>

- <ins>Insert the following ticket information</ins>:

  - Email Address: `Karen@osticket.com`

  - Name: `Karen Karen`

  - Help Topic: `Business Critical Outage`

  - Issue Summary: `Entire mobile online banking is down`
 
  - Ticket Details: `Customers are reporting they are getting a 404 error when browsing to online banking.`

  - Click: `Create Ticket`

>**Note: *When mobile online banking is down it can lead to major loss in revenue for the company.***


***

### Step 2. ) Assignment and Communication

- Login to osTicket as an Agent: `(User: jane.doe / jane.doe@gmail.com)`

<img src"https://i.imgur.com/6ipKM19.png"/>  



***

- Click: The `entire mobile online banking is down` Ticket we made in the prior step of this lab (step 1)
 
<img src"https://i.imgur.com/G4uqKcr.png"/>

***
In order for the ticket to be handled properly, information reguarding the severity level can be changed.
Because the entire mobile banking is down and that is critical to business impact, we are going to change priority
of this ticket to Emergency and the SLA to SEV-A.

<img src="https://i.imgur.com/Dd8m7IY.png"/>

- Priority: `Emergency`

  - Type In: `Business Impacting Event`
 
  - Click: `Update`


***

- Click: `Department`

  - Select: `System Administrators`

  - Details: `Sys Admins responsible for mobile banking infrastructure`
 
  - Click: `Transfer`

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/ticket-lifestyle/assets/161680745/36c0c3af-eef1-42fe-995b-a1434502f81a"><br>

***

- Assigned to: `Jane Doe`

  - Click: `Assign`

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/ticket-lifestyle/assets/161680745/a554032d-af6a-4a58-8b61-4eb41fb8eb68"><br>

***

- SLA Plan: `SEV-A`

  - Details: `Business Impacting, Critical Event`
 
  - Click: `Update`

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/ticket-lifestyle/assets/161680745/7e8ed40c-2af1-47b0-9c21-f46559d890f8"><br>

***

>**Note: *Make sure your ticket information matches the image below and continue to the next step.***

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/test-ticket-lifestyle/assets/161680745/2fcefd0b-2348-4657-9815-518cf0a24ef3"><br>

***

>**Note: *This is where you will see the history and updates of the tickets. &darr;***

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/ticket-lifestyle/assets/161680745/24eb9246-f9ab-4d37-b64f-920b9632a609"><br>

***

- Response Text Box: `Coordinating with Sys Admin Team to bring mobile banking back online.`

- Select: `Post Reply`

>**Note: *The organizaition you work for will determine the type of details you type into the description.***

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/ticket-lifestyle/assets/161680745/1b17a40a-3193-423b-9bdd-201edc1fa24a"><br>

***

- Go Back To: The `entire mobile online banking is down` Ticket

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/test-ticket-lifestyle/assets/161680745/144b43ef-ea8a-4997-bc9c-de5c09c98ae0"><br>

***

### Stage 3. ) Working the Issue

- On the back end, Jane is working with the System Adminstrator team to resolve the issue.

### Stage 4. ) Resolution
     
- Return to the ticket and update the end user once the issue is resolved.

- Response Text Box: `Jerry from System Engineering found and connected a failed load balancer. Mobile banking should be back up.`

- Ticket Status: `Resolved`

- Select: `Post Reply`

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/ticket-lifestyle/assets/161680745/9a8e565a-0549-4171-8c0d-72dbb5d37afe"><br>

***

*<ins>The ticket should now be on the "closed" tab since it has been resolved.</ins>*

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/test-ticket-lifestyle/assets/161680745/d2229ae1-877e-4184-b659-16a9c9cd60fd"><br>

🎉 Congratulations! You have created and resolved your first few tickets! 🎉

☎️ For any questions, concerns, or just to connect, you can contact me at:

📲 LinkedIn: www.linkedin.com/in/misskayteedee

📬 Email: misskayteedee@gmail.com
