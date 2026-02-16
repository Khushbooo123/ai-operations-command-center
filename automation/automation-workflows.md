# Automation Workflows

## Automation 1 — New Lead Notification
Trigger: New Lead Added  
Action: Send Email Notification  

Flow:
[New Lead Added]
→ [Zapier Trigger]
→ [Email Sent]

---

## Automation 2 — Deadline Reminder
Trigger: Daily Schedule  
Filter: Deadline < Today AND Status ≠ Completed  
Action: Email Reminder  

Flow:
[Daily Check]
→ [Filter Condition]
→ [Reminder Sent]
