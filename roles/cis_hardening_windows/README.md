CIS Hardening Windows
Applies security patches to harden system base on CIS benchmarks


Dependencies
- Azure CLI is required. It's used to push reports to a storage blob.

Role Variables
- rules_list: A list of rule numbers. Usually generated from the exceptions_list.yml 


Example Playbook
- hosts: servers
  role: cis_hardening_windows
  rules_list:  "{{ exceptions_list | map(attribute='rule') | list }}"
