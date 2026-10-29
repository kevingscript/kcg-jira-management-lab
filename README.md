
# KCG Technology | Jira Service Management Lab

A hands-on IT Service Management (ITSM) lab demonstrating service request workflows, approval automation, ticket lifecycle management, SLA monitoring, and technical documentation using Jira Service Management.

## Project Overview

This project explores the configuration and validation of an IT service desk environment through a controlled Jira account access request.

The lab simulates an IT Support workflow, from customer portal submission through approval, support assignment, investigation, resolution, and closure.

The objective is to demonstrate practical ITSM skills while maintaining documented evidence of workflow behavior and administrative actions.

## Technologies and Tools

- Jira Service Management
- Jira Automation
- Jira Customer Portal
- Jira Work Item History
- Jira Approval Workflows
- Jira SLA Tracking
- Markdown
- macOS Terminal

## Lab Environment

**Service Desk:** KCG Technology IT Service Desk  
**Test Work Item:** IT-1  
**Request Type:** Request a new account  
**Final Status:** Closed  
**Resolution:** Validation Complete

This is a controlled lab environment. No production account provisioning or access permission modifications were performed.

## Skills Demonstrated

- IT Service Management (ITSM)
- Service Request Management
- Jira Service Management Administration
- Approval Workflow Validation
- Jira Automation
- Ticket Lifecycle Management
- SLA Monitoring
- IT Support Documentation
- Customer Communication
- Workflow Audit Trail Review
- Access Request Governance
- Principle of Least Privilege

## Workflow Validation

The IT-1 test request successfully progressed through the following stages:

1. Waiting for approval
2. Waiting for support
3. In Progress
4. Resolved
5. Closed

The exercise verified automated approver assignment, approval processing, IT Support assignment, internal documentation, customer-visible communication, and resolution tracking.

### SLA Results

| SLA Metric | Target | Result |
|---|---|---|
| Time to first response | 12 hours | Met |
| Time to resolution | 48 hours | Met |
| Time to close after resolution | 60 hours | Met |

All three SLA metrics displayed successful completion indicators for the test request.

## Technical Documentation

For the complete workflow walkthrough, validation steps, SLA observations, and supporting screenshots, see:

[IT-1 Workflow Validation Report](docs/it-1-workflow-validation.md)

## Evidence

The repository includes three screenshots documenting the controlled test:

1. Final request status and SLA results
2. Request lifecycle and work item history
3. Approval decision and audit trail

Evidence files are located in:

`evidence/it-1-access-request/`

## Project Limitations

This exercise validated Jira Service Management workflow behavior for a single controlled test request.

It did not include actual account creation, permission assignment, production provisioning, or integration with an external identity provider.

The results demonstrate workflow functionality within the tested environment, not enterprise-wide service desk performance.

## Project Status

**IT-1 Workflow Validation: Completed**

Additional Jira Service Management lab exercises may be added as the project develops.

