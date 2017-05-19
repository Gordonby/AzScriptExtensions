# AzScriptExtensions

## Linux Scripts
###### RhelHttpd
A simple script for use in the Azure Linux Custom Script Extension.
- It installs the apache http daemon, starts it and configures it to auto start at boot time.
- It also downloads a sample html file as i've found not having one can cause issues with some other Azure services like the Application Gateway Health Probe.
- It then opens the VM host firewall on port 80.
