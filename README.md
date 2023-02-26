# firewall_script_cmd

Copy this fille to folder witch file you want to block
## Batch Script: Firewall Rules for *.exe and *.dll Files

This batch script creates firewall rules for all *.exe and *.dll files located in the current directory and its subfolders. It uses the Windows netsh command to add inbound and outbound rules to the Windows Firewall.

## Prerequisites

Windows operating systemA
dministrator privileges

## Usage

Copy the batch script to a directory that contains *.exe and *.dll files.
Open Command Prompt as Administrator.
Navigate to the directory that contains the batch script.
Run the batch script:
In folder

Press any key to continue or CTRL+C to terminate the script.
The script will create an inbound and outbound firewall rule for each *.exe and *.dll file in the current directory and its subfolders. The firewall rules will block inbound and outbound traffic for each file.

## Notes

The script will display the list of *.exe files for which it is creating firewall rules.The script will display a message when it finishes creating the firewall rules.The script will display an error message if it is not run with Administrator privileges.License
This script is released under the MIT License.

