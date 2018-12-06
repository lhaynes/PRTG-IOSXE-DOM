# PRTG-IOSXE-DOM
Optical DOM Monitoring using Ansible and PRTG

#### DOM Rx  
![screenshot](https://github.com/lhaynes/PRTG-IOSXE-DOM/raw/master/screenshot.png)

IOS-XE only exposes DOM statistics via CLI. This playbook leverages ntc-ansible and its TextFSM integration to parse the CLI output of 'show interfaces transceiver' and POST the output to a PRTG HTTP Push Data Advanced sensor.

[PRTG HTTP Push Data Advanced Sensor Documentation](https://www.paessler.com/manuals/prtg/http_push_data_advanced_sensor)
