# Tier 1 Help Desk Diagnostic Frameworks

This document outlines structured troubleshooting and security frameworks I use in Windows-based help desk environments.

They reflect my real-world experience supporting users (former clients, coworkers, friends), applications, networking, and systems.

**STABLER Troubleshooting Model**

A structured troubleshooting workflow that I use in my IT Support role.

S – Scan the Environment

Review system behavior, error messages, recent updates, and environmental context. Collect data.

T – Talk to the User

Clarify symptoms, timing, scope, and impact. Confirm what changed. Collect more data. 

A – Assess the Issue

Categorize the issue using the UNAS model (User, Network, Application, System). Work on narrowing the scope. 

B – Build Hypothesis

Form testable root cause theories based on the evidence that I have collected.

L – Launch Fix

Apply the lowest-impact corrective action first. Apply a targeted intervention or reconfiguration. 

E – Evaluate Outcome

Confirm resolution with the user. Test to see if it worked. Escalate, if needed.

R – Record and Document

Log steps taken, commands used, findings, and resolution in the ticketing system. Follow up with the user.

**UANS Diagnostic Model**

The UNAS model helps me quickly identify where an issue originates.

It reflects my hands-on experience supporting the following areas:

**U** – Users

Login failures

Password resets

MFA troubleshooting

Account unlocks

Role-based access issues

Permission corrections

Profile issues

**A** – Applications

Microsoft 365

Outlook configuration and profile repair

SMTP configuration

SharePoint access issues

Microsoft Teams support

Event Viewer diagnostics

Task Manager performance analysis

**N** – Networking

TCP/IP configuration

Wi-Fi troubleshooting

NIC validation

Gateway reachability

DNS resolution

IP lease renewal

External connectivity testing

**S** – Systems

Windows 10 / Windows 11

Device Manager troubleshooting

Driver conflicts

Firmware-based printer drivers

Peripheral setup

Hardware diagnostics

OS-level troubleshooting

**TINGEDE Network Diagnostic Model**

A repeatable network troubleshooting guide.

T – TCP/IP Configuration

Verify IP address, subnet mask, and gateway using ipconfig.

I – Interface Status

Confirm NIC is enabled and the driver is working correctly.

N – Network Connectivity

Ping local gateway.

G – Gateway Validation

Confirm proper routing and gateway responsiveness.

E – External Ping Test

Ping a public IP address (e.g., 8.8.8.8).

D – DNS Resolution

Test domain resolution using nslookup or domain ping.

E – Escalate if Needed

Escalate if upstream routing, firewall, ISP, or infrastructure issue is suspected.

This ensures network troubleshooting is systematic and documented.

**LAPNR Security Awareness Model**

A security-first review model used during account and access-related troubleshooting.

L – Logins

Validate the authentication method and login history.

A – Accounts

Confirm correct account, status, and lockout state.

P – Permissions

Review access rights and group membership.

N – Networks

Confirm access context (VPN, internal network, remote access).

R – Roles and Least Privilege

To ensure permissions align with the role and follow least privilege principles.

This model reinforces secure support practices during Tier 1 account management tasks.

**Philosophy**

These frameworks are designed to:

Reduce organizational IT risk

Reduce reactive troubleshooting

Increase documentation consistency

Reinforce security-informed decision making

Create repeatable support processes

Minimize downtime and maximize uptime 

Increase the stability of the business


