# Online Job Portal – Connecting Talent with Opportunity

## Overview
Java-based job portal where employers post jobs and candidates apply.
Implements Core Java, OOP, JDBC, MySQL, and a basic Swing GUI.

## Tech Stack
- Java (Core + OOP)
- Swing (GUI)
- JDBC
- MySQL

## Setup
1. Import `OnlineJobPortal` into your IDE (IntelliJ/Eclipse).
2. Run `database/job_portal.sql` in MySQL.
3. Update DB credentials in `src/com/jobportal/util/DBConnection.java`.
4. Add MySQL Connector JAR to project classpath.
5. Run `com.jobportal.main.Main`.

## Features
- Login (Admin, Employer, Candidate)
- Employer can post jobs
- Candidate can view available jobs
- Layered architecture: model, dao, gui, util

