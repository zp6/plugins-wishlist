# Maintainer Response SLA Guidelines

## Overview
This document establishes Service Level Agreements (SLAs) for maintainer response times on bounty-related PRs.

## Response Time Targets

| Priority | Initial Response | Full Review | Decision |
|----------|-----------------|-------------|----------|
| Critical | 48 hours | 5 days | 7 days |
| High | 72 hours | 7 days | 14 days |
| Normal | 7 days | 14 days | 21 days |
| Low | 14 days | 21 days | 30 days |

## Escalation Process

### After 7 Days No Response
1. Automated reminder comment on PR
2. Ping maintainer in linked issue

### After 14 Days No Response
1. Escalate to project admin
2. Flag in weekly sync
3. Offer alternative maintainer assignment

### After 21 Days No Response
1. Mark as "Needs Attention"
2. Contributor can request maintainer reassignment
3. Bounty timeline extended proportionally

## For Contributors
- Bump PR after 7 days of silence
- Document waiting time in issue
- Request alternative reviewer if needed

## For Maintainers
- Acknowledge PRs within SLA window
- Provide actionable feedback
- If busy, request co-reviewer
- Update status labels regularly

## Metrics Tracked
- Average first response time
- Average merge time
- Stale PR count
- Contributor satisfaction score
