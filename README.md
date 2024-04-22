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

The first thing we are going to do create a ticket from the user end of the osTicket platform.

- Open osTicket: http://localhost/osTicket/

- Select: `Open a New Ticket`

<img src="https://i.imgur.com/4Slnd3I.png"/>


- <ins>Insert the following ticket information</ins>:

  - Email Address: `Karen@osticket.com`

  - Name: `Karen Karen`

  - Help Topic: `Business Critical Outage`

  - Issue Summary: `Entire mobile online banking is down`
 
  - Ticket Details: `Customers are reporting they are getting a 404 error when browsing to online banking.`

  - Click: `Create Ticket`

    <img src="https://i.imgur.com/Hocs7bO.png"/>

>**Note: *When mobile online banking is down it can lead to major loss in revenue for the company.***


***

### Step 2. ) Assignment and Communication

- Login to osTicket as an Agent: `(User: jane.doe / jane.doe@gmail.com)`

<img src="https://i.imgur.com/6ipKM19.png"/> 



***

- Click: The `entire mobile online banking is down`
  (this is the ticket we just created on the user end as Karen)
 
<img src="https://i.imgur.com/1qsE9NG.png"/>

***
In order for the ticket to be handled properly, information reguarding the severity level can be changed.
Because the entire mobile banking is down and that is critical to business impact, we are going to change the priority
of this ticket to EMERGENCY and the SLA to SEV-A.

<img src="https://i.imgur.com/Dd8m7IY.png"/>

- Priority: `Emergency`

  - Type In: `Business Impacting Event`
 
  - Click: `Update`


***
 We are also going to assign

- Click: `Department`

  - Select: `System Administrators`

  - Details: `Sys Admins responsible for mobile banking infrastructure`
 
  - Click: `Transfer`

<p align="center">
<img width="800" alt="isolated" src="https://i.imgur.com/Hw2VHyq.png"><br>

***

- Assigned to: `Jane Doe`

  - Click: `Assign`

<p align="center">
<img width="800" alt="isolated" src="https://i.imgur.com/WaMBNU3.png"><br>

***

- SLA Plan: `SEV-A`

  - Details: `Business Impacting, Critical Event`
 
  - Click: `Update`

<p align="center">
<img width="800" alt="isolated" src="https://i.imgur.com/Dd8m7IY.png"><br>

***

>**Note: *Make sure your ticket information matches the image below and continue to the next step.***

<p align="center">
<img width="800" alt="isolated" src="https://i.imgur.com/N2HuQJg.png"><br>

***

>**Note: *This is where you will see the history and updates of the tickets. &darr;***

<p align="center">
<img width="800" alt="isolated" src="https://i.imgur.com/UOOBCD6.png"><br>

***

### Stage 3. ) Working the Issue

- On the back end, Jane is working with the System Adminstrator team to resolve the issue.

- Response Text Box: `Coordinating with Sys Admin Team to bring mobile banking back online.`

- Select: `Post Reply`


<p align="center">
<img width="800" alt="isolated" src="https://i.imgur.com/ABuZ4RN.png"><br>
**Note: *The organizaition you work for will determine the type of details you type into the description.**


***

### Stage 4. ) Resolution
     
- Return to the ticket and update the end user once the issue is resolved.

- Response Text Box: `Jerry from System Engineering found and connected a failed load balancer. Mobile banking should be back up.`

- Ticket Status: `Resolved`

- Select: `Post Reply`

<p align="center">
<img width="800" alt="isolated" src="https://i.imgur.com/KnWu3Q7.png"><br>

***

*<ins>The ticket should now be on the "closed" tab since it has been resolved.</ins>*

<p align="center">
<img width="800" alt="isolated" src="https://i.imgur.com/G4uqKcr.png"><br>

🎉 Congratulations! You have created and resolved your first few tickets! 🎉

☎️ For any questions, concerns, or just to connect, you can contact me at:

📲 LinkedIn: www.linkedin.com/in/misskayteedee

📬 Email: misskayteedee@gmail.com
