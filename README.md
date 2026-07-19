# Python Network Automation

This repository contains simple Python tools for network troubleshooting and automation.

The projects demonstrate practical tasks such as checking device availability, calculating subnets, connecting to network devices through SSH, backing up configurations, and analyzing firewall logs.

## Projects

### Ping Multiple Hosts

Checks whether multiple network devices are reachable.

```bash
python ping_multiple_hosts.py
```

### Subnet Calculator

Displays subnet information such as the network address, broadcast address, subnet mask, and usable hosts.

```bash
python subnet_calculator.py
```

### SSH Connection

Connects to a network device through SSH using Netmiko.

```bash
python ssh_connect.py
```

### Configuration Backup

Connects to multiple devices and saves their running configurations locally.

```bash
python backup_configs.py
```

### Firewall Log Parser

Reads a firewall log file and summarizes allowed and denied traffic.

```bash
python firewall_log_parser.py
```

## Requirements

- Python 3
- Netmiko

Install the required package:

```bash
pip install -r requirements.txt
```

## Security

Do not store real passwords, customer IP addresses, private keys, or confidential configurations in this repository.

Use this project only with devices you own or are authorized to manage.
