---
layout: post
title:  "Arma 3 Administrative Bot"
date:   2024-10-19
categories: ["projects"]
author: "VeebS"
---

<h1>13th MEU Custom Discord Bot</h1>

This post showcases a custom-built Discord bot developed for the **13th Marine Expeditionary Unit (MEU)** Arma 3 realism unit.  
The bot was designed to automate and streamline administrative processes, improve efficiency for staff, and enhance the member experience.  

<br>

<h2>Overview</h2>

The bot is fully integrated with **MongoDB** for persistence and data backup. This ensures that no data is lost in the event of corruption or failure. Every system is automated, role-based, and designed to reduce manual work for staff while maintaining accountability and accuracy.

<br>

<h2>Core Features</h2>

<h3>Role & Member Management</h3>

- **Promotion & Demotion Commands**  
  Automated role assignment and removal with automatic name changes.  
- **Discharge Commands**  
  Full automation of role stripping/assignment upon member discharge.  
- **Interview Commands**  
  Automates interview outcomes with role management and name adjustments.  
- **Leave of Absence (LOA) Submissions**  
  Role-based LOA submissions requiring admin authorization, with automated role handling.

<br>

<h3>Staff Tools</h3>

- **Staff Shop Ticketing System**  
  Complete ticketing system with archival functionality for staff management.  
- **Probationary Tracker**  
  Embed-based tracker for probationary members, fully automated with role management.  
- **Error Logging System**  
  Any bot errors are automatically logged into a tickets channel for monitoring and debugging.  

<br>

<h3>Member Profile System</h3>

A comprehensive **profile system** integrated with MongoDB to track individual member history and accomplishments, including:

- Ribbons, promotions, demotions, NJPs, and JPs  
- Transfers, join date, qualifications, instructor qualifications  
- Interview question responses from enlistment  
- Current rank and progression  

<br>

<h3>Operational Features</h3>

- **Server Status Embed**  
  Displays real-time server information using API-linked BattleMetrics data.  
- **Attendance Marker**  
  Automates attendance for operations and training sessions, listing members per event.  
- **Automatic BCT Scheduling**  
  After successful interviews, BCT sessions are automatically scheduled.  
- **Join Messages & Ready Command**  
  New members receive an automatic join message with a “Ready” button, notifying admins they are prepared for their interview.  

<br>

<h2>Technical Highlights</h2>

- Built with **MongoDB** integration for reliability, persistence, and disaster recovery.  
- Fully modular design for role-based automation across all commands.  
- Embeds and ticket systems for clean and organized Discord integration.  
- Error tracking ensures issues are logged and resolved efficiently.  

<br>

<h2>Conclusion</h2>

The 13th MEU Discord bot provides a **fully automated administrative framework** tailored to the needs of a large Arma 3 realism unit.  
By integrating role automation, attendance, staff tools, and persistent profiles, the bot reduces manual overhead and ensures smooth day-to-day operation of the unit.

