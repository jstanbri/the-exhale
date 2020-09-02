# Automations #
Throughout, I have used Zapier for several Business Rules processes

## master event update ##
Automated population of master tracking sheets with the critical metrics
Zapier https://zapier.com/shared/9d988605d3f1116d4bd00c26f313d95406453ee1

## email the recordings ##
This Zap is triggered by a new line in the worksheet that includes the recordings details and all the attendees, which automates the mail of the attendees all their replay details
Zapier https://zapier.com/shared/c98b0195e6944fe7e05119525242c87419f2b132

## zoom recording capture ##
When Zoom triggers a new recording capture, a look-up is performed with the master sheets to pull together the cohort email for that meeting. Then a new row is created to trigger the 'email the recording' action above
Zapier https://zapier.com/shared/b77dcea3b98eea71fb1f0010bda9b4467bc22393

## post recording email sending ##
This automation is triggered when a Zoom meeting is completed, and the shareable URL is created. An email is generated which alerts the team that we have a set of customers and a link to send them (kinda internal alert)
Zapier https://zapier.com/shared/8b74bd7a81c97864de262adb844d774de22e785e

