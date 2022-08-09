# Ansible_infolox And Infoblox NIOS Modules for Ansible Collections 
Using ansible-playbook automate the infoblox for creating, deleting the host records 
Ansible-Infoblox Documentaion 

## About 
Infoblox NIOS Modules for Ansible Collections allows managing your NIOS objects through APIs. It, thus, enables the DNS and IPAM automation of VM workloads that are deployed across multiple platforms. The nios_modules collection provides modules and plugins for managing the networks, IP addresses, and DNS records in NIOS. This collection is hosted on Ansible Galaxy under infoblox.nios_modules.

# Modules Overview
The infoblox.nios_modules collection has the following content:

## Modules
nios_a_record – Configure Infoblox NIOS A records

nios_aaaa_record – Configure Infoblox NIOS AAAA records

nios_cname_record – Configure Infoblox NIOS CNAME records

nios_dns_view – Configure Infoblox NIOS DNS views

nios_dtc_lbdn – Configure Infoblox NIOS DTC LBDN records

nios_dtc_pool – Configure Infoblox NIOS DTC pools

nios_dtc_server – Configure Infoblox NIOS DTC server records

nios_fixed_address – Configure Infoblox NIOS DHCP Fixed Address

nios_host_record – Configure Infoblox NIOS host records

nios_member – Configure Infoblox NIOS members

nios_mx_record – Configure Infoblox NIOS MX records

nios_naptr_record – Configure Infoblox NIOS NAPTR records

nios_network – Configure Infoblox NIOS network object

nios_network_view – Configure Infoblox NIOS network views

nios_nsgroup – Configure Infoblox DNS Nameserver Groups

nios_ptr_record – Configure Infoblox NIOS PTR records

nios_restartservices - Controlled restart of Infoblox NIOS services

nios_srv_record – Configure Infoblox NIOS SRV records

nios_txt_record – Configure Infoblox NIOS txt records

nios_zone – Configure Infoblox NIOS DNS zones

# Plugins
nios_inventory: List all the hosts with records created in NIOS

nios_lookup: Look up queries for NIOS database objects

nios_next_ip: Returns the next available IP address for a network

nios_next_network: Returns the next available network addresses for a given network CIDR

# Installation
## Dependencies
Python version 2.7 or later
Ansible version 2.9.0 or later
NIOS 8.2.4 or later

# Prerequisites
Install the infoblox-client WAPI package. To install, run the following command:

$ pip install infoblox-client

