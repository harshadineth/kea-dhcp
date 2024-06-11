****Kea DHCP Server Configuration****


****Overview****

This repository contains the configuration for a Kea DHCPv4 server with advanced features, including High Availability (HA) in a hot-standby mode.



****Key Features****

- Interfaces Configuration: Listens on all available network interfaces using raw sockets.

- Lease Database: Uses a memory-backed file for lease storage with a regular cleanup interval.

- High Availability: Configured for hot-standby mode with heartbeat and failure detection parameters.

- Subnet Configuration: Serves the subnet 10.0.2.0/24 with a specific pool of IP addresses.

- Logging: Outputs logs to stdout with INFO severity.
