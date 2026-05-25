# Moodle LDAP Learning Platform

## Overview

This project demonstrates a Moodle learning platform deployed on Ubuntu Server and integrated with Windows Server Active Directory authentication using LDAP.

The goal was to create an internal company-style learning platform where users can log in using their own domain credentials.

## Project Goals

- Deploy Moodle on Ubuntu Server
- Configure Apache, PHP, and MariaDB
- Connect Moodle to Windows Server Active Directory
- Enable LDAP authentication
- Test login using domain users
- Configure scheduled backups

## Technologies Used

- Ubuntu Server
- Apache
- PHP
- MariaDB / MySQL
- Moodle
- Windows Server
- Active Directory
- LDAP
- Cron
- mysqldump
- VirtualBox

## Features Implemented

- Moodle installed on Ubuntu Server
- Database configured with MariaDB
- LDAP authentication connected to Active Directory
- Domain users can log in to Moodle
- Scheduled backup using cron and mysqldump

## Screenshots

Screenshots will be added in the `screenshots` folder.

Planned screenshots:

1. Moodle login page
2. Moodle admin dashboard
3. LDAP authentication settings
4. Active Directory test user
5. Successful Moodle login with domain user
6. Backup script or backup folder

## What I Learned

- How to deploy a web application on Linux
- How Apache, PHP, and MariaDB work together
- How Moodle authentication can be connected to Active Directory
- How LDAP login works
- How to automate backups with cron
- How to troubleshoot Linux and Windows Server integration

## Future Improvements

- Add HTTPS with SSL certificate
- Add Google OAuth login
- Improve backup storage
- Add monitoring
