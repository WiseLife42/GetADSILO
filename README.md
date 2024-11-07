# Introduction
GetADSILO is a Python script that queries Active Directory to list users and computers associated with authentication silos.

The script performs the following actions:
* Displays users with SILO applied.
* Displays computers with SILO applied.

# Installation

### With source :
```
git clone https://github.com/WiseLife42/GetADSILO
cd GetADSILO/
pip install .
```

### With pip :
```
pip install GetADSILO
```

# Usage
```
# GetADSILO

usage: GetADSILO [-h] -u USERNAME -p PASSWORD -d DOMAIN --dc-host DC_HOST [--kerberos] [--ccache CCACHE] [-v]

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
## Running with user account
![image](https://github.com/user-attachments/assets/eb1306cb-f7aa-44c9-a2a3-b9055f1b3d1c)

## Running with user account (verbose)
![image](https://github.com/user-attachments/assets/b7bed261-df73-4fa7-a404-20bfa95e2ccb)




