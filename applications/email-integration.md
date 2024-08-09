# Email integration

All email integrations must be appropriately documented both in the context of the application but also the context of the organisation's wider digital architecture. Undocumented interfaces may be interrupted or switched off at any time.

## Sending of email

Any application requiring the ability to send emails will need access to a suitable email relay.

Dorset HealthCare uses the national NHSmail service, which is accredited to the [NHS secure email standard DCB1596](https://digital.nhs.uk/data-and-information/information-standards/information-standards-and-data-collections-including-extractions/publications-and-notifications/standards-and-collections/dcb1596-secure-email), and provides two secure email relay options:

* the Office 365 SMTP server;
* the NHSmail high sending SMTP solution.

The Office 365 SMTP server is [suitable for most applications](https://support.nhs.net/knowledge-base/applications-guide/). The NHSmail high sending SMTP solution can additionally be used where the number of outbound emails may exceed thirty messages a minute. [Further guidance is provided on the NHSmail support website](https://support.nhs.net/knowledge-base/high-sending-smtp-solution/).

There is also an insecure mail relay, however access to this is blocked from Dorset HealthCare's network and only opened by exception.

The sending of email must be controlled to prevent relays being marked as a source of spam by third parties. Mass mailing should be carried out using services dedicated to the purpose and should not use the NHSmail relays.

Connections to any of the NHSmail relays must be secured using TLS 1.2 or greater, and must be made in an authenticated manner using an NHSmail [application account](https://support.nhs.net/knowledge-base/application-account/) with an appropriately configured username and password. Application accounts can be requested from the Digital Services Group via an IT service request.

Architectural approval must be sought before installing or configuring any new email relay within the Trust's infrastructure.

Architectural approval must also be sought for any new flow of anonymous email through either the NHSmail insecure relay or any new email relay.

## Receiving of email

Any application that needs to receive email must be secured using TLS 1.2 or greater, and must have the ability to block and filter spam, phishing and other unwanted emails and attachments.

Such requirements may be met through the application receiving email via an NHSmail [application account](https://support.nhs.net/knowledge-base/application-account/). Such a connection must be secured using TLS 1.2 or greater, and must use an appropriately configured username and password. Account credentials must be protected and must not be shared on the internet.

## Security

All connections to and from official email services must be encrypted and authenticated.

Official email (as well as any material with the additional SENSITIVE marking) must use the NHSmail service, which is accredited to the [NHS secure email standard DCB1596](https://digital.nhs.uk/data-and-information/information-standards/information-standards-and-data-collections-including-extractions/publications-and-notifications/standards-and-collections/dcb1596-secure-email).