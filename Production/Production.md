# AWS Forecast Approach

### Overview



### Prerequisites

Before you begin looking into the AWS Forecast approach in CloudLabs, ensure you have the following prerequisites:

- Admin access to [CloudLabs Admin Portal](https://admin.cloudlabs.ai/) (If access is unavailable, kindly reach out to your point of contact or [CloudLabs Support](https://docs.cloudlabs.ai/RequestSupport)).

### AWS Forecast Approach

#### Using Cross Account Event Bus as a Target in the Rules

You can send and receive events between event buses in AWS accounts within the same Region in all Regions and between accounts in different Regions as long as the destination Region is a supported cross-Region destination Region.

![](./img/01.png) 

Configuring EventBridge to send events to or receive events from an event bus in a different account include the following:
- On the receiver account, edit the permissions on an event bus to allow specified AWS accounts, an organization, or all AWS accounts to send events to the receiver account.
- On the sender account, set up one or more rules that have the receiver account's event bus as the target.
- On the receiver account, set up one or more rules that match events that come from the sender account.

Scripts:
- Script for Deploying EventBu s rules with a Cross Account EventBus as a Target:

  Link:

- Script for Validating the creation of EventBus rules with a Cross Account EventBus as a Target:

  Link:

- Script for Deleting the created resources in EventBus: 

  Link:

PRICING
1.	EVENT BRIDGE PRICING:
    Link: https://aws.amazon.com/eventbridge/pricing/
    
-  Event Bus:

