# Oracle Admin App (Hospital Data Security, Subsystem 1)

A C# WinForms desktop application for administering users, roles and privileges on an Oracle database. It is Subsystem 1 of a university course project, *Data Security in Information Systems* (HCMUS, 2025-2026), whose wider goal was to secure a hospital database with RBAC, Virtual Private Database (VPD), Oracle Label Security (OLS), auditing/FGA and RMAN recovery.

## Features

- **Login** with an Oracle account (host, port, service name); passwords can be shown or hidden.
- **User / Role management:** create, update, delete and list Oracle users and roles.
- **Privilege management:** grant and revoke privileges to a user or a role, including `WITH GRANT OPTION` and column-level `SELECT` / `UPDATE` on tables, views, procedures and functions.
- **Privilege inspection:** view the privileges held by any user or role.

## Tech stack

C# · .NET Framework 4.8 · Windows Forms · Oracle.ManagedDataAccess (ODP.NET)

## Run it

1. Install Visual Studio 2022 or later with the .NET desktop workload, and have an Oracle database you can connect to.
2. Open `Source/OracleAdminApp/OracleAdminApp.slnx`, restore NuGet packages and run.
3. Sign in with an Oracle account that has the rights to manage users and roles (for example a DBA account). No credentials are stored in the repository.

## Team

Team of 5 (course project). Subsystem 1: foundation and core features (users, roles, grant/revoke, privilege view) by [@DomTriet](https://github.com/DomTriet); UI/UX refinements and extra features by Le Pham Kieu Duyen.

## Note

This repository is a copy of the original team repository `DomQuangMinhTriet/PhanHe1_ATBM_2526` with its full commit history.
