# IBM MQ Server
The following directory includes the Ansibile resources required for the installation and configuration of IBM MQ Server. Requirements include:

- IBM ACE Package
- IBM MQ Package

## Playbooks
| Playbook Name | Description |
| ---------- | ---------- |
| ibmmq.yml | Full installation and configuration of MQ Server |


## Roles
| Role Name | Description |
| ---------- | ---------- |
| prepare_install | Will perform any pre-steps required like downloading/extracting binaries, setting up environment variables, Setup OS, etc. |
| mq_install | Install the MQ Server, ACE Server, Fix Packages, Plug-ins |


## Variables
| Variable Name | Description |
| ---------- | ---------- |



##  Automation Execution
Reference the following (IBM MQ Server Runbook)[https://amedeloitte.sharepoint.com/:w:/r/sites/TexasTIERSMigration/Shared%20Documents/General/Architecture%20Diagram%20%26%20Runbook/App%20Runbook/COTS%20Runbooks/Sprint%201/TIERS%20Cloud%20Migration%20IBM%20HTTP%20Runbook%20v1%2020231201.docx?d=wcd305073d3ff4c7fb63ca11f4fc8516e&csf=1&web=1&e=zeI6sg] to execute the following product in Ansible Tower.
