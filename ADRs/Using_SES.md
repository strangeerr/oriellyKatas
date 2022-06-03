# Using AWS SES for email notifications

## Context
We need a way to send emails to users to notify them of events (successful registration, reminders, etc). We could set up an SMTP server and use it to send emails, or use a managed email service like AWS SES.

## Decision
We decided to go ahead with AWS SES. Since it is a managed service, we don't have to worry about provisioning and maintaining the server. It is cost-effective as we pay based on the number of emails sent. An on prem server would be under utilized. AWS monitors SES mails to ensure that they are trustworthy, They won't get marked as spam.

## Consequences
Pros: Cost effective solution. The per email price reduces with scale. Enterprise-ready solution. no hassle of server management
Cons: Paying for the service monthly instead of a one-time upfront investment. Needs some technical knowledge to implement