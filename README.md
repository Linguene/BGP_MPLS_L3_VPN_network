# BGP_MPLS_L3_VPN_network

The aim of this project is to build a BGP/MPLS L3 VPN by configuring network devices using FRRouting software.

## Purpose and goals in details

A network with the following characteristics has been created as part of the project:
* OSPF has been configured withing the AS400
* LDP tunnels have been estabilished between PE routers
* BGP-free core has been set in AS400
* Finally, the required eBGP connectivity has been estabilished between customer Blue CE routers and the respective PE routers in AS400

## Initial configurations

This directory contains the initial network device configurations and setup associated with the FRR.

## Final configurations

This folder contains the terminal text from the console of each network device. At the end of each file is the configuration for setting up the BGP/MPLS L3 VPN on each device.
