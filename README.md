# NetSec-automation02

Network Automation In a Datacenter context using mainly Arista vEOS devices.
Using a combination of Ansible playbooks and Jinja templates we can build a datacenter fabric using the spine-leaf topology.
It also includes playbooks for configuring the management plane, verification and cleanup as well.

I wanted to make the configuration as dynamic as possible with as little hard coded variables as possible.
This requires some forethought regarding the network design and configuration.
Consistency and standardization is key to an efficient automation solution.

This is a work in progress but everything included so far has been successfully tested in GNS3.
It uses ansible version 2.9.9 and Jinja 3.0.2
Make sure you at least have Jinja 2.10 installed or else the templates won't work properly.

I have loosely followed chapter 4 of network automation cookbook by Karim Okasha as a guideline.

Every line of code is written by me.
