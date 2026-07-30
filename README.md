# KC7 - Rap Beef

![KC7 Badge](badge.png)

## Overview

Completed the KC7 **Rap Beef** investigation on the KC7 platform.

This investigation involved analyzing web logs, email logs, and Passive DNS records using Kusto Query Language (KQL) to identify suspicious activity and trace attacker behavior.

---

## Skills Practiced

- Kusto Query Language (KQL)
- Threat Hunting
- Log Analysis
- Email Investigation
- Passive DNS Analysis
- Indicator of Compromise (IOC) Investigation

---

## Key Concepts Learned

- Filtering data using `where`
- Searching with `has`
- Using `between` for time ranges
- Investigating attacker IP addresses
- Following evidence across multiple log sources

---

## Example KQL Queries

### Web Logs

```kusto
InboundNetworkEvents
| where src_ip == "18.66.52.227"
```

### Email

```kusto
Email
| take 10
```

### Passive DNS

```kusto
PassiveDns
| where ip == "18.66.52.227"
```

---

## Outcome

Successfully completed the KC7 Rap Beef investigation and gained practical experience with KQL, log analysis, and basic threat hunting techniques.
