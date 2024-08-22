# Postmortem

## Summary
- Issue Summary:
On November 5, 2023, at 03:45 AM (UTC), there was an unprecedented service disruption that lasted until 11:30 AM (UTC). Our flagship messaging service was affected, and it disrupted communication for 30% of our user base.

Root Cause:
During routine maintenance, a misconfigured load balancer initiated a cascading failure, which led to the disruption of our messaging service. The misconfiguration caused an uneven distribution of traffic, leading to some servers being overwhelmed while leaving others underutilized.

Impact:
The cascading failure affected our flagship messaging service, and it disrupted communication for 30% of our user base.

