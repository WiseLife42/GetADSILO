# Introduction
GetADSILO is a Python script that queries Active Directory to list users and computers associated with authentication silos.

The script performs the following actions:
* Displays users with SILO applied.
* Displays computers with SILO applied.

# Installation
## Prerequisites
* Python3
* ldap3
* rich
    
```
pip install ldap3 rich
wget https://raw.githubusercontent.com/WiseLife42/GetADPSO/main/GetADSILO.py
```

# Usage
```
# python3 GetADSILO.py -h

usage: GetADSILO.py [-h] -u USERNAME -p PASSWORD -d DOMAIN --dc-host DC_HOST [--kerberos] [--ccache CCACHE] [-v]

Script to query authentication silos in Active Directory and list associated members.

options:
  -h, --help            show this help message and exit
  -u USERNAME, --username USERNAME
                        Active Directory username
  -p PASSWORD, --password PASSWORD
                        Active Directory password
  -d DOMAIN, --domain DOMAIN
                        Active Directory domain
  --dc-host DC_HOST     Domain controller hostname or IP address
  --kerberos            Use Kerberos authentication
  --ccache CCACHE       Path to Kerberos ccache file
  -v, --debug           Enable debug logging for more details

```
## Running



