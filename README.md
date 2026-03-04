# UMU Unified Booking Platform

A modular, multi-institution booking and allocation platform for Uganda Martyrs University and its affiliates (on-campus hostels and Nkozi Hospital), built with Laravel and MySQL.

## What this project does

- Academic Booking: Reserve lecture rooms, labs, equipment (e.g. projectors), and the university conference hall with conflict-aware scheduling and approvals.
- Hostel Allocation: Manage semester-based room/bed allocations, live occupancy, and basic maintenance reporting for on-campus hostels and apartments.
- Hospital Services: Book appointments, request asynchronous consultations, and trigger a structured emergency escalation workflow from students to school health staff to Nkozi Hospital on-duty staff.

## Tech stack

- Backend: Laravel (PHP 8+), RESTful APIs, Blade or SPA-friendly JSON responses
- Web server: Nginx (LEMP stack on Ubuntu/WSL)
- Database: MySQL
- Auth & security: Central authentication, role-based access control (RBAC), audit logs
- Notifications: Email/SMS for confirmations, reminders, and emergency escalations

## Project goals

- Replace scattered paper/WhatsApp/phone workflows with a unified system
- Reduce double-bookings, favoritism, and no-show waste
- Provide reliable utilization and health data for institutional decision-making
- Ship an open-source, well-documented codebase that can be maintained beyond the original student team

## Status

Early development / prototype. Initial focus: Academic Booking module and core platform (auth, roles, admin).
