# PRTG-IOSXE-DOM
Optical DOM Monitoring using Ansible and PRTG

#### DOM Rx  

IOS-XE only exposes DOM statistics via CLI. This playbook leverages ntc-ansible and its TextFSM integration to parse the CLI output of 'show interfaces transceiver' and POST the output to a PRTG HTTP Push Data Advanced sensor.
