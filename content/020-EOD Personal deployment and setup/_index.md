---
title: "EOD Personal deployment and setup"
chapter: true
weight: 20
---
![Title](/images/UserConfig.jpg)
## Objective

By the end of this section you will know how to deploy and setup Azure Environment on Demand (EOD) that will allow you to create a Personal environment in the Genesys Engage Cloud production tenant. You will be able to demonstrate cloud functionality in the same environment used by customers.


![Deployment](/images/UserConfig2-768x300.jpg)
## Deployment of your Azure EOD Personal Environment

Creating Your Configuration
 1. Go to the navigation in GDemo and select "Environments" from the Genesys Engage Cloud menu.
![Environments](/images/file_1604107212047_gecEnvironments.jpg)

 2. You will create a configuration and define the settings.
![Settings](/images/file_1604373858266_gecEODPersonalNew.jpg)


 4. Select Microsoft Azure as the Cloud Provider.
 5. Select EOD Personal as the type of Environment that you want to provision, and then click "Create EOD Personal".
 6. Complete the Properties page and click "Provision"..
 7. It may take a few minutes to provision. This is normal.

Provisioning Completed
 1. When finished, you will you will see your new Azure Personal EOD in your list of Live Environments.
 2. Note the icon that designates your new EOD as provisioned on Azure.

Retrieving Configurations at later time
 1. At any time you can retrieve your configuration, such as Unit ID, agent password, etc., by going to 'My Live EODs', and then clicking the 'View EOD Configuration' icon.
 2. On the Configuration page, note this button which will give you a PDF version of your configuration.
 3. Note that your Unit Type is designated as Azure.

## Opening your Azure EOD Personal Portal

Once you have deployed your EOD Personal, open the Azure EOD Portal here:

 [Azure EOD Portal](https://portal-1007-westus2.prod001.genesysengage.com/)

>The Portal is accessed directly in the browser. Without VPN and without the GDemo View VDI. This is a major distinction between EODs provisoned on Azure and those >provisioned on AWS. 

## Customization and Supported Channels

The comprehensive guide to customization and supported channels, with numerous instructions and how-to, is available [here]

## Recommended Demonstrations

Once you have your Azure EOD Personal deployed, and are familiar with connecting, there are additional demonstrations available on GDemo where you can use your EOD. Realize that your 'EOD Personal' is sometimes referenced as 'PEC Environment' in other instructions. 

Treasure Bank

This is a CrossPlatform demonstration that shows multiple Pure Engage Cloud (PEC) products in the cohesive storyline of a customer's interaction with a fictional bank website. Uses the PEC Environment throughout. [link]

GSol

This is a CrossPlatform demonstration of various scenarios using the GSol website. Uses the PEC Environment in the PureEngage Cloud tab of the demonstration. [link] 

Predictive Engagement Personalized xP

This is a CrossPlatform demonstration that creates a personalized environment to help your prospects visualize what they could get by powering their corporate website with Genesys; using the Demo Builder Wizard. Uses the PEC Environment in the PureEngage Cloud tab and select Azure environment of the demonstration. [link]

CX Contact

This demonstration allows you to fully explore the CX Contact UI including processing a live interaction. Please refer to the CX Contact demonstration for futher details. [link]

IWD

This demonstration allows you to demo IWD scenarios including using IWD Manager in read-only mode. Currently there are two use cases

Treasure Bank Loan Application: [link]
GInsurance Insurance Claim: [link]

## Different types of EOD

Here are all EOD types that we currently support.

WORKSHOP Units
Tailored for training of users on the platform during TOIs...
Can be set up to for up to 50 attendees
Build your own Application (Routing / IVR / Bot / Messaging) using Designer / BotEngine
Each attendee has their own agent, and a shared admin account
1 shared DID per region
Expires like PureEngage-PODs
POC Units
Can be set up to for up to 50 agents
Dedicated DIDs / Task endpoints
Build your own Application (Routing / IVR / Bot / Messaging) using Designer / BotEngine
Extended administrator privileges
Can be associated with a PureCloud OOD for custom Predictive Engagement
Expires like PureEngage-PODs

## Help

If there are inaccuracies or issues with this Azure EOD Personal Deployment demonstration, or if you would like to give feedback on this demonstration, please use this link. Include a screenshot(s) if possible.

If you have general demo or larger issues,
please contact Global Technical Sales as usual.

## Notes

Platform stability

This Azure EOD is a production tenant on the Genesys Engage Cloud platform.  The availability of the platform and components is managed by the DevOps cloud team, therefore  we are not responsible for the service level and availability of the platform.

Application cache in Designer 

To speed up the availability of a change you made in a Designer application, we recommend to follow these steps:

Save your application by using the [Save Flow] button
Create a new build for your application by using the [Build] button, then enter a Label, then hit [Build]
Go back to the list of applications
Select the line with your application
Select the active stream
Click on Builds and select your new build
If you use the default method (Latest Published), you will instead have to wait for several minutes until your latest changes are live.
