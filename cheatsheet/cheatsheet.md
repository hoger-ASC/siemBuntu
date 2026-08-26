# Cheatsheet
## Common commands for quick reference

- Wazuh functions are stored in /var/ossec/bin
  - Manager-side /bin/ functions:
   1. /var/ossec/bin/manage_agents = <span style='text-color: blue'>Intuitive agent access functionality</span>
   2. /var/ossec/bin/agent_control = <span style='text-color: blue'>Critical flag-based tooling; <b>Valuable for Automation</b></span>
 
  - Agent-side /bin/ functions:
   1. /var/ossec/bin/manage_agents = <span style='text-color: blue'>Import/ Clear key</span>
## Important files

- Includes logs and config
  - Agent-side config:
   1. /var/ossec/etc/ossec.conf = <span style='text-color: blue'>Configure agent</span>

  - Logs:
   1. /var/ossec/logs
