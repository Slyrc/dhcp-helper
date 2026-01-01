# DHCP-HELPER - "From scratch container"

Goal: 

Get a small minimall container which only holds static dhcp-helper bin.
In the end the container is less then 0.5MB.

We use musl to build satic bin. Afterwards dhcp_helper is only 129.4K!!

This static bin can now be used for our from scratch container.