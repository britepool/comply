name: Products and Services Narrative
acronym: PSN
majorRevisions:
  - date: Jan 2 2020
    comment: Initial document
---

# Products Narrative

BritePool's mission is to keep the open web secure and free for users.

# Products

## User Portal

BritePool provides a platform to consumers where they can contribute a minimal amount of information about themselves (name & email address) and be rewarded.  Users get a degree of transparency and control. Transparency comes in the form of reports about what data we have about them, where their data is used and for what purpose(s). Control is given to the user to revoke permission to use their data at any time and ask that it be deleted.

### Architecture

The User Portal is a web app (website) that collects a small amount of information via the user's browser or device.  It allows a user to manage their account, receive educational material about privacy and security on the internet, to be rewarded for their data contribution, gain transparency into how their data is used and by whom and to control whether it is shared.  User information is submitted from the browser to webservices and stored in long term storage for persistance across requests.

### Security Considerations

Security considerations for the User Portal include transmission and storage of small amounts of user data, authentication of a user, and safe guarding of a user's account and data.

## Identity Resolution Services

BritePool provides identity resolution services to partners across the open web.  For every user, BritePool generates a random string of characters called a BritePool ID (BPID).  This BPID represents the concept of a person.  Data that could be used to identify or contact a specific individual in the physical world is never provided to a partner that does not already have it.  The only information provided by BritePool to any partner is the BritePool ID. (BPID)

### Architecture

The Identity Resolution Services consist of client scripts/code that execute in the context of a device or browser, web services that send and receive data, as well as short and long term storage of user, partner and BritePool information.

### Security Considerations

Security considerations for the Identity Resolution Services include transmission and storage of small amounts of user data, authentication of a user or partner system, safe guarding of a user, partner and BritePool accounts and data at rest and in transit.

# References

## Narratives

- Organizational Narrative
- Security Narrative
- System Narrative

## Policies

- Application Security Policy
- Datacenter Policy
- Log Management Policy
- Password Policy
- Security Incident Response Policy
- Risk Assessment Policy

## Procedures

- Access Review, Onboarding, & Offboarding
- Patching
- Alert Monitoring
- Log Review
- Penetration Testing