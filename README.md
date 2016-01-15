# Create 2 Virtual Machines in an Availability Set and Configure NAT Rules through the Load balancer

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmschray%2FAzureVMCreate%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fmschray%2FAzureVMCreate%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>


This template allows you to create 2 Ubunto Virtual Machines in an Availability Set and configure NAT rules through the load balancer. This template also deploys a Storage Account, Virtual Network, Public IP address and Network Interfaces.

In this template, we use the resource loops capability to create the network interfaces and virtual machines.
