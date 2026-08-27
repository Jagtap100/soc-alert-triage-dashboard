# SOC Alert Triage Dashboard

## Overview
A practical SOC alert triage project demonstrating how security alerts can be reviewed, prioritized, investigated, and escalated.

## Alert Triage Workflow

| Stage | Action |
|---|---|
| 1. Alert Received | Review alert title, source, timestamp and affected asset |
| 2. Validate | Check whether the alert is a true or false positive |
| 3. Prioritize | Assign severity based on risk and impact |
| 4. Investigate | Analyze logs, users, hosts and related events |
| 5. Classify | Categorize the alert based on observed activity |
| 6. Escalate | Escalate confirmed or high-risk incidents |
| 7. Document | Record findings, evidence and mitigation steps |

## Severity Levels

- Critical – Immediate response required
- High – Potentially serious security incident
- Medium – Requires investigation
- Low – Low-risk activity or informational alert

## Example Alert

Alert: Multiple Failed Login Attempts  
Event ID: 4625  
Severity: Medium  
Status: Under Investigation

### Investigation
- Review affected account
- Check source IP and hostname
- Review authentication timeline
- Look for repeated or unusual activity
- Correlate related security events

### Recommended Action
If malicious activity is confirmed, escalate the alert to the appropriate SOC analyst or incident response team.

## MITRE ATT&CK Mapping

Potential techniques should be mapped to the appropriate MITRE ATT&CK technique after investigation and validation.

## Skills Demonstrated

- SOC Alert Triage
- SIEM Monitoring
- Log Analysis
- Windows Security Events
- Incident Investigation
- Alert Prioritization
- Incident Escalation
- Security Documentation

## Disclaimer

This project is for educational and portfolio purposes and uses simulated/example investigation scenarios.
