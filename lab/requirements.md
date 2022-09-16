# OPI Lab Requirements

## Access

- Lab staff can access to all machines.
- OPI members should access only to their own machines.
- Remote access to a machine requires private VPN specific to the machine.
- OPI members cannot access to a machine from another one.
- SSH connection is available through VPN.
- Emergency console can be enabled for remote access in case of issue.

## Backup

- All critical servers must be backed up.
- Restoration of critical servers must be done within a couple of hours.
- Hosting provider must be trained to do backup/restore.

## Capacity

- Wait queue for automatic tests should be less than 1 hour.
- Sufficient excess capacity so that manual workloads does not affect automatic tests too much.
- System must support firmware updates.

## Process

- End users given 2 weeks notice for major lab works
- End users given 1 week notice for regular lab maintenance works
- End users notified as soon as it is known immediate emergency lab work need to be done
- Hosting provider must be notified 2 days in advance of a change on a machine
  in order to avoid false negative results due to an upgrade in process.
- Any environment change (firmware, OS update or new software)
  and test changes (new or updated use case)
  must be validated first before being used in automatic tests.
- Lab inventory management system in place
- Lab tech updates inventory as needed
- Lab manager assigned
- Process in place to forecast equipment needs
- Questionnaire in place to be handed out to lab users to help with equipment forecast
- Lab requirements reviewed by OPI TSC
- Sufficient budget in place to fund initial capital costs
- Sufficient budget in place to fund ongoing operations
- Ticketing system in place to request lab services

## Documentation

- Wiki showing servers, assigned owners, emergency console and SSH access info
- Documentation in place for lab resources and interconnection
  - example: <https://opendcim.org/screenshots.html>

## SLA

- SSH access at 99% availability.
- Automatic tests running at 95% availability (includes maintenance downtime).
