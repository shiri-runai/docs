---
title: Researcher Email Notifications
summary: This article describes researcher notifications and how to configure them.
authors:
    - Jason Novich
    - Shiri Arad
date: 2024-Jul-4
---

## Importance of Email Notifications for Data Scientists

Managing numerous data science workloads requires monitoring various stages, including submission, scheduling, initialization, execution, and completion. Additionally, handling suspensions and failures is crucial for ensuring timely workload completion. Email Notifications address this need by sending alerts for critical workload life cycle changes. This empowers data scientists to take necessary actions and prevent delays.

Once the system administrator configures the email notifications, users will be able to set up personal notifications about their workloads that transition from one status to another. In addition, the user will get warning notifications before workload termination due to project-defined timeouts. Details included in the email are:

* Workload type
* Project and cluster information
* Event timestamp

To configure the types of email notifications you can receive:

1. The user must log in to their account.
2. Press the user icon, then select settings.
3. In the *Email notifications*, and in the *Send me an email about my workloads when* section, select the relevant workload statuses.
4. When complete, press *Save*.


## **Available Notification Types**
### **Workload Notifications**
#### Workload Status Change:

- Creating
- Pending
- Initializing
- Running

- Degraded
- Completed
- Failed
- Stopped

- Deleting

> Note: The system checks the status every 5 minutes. If multiple status changes occur within the same 5-minute interval (e.g., creating, initializing, running), they will be consolidated into a single message to enhance clarity and prevent inbox clutter.

#### Workload Timeout Alerts:

- The workspace workload is about to be stopped due to a timeout
- The training workload is about to be stopped due to a timeout
