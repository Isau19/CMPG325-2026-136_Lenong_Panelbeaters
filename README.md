CMPG 325 Computer Networks Project
Lenong Panelbeaters (Rustenburg)
Student Information

Initials and Surname: I. Sithole

Student Number: 47255242

Project ID: CMPG325-2026-136

Client ID: CLI-136

Organisation: Lenong Panelbeaters (Rustenburg)

Industry: Automotive

Project Overview

This project was completed as part of CMPG 325 Computer Networks. The objective was to design, implement and test a network solution for Lenong Panelbeaters using Cisco Packet Tracer.

The solution was developed to satisfy the client requirements, implement DNS (Internal Name Resolution Service), provide inter-VLAN communication and accommodate a shared printer zone that can be accessed by multiple departments.


Organisational Network Structure

Administration Department (VLAN 10)
The Administration Department supports the daily business operations of the organisation, including:

Reception services
Customer enquiries
Bookings and scheduling
Finance and accounting
Customer service
Workshop Department (VLAN 20)

The Workshop Department supports operational activities including:

Vehicle assessments
Panel beating and repairs
Maintenance activities
Parts management
Workshop supervision
Server Network (VLAN 30)

This VLAN hosts critical services including:

Internal DNS service
File services
Application services
Shared Printer Zone (VLAN 40)

A dedicated printer VLAN was implemented to satisfy the client change request by providing printing services to both departments.

Assigned Networking Challenge
DNS (Internal Name Resolution)

Internal DNS was implemented using LENONG-SERVER
The DNS service enables users to access network resources using hostnames rather than numerical IP addresses.

Design Constraint
The project required critical services such as file, print and application services to remain available during business hours.

This requirement was addressed by:

Dedicated Server VLAN
Dedicated Printer VLAN
Inter-VLAN routing
Centralised DNS services
Change Request (CR8)

A shared printer zone was implemented to allow both the Administration Department and Workshop Department to access a common printer resource.
Technologies Used
Cisco Packet Tracer
VLANs
Trunking
Router-on-a-Stick
Inter-VLAN Routing
DNS
IPv4 Addressing
Network Testing and Troubleshooting
