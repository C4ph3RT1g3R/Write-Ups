# Basic Server Maintenance and Cleaning [NG]
Author: Steven Rodriguez
Framework Category: Operate and Maintain
Specialty Area: Systems Administration
Work Role: System Administrator
Task Description: Conduct periodic system maintenance including cleaning (both physically and electronically), disk checks, routine reboots, data dumps, and testing. (T0435)

## Scenario
Several of our employees have been complaining about computers not functioning properly and in turn causing a negative effect on work productivity. I've come to the conclusion that DASwebs is in need of a regular maintenance plan. This plan needs to cover basic maintenance that will be ran often as well as more thorough maintenance that will be done less frequently. You will create a detailed guide as to what types of maintenance will be done and maintenance scheduling. If accepted, your guide will be what we have interns using to conduct said maintenance.

## Additional Information
More details and objectives about this challenge will be introduced during the challenge meeting, which will start once you begin deploying the challenge. Hybrid challenges do not have checks, their only deliverable being usually a report or plan. This should be done within the documentation tab of the workspace once the challenge is deployed. Below the main documentation section be sure to include a tagged list of applications you used to complete the challenge.

Your username/password to access all virtual machines and services within the workspace will be the following...
Username: playerone
Password: password123

The username/password used to access the Firewall's web interface within the workspace will be the following...
Username: admin
Password: password123

## Meeting Notes
<div id="header" align="left">
  <img src="https://github.com/CodebenderCate/Write-Ups/blob/main/files/Nice/Images/phpnVMu8p.png"/>
</div> 
## Virtual Machines
<div id="header" align="left">
  <img src="https://github.com/CodebenderCate/Write-Ups/blob/main/files/Nice/Images/phpc39yAn.png"/>
</div> 

## My Solution

### Tools Used
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| windows update | Firewall | device manager | backup and restore | local security policy | network adapter settings | windows security | access control |
| this pc | network & internet settings | bios update | compressed air | external storage device | cloud backups | dedicated teams | routines |
### Documentation
'Workstation-Desk' shows that it is a 64 bit operating system with 4.0 GB RAM. All security checks are showing as "okay" except virus protection whivh found one threat, and there does not appear to be a network error. The device is missing updates, but the network policy forbids the workstation user from updating the system themselves. Many of the local security policies in security policies are accessble by end users and the menu is not locked to admin-only access. Local security policies are outdated or inappropriate for the desired company setting. The accessible disk drives include the onboard drives, as well as a flash drive and a network shared drive. These do not appear to be defragmented, compressed, or "cleaned" by the system. The share drive grants open access to a file called "employee performance reviews" which should be confidential. The flash drive appears to have used space, but even with "show hidden files" activated, there are no files visible. This presents a security concern.

The reasonable assumption in this scenario is a lack of maintenance on both the machines and the network. The solution would be the following:

 - **Physical Maintenance**: clean dust out of the machines, check for bad cables or hardware, update or upgrade physical hardware as required.
 - **Software Maintenance**: Regularly update the operating system, directory domain, outdated users, passwords, admin privileges, access management/monitoring, software and security updates (etc), disk checks/cleanups, and other digital maintenance. This should be updated and monitored regularly by a designated team and not left to a "when I remember" strategy.
 - **Data Maintenance**: Information which is considered confidential should be regularly monitored, checked (for inactivity or breaches), backed up, and protected with access management and security protocols.
 - **"Regularly"** - A schedule and routine should be created based on the requirements for the machinery and data, not the requirements of the users or admins, and the regularly scheduled maintenace should be compartmentalized between teams based on area of need rather than randomly assigning tasks to random persons - Security audits should be a separate team from the physical maintenance
 - **Audits and Management**: The system has a virus on it, therefore a routine security scan would be wise, to determine whether a threat or risk exists and what to do about it. If a threat is found, then threat analysis and incident response needs to be made to know why it happened and how to prevent it happening again.
 - **Reboots and Restores**: Information can be updated, but we need to make sure the machines are capable of maintaining those updates. Regularly rebooting machines can insure that the updates are properly implemented, and if the information is lost on reboot, then a restore needs to take place to attempt to identify and resolve the error of loss.
