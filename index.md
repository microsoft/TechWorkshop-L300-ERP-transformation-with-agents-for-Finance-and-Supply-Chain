---
title: Introduction
layout: home
nav_order: 1
---

# Deploy a new Finance and Operations ppac environment in your Demo environment 

In this lab, you'll configure a Finance and Operations Demo environment so that you can demonstrate the value of relevant AI agents to customers.


### Prerequisites

To run this lab, you'll need a **Finance and Operations Demo** environment that is hosted on Business Applications Demo Hub. We provide instructions for accessing the Demo Hub and requesting the environment for reference as Exercise 0.

{: .warning }
> It's important that you request the demo prior to this workshop. It can take several hours for the system to provision the environment after you make the request.


### Disclaimer
The agents that you'll configure in this lab are considered production ready previews. The agents do employ most privacy and security measures typically present in generally available online services. You may use such previews to process personal data or other data that is subject to legal or regulatory compliance requirements. 


### Tools and technologies used in this lab

In this lab, you'll use a variety of tools and technologies to configure the demo environment, including:

- Azure portal
- Copilot Studio
- Microsoft 365 admin center
- Microsoft Graph Explorer
- Power Apps Maker portal
- Power Automate portal
- Power Platform admin center
- Teams admin center
- Windows PowerShell


You may not be familiar with all these tools. The instructions will provide prescriptive guidance and screenshots to help you perform any required  steps.


<!--  --Taking this out for GitHub instructions--

# Working in the lab environment

---

### Test fields in the Instructions pane
As you configure the environment to support the agents, you'll need to collect a lot of information. To ensure that You've the best possible experience, we've included text fields in various places in the instructions. you'll be asked to paste information into these fields. The information is saved in variables so that you can easily use the values later in the lab when needed.

### The Type Text icon  
The **Type Text** feature  (![hut7bsbc.jpg](../../media/hut7bsbc.jpg)) used in this lab will send the specified text string to the active window in the virtual machine. Always compare the text in the lab document with the typed text in the virtual machine and verify that the expected text displays.

For larger code segments, consider using the **Copy** button and then pasting the text by right-clicking or using **CTRL+V** in the virtual machine.

![q1n1yy18.jpg](../../media/q1n1yy18.jpg)

---

### Lab credentials
The credentials required for accessing the virtual machine are available in the instructions pane on the **Resources** tab. They're also included in the instructions themselves.

You can use the **Type Text** feature to automatically send the specified username and password to the active window in the virtual machine. Ensure that the credentials are entered correctly by comparing them with the values in the **Resources** tab.

---

### Saving your progress  
To save your progress, in the upper-right corner of the screen, select **Exit Lab**. Then, select **Save Progress and Exit**. This will ensure that your work is preserved for future sessions.

{: .warning } Selecting **End Lab** will terminate the lab instance. Do not select this option until You've completed the entire lab.

---

### Diagrams and screenshots  
All visuals in the lab instructions are selectable. By selecting any diagram or screenshot, you can open a zoomed view in a separate window for better clarity and analysis.


---

### Split Window feature  
If You've a computer with multiple screens, you can use the **Split Window** feature to place the lab instructions on a separate screen, making better use of your screen real estate. 

To enable this feature:  

1. In the upper-right corner of the instructions pane, select **Settings** (the **&#x2699;** icon).   
2. Select **Split Windows** at the lower of the **Settings** pane.

This will help you keep the virtual machine and instructions visible simultaneously for a more efficient workflow. -->




### Architecture
The Finance and Operations Demo environment provisions a number of related technologies. The following diagram shows key components and their relationships.


![Designer.png](/media/Designer.png)


Finance and Operations apps support two fundamental types of Copilot features:

Sidecar features - These features are opened in a pane on the right side of the page. They provide natural-language chat features.
Summary and content-generation features - These features are embedded in each application.

![0p9bx0sz.jpg](/media/0p9bx0sz.jpg)


### Exercises

This lab has the following exercises:
 - Request and validate a Finance and Operations Demo environment 
 - Configure global settings for the demo environment