# Kitsu Security Policy
## Reporting security problems to Kitsu

**DO NOT CREATE AN ISSUE** to report a security problem. Please
send an email to nuck@kitsu.io or help@kitsu.io

## Security Point of Contact

The security point of contact is [Emma](https://github.com/NuckChorris). Emma responds to
security incident reports as fast as possible, within one business day at the latest.

If Emma does not respond then please contact help@kitsu.io so somebody can nag her.

## Incident Response Process

If an incident is discovered or reported, the following process will be used to respond,
and we will communicate with you as we work on each step.

### 1. Assessment

Find the root cause, nature and scope of the issue. We need to answer the following:

- **Is it still ongoing?** If so, top priority is to stop it.
- **Who knows about it?** Ideally limit exposure until we can respond.
- **What was exposed?** Determine how large the issue is and who will need to be notified.

### 2. Containment

Once we have context on the incident, we will immediately begin work on temporary
containment. This is not expected to be long-term solutions, just enough to limit
exposure while we work on actual remediation. This may consist of shutting off features
temporarily or adding WAF rules.

If temporary containment is not feasible or remediation is easy, we may skip this step
and proceed directly to remediating the issue. If we make this decision, we will notify you.

### 3. Remediation

After the initial assessment and containment, we will begin work on the long-term
remediation process. This may involve larger changes than containment, and will
culminate in public announcement of the vulnerability.

### 4. Postmortem

Once the incident is resolved, we will look at the root cause and our own incident
response process to learn from it.  The result of this will be a list of various
process and code changes to make longer-term to prevent similar incidents in future or
improve our incident response process.  If you are willing, we like to include you
in this step to give us feedback!
