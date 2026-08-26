# VM network configuration

- Both Ubuntu versions tested for this setup include two unique network configuration file paths:
  - 22.04: /etc/netplan/50-cloud-init.yaml
  - 16: /etc/network/interfaces
 
## Notes
- Wazuh requires both agents and manager to be in the **same subnet**;
