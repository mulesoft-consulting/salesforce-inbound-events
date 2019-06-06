# salesforce-inbound-events

This project contains source for a Salesforce lightning Component, that listens on event /event/Mule_Event__e, and pushes a toast notification to the user's page in Salesforce, where the user is logged in.  This component would be added to the page where the toast is desired to be displayed.

Platform Event Mule_Event__e contains two fields:
1. Message__c Text(255)
2. TargetUserId__c Text(18)

The target user id field can be used to filter events to ensure that specific events are only displayed to the targeted user.
