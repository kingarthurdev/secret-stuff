# quick note for windows:
install malwarebytes, run a scan WITH THE ROOTKIT DETECTION SETTING ENABLED!!!!!!!!

# Repo for scripts for that one competition (that can't be named or other teams will steal our scripts)
Download and unzip the appropriate files for your system, follow the readme in each of the zip files 

# Windows + server:
The lgpo.zip file is for windows, needed in combination with one of the other baselines/remediations scripts to work. 

Run the windowscp.bat and windowscp.ps1 as admin. If windowscp.ps1 can't be run due to scripts disabled, run this command: Set-ExecutionPolicy -ExecutionPolicy Unrestricted

Another script: https://github.com/simeononsecurity/Standalone-Windows-STIG-Script/blob/master/README.md
This script works only for enterprise systems, but there is anothe link in its readme that is designed for personal systems. 

Another script for windows and server: 
https://github.com/scipag/HardeningKitty

# Another script for ubuntu
https://github.com/Cloudneeti/os-harderning-scripts/blob/master/Ubuntu18_04/Azure_CSBP_Ubuntu18_04_Remediation.sh
: 
# Note regarding ansible ubunto script:
This script needs ansible installed to work, idk if worth the effort. 
https://www.linuxtechi.com/how-to-install-ansible-on-ubuntu/     <-- this tells how to install ansible 

# Other resources: BE SURE TO SKIM THROUGH SCRIPTS, AS MANY CHANGE USERNAMES, USERS, AND PASSWORDS!!!!!
Good basic checklist for linux (supposedly got 400/400pts): https://github.com/Forty-Bot/linux-checklist/blob/master/README.md
CAREFUL, this windows scripts changes user creds!!!!!: https://github.com/xFaraday/EzScript/blob/master/ezScript.ps1
General script for many systems: https://github.com/BaiqingL/CyberPatriotScripts/tree/master/Windows
Pretty reliable script that hasnt killed us yet: https://github.com/ponkio/CyberPatriot
Interesting python based scripts for linux and windows, will install python and git, then run. Read the readme: https://github.com/malvern-cads/centsecure/blob/master/scripts/install.sh



