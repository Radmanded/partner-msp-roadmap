# procellis-msp
Resources for the msp practice


### Survey Assessment
In 32 questions the Alys Assessment will help you to understand how you compare with your MSP peers, prepare you a personalized report with recommendations as to how you can develop your organization.

https://www.candefero.com/survey/surveystart.php?id=983

### Cisco Partners Elevate

https://app.canapii.com/login?e=cisco-provider-elevate


### How are people selling in MSP?


### Simplified MSP
https://www.youtube.com/watch?v=iG6dShv5r-Y&ab_channel=MichelleRagusa-McBain

![CleanShot-Google Chrome202207-12 at 14 44 37](https://user-images.githubusercontent.com/9085386/178580802-73c4a756-fa99-4136-b0e3-d754fb17602d.png)

### Cisco Community 

https://community.cisco.com/t5/cisco-insider-user-group/ct-p/ccp-home?ccid=cc001547

### Cisco Meraki Vitual MX on AWS Cloud

https://aws-quickstart.github.io/quickstart-cisco-meraki-sd-wan-vmx/

**Quick Start**
Uses CloudFormation templates to deploy
http://aws.amazon.com/quickstart/


### Meraki MSP

https://documentation.meraki.com/General_Administration/Managed_Service_Providers_(MSPs)

Best Practices
When creating new networks and organizations as an MSP, there are some best practices that increase the ease of management and prevent scalability problems as the service grows.

Clone new customer organizations from an existing organization to preserve SP specific features
Some settings, such as branding or EoGRE, must be enabled by Support. Cloning from an organization that already has these features will prevent an extra call to Support as the SP specific features are retained during the cloning process. 
Please see the linked article for information on what settings are carried over during the cloning process
Create networks and organizations using a generic shared address, such as meraki@example.com
Multiple admins can easily access and share this account
As admins change, the account remains the same
This account can be tied to a mailer list to ensure that, in the event of an alert or licensing issue, multiple parties are notified 
Additional admins can still be added with their own e-mails, after creation is done using the generic account
Create separate organizations for each customer/company, since each organization will share the following across its networks/devices:
User accounts
Cisco Meraki VPN peers
3rd party VPN peers
Licensing co-termination and feature set 
