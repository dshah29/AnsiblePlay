# CIS Hardening - Windows

## Compatibility
- Windows Server 2019
- Windows Server 2016
- Windows Server 2012
- Windows 10 Enterprise

# How to run
```
ansible-playbook playbook
```
OR if you want to upload reports to blob storage
```
ansible-playbook playbook --tags='all,get_report'
```

## Optional Requirements
- Azure CLI installed if using "get_report" tag

## Current Post Hardening Scores

- Windows Server 2019:
  - ```
    Score Earned: 279.0,
    Maximum Available: 292.0,
    Total: 95.55%
    ```
- Windows Server 2016:
  - ```
    Score Earned: 276.0",
    Maximum Available: 289.0",
    Total: 95.5%
    ```
- Windows Server 2012:
  - ```
    Score Earned: 260.0",
    Maximum Available: 272.0",
    Total: 95.59%
    `
- Windows 10 Enterprise:
  - ```
    Score Earned: 314.0,
    Maximum Available: 332.0,
    Total: 94.59%
    ```
