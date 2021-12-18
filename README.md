# CheckLogon-Service
"CheckLogon Service" is a Windows service application, written in PowerShell - for automatic management of disabling Windows users by login time.

For every SA machine it is a known Headache for above feasibility, so I took a step in and write-down an Windows application, compiled as a Windows Service that parsing every user Logged-In, Locked, etc... logon time, And Ignore the local Administrators.
