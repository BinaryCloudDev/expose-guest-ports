# Expose Guest Ports
PowerShell script to expose VirtualBox guest machine TCP and UDP ports to the host

## Usage

`/Expose-Guest-Ports.ps1 -startPort <start port> -endPort <end port> -vmName <target guest machine name>`

E.g. `/Expose-Guest-Ports.ps1 -startPort 3000 -endPort 4000 -vmName Ubuntu`

will inclusively expose every port between 3000 and 4000 from a guest machine named Ubuntu under localhost on the host.
