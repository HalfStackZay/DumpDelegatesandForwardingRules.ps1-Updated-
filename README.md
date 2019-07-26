# DumpDelegatesandForwardingRules.ps1-Updated-
O365 DumpDelegatesandForwardingRules.PS1 updated for MFA enabled Exchange Online Remote PowerShell Module


Follow these instructions to download the Exchange Online Powershell Module for non-legacy connections:
#
#
The Exchange Online Remote PowerShell Module needs to be installed on your computer: 
#
In Internet Explorer or Edge, open the Exchange admin center (EAC) for your Exchange Online organization. For instructions, see Exchange Admin Center in Exchange Online. 
#
Note: A browser that uses ClickOnce to download (like Internet Explorer or Edge) is needed to complete the next step. 
#
In the EAC, go to Hybrid > Setup and click the appropriate Configure button to download the Exchange Online Remote PowerShell Module for multi-factor authentication.
#
In the Application Install window that opens, click Install. 
#
#
Windows Remote Management (WinRM) on your computer needs to allow basic authentication (it's enabled by default). To verify that basic authentication is enabled, run this command in a Command Prompt: 
#
#
Open the run line by hitting the windows key + r 
#
Type services.msc and hit enter 
#
Scroll down the list to the Windows Remote Management service 
#
Highlight and start the service 
#
I would recommend double clicking and changing the service to automatically start with delay 
