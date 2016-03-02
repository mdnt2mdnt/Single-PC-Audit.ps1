# PS---Single-PC-Audit
This script will create a report that lists the Computer Specs for a single computer (not for domain wide scanning)

CPU speed, Processor Type
BIOS Info
OS Information
Hard Disk Information (includes ALL attached drives)
RAM Information
Network Connection Information
Software Inventory 

Running this script would be useful when issuing out laptops to remote users / sites. 

After the script is run, it will open up Internet Explorer to show the results. 
IE is forced b/c limitations on Chrome (havn't tested Firefox) to be able to display the HTML output from Powershell
