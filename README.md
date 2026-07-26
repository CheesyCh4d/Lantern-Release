# Lantern — Releases

Downloadable builds of **Lantern**, an tool for connecting to Powerschool
running SQL based reports.

This repository hosts release binaries only. Each version is published under
[**Releases**](../../releases) with installers for macOS, Windows, and Linux.

## Download

Grab the latest build from the [Releases page](../../releases/latest):

| Platform | File |
|----------|------|
| macOS    | `Lantern-<version>-<arch>.dmg` |
| Windows  | `Lantern-<version>-x86_64.zip` (or `-setup.exe`) |
| Linux    | `Lantern-<version>-<arch>.AppImage` |


## What is Lantern?

Lantern gives educators (Principals, Counselors, Teachers, etc)
an easy to use interface for running SQL reports against
PowerSchool.

Front end features include:
 -- Report Categorization & Favoriting
 -- Scheduled Report runs and delivery via SFTP/email
 -- The ability to Follow report creators
 -- Build, Save, and Export Pivot Tables based on report results
 -- Build, Save, and Export Charts based on pivot table results
 -- Share report results via direct link

Back end features include:
 -- Multiple connection methods
   -- Lantern can be configured to work through a Cloudflare Tunnel, or device VPN
 -- User Account Management
 -- Location Management
 -- SFTP Connection Management
   -- Store Multiple SFTP connections in order to meet your district's needs.
 -- Database Connection Management
   -- Connect directly or use Bitwarden Secrets Manager to mask your connection information.
 -- Exportable Audit Log
 -- Ability for admin to run SQL against Lantern's internal database
 -- Pre-Configured templates for building t-list SQL reports

Database Administrator Features:
 -- Full IDE for writing code directly in Lantern
 -- Ability to browse, search, and favorite all database tables
 -- Full Data Dictionary integration for Powerschool
 -- Save code written often as "Snippets"
 -- Joins written often can be saved and reused
   -- Lantern will suggest saving Joins if they're not in your catalogue
 -- "PII" flag and configuration per report
 -- Export query results in multiple formats, or move directly to the Pivot Table & Chart Builder


Lantern does not collect or store any student information.
Lantern does not collect or store any user information.
Your district, your data.
 

****A valid license is required to run reports against live data.**

## Support

Questions or access requests: https://lanternreports.com

---

© 2026 Chad Jacks. All rights reserved.
