# B2B Live Training Registration

> This is an autoresponder for B2B Live Training submissions.

## Configuration:
Run as TZ, Notify Immediately on Error, onFormSubmit throughout

## Relevant Quips

https://salesforce.quip.com/aonPAe6ruImc

## Relevant Form

https://docs.google.com/forms/d/e/1FAIpQLSeS_NgPSUXtVGDJwRUdYa0mRQzV3z1_f1sQmHFgtwppi3NRlA/viewform

## Relevant Sheet

https://docs.google.com/forms/d/1rCXZE7Qx9VBHBDNQTGECKbM_5d1s4ISnLYkPxWpLCUo/edit#responses

## Deployment

Code.gs is loaded into Extensions > Apps Script (from the top menu of sheet)

## How to launch or test

Code is invoked via the onFormSubmit method. You can submit the form using your company or personal email address.

# TODOs:

1. Add a digest function to send at a fixed internal instead of sending every email live (per the Slack Channel approach): https://github.com/tzarrsf/commerce-slack-channel-request-form
2. Make it so you don't have to leave the gmail interface (uber lazy Tom pet project)
