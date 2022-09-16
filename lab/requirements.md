# OPI Lab Requirements

## Access

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
- Documentation in place for browsing, requesting, and releasing lab resources
  - e.g. how to request for new physical servers with power cycler
- Documentation in place for lab resources and interconnection
  - example: <https://opendcim.org/screenshots.html>

## SLA

- SSH access at 99% availability.
- Automatic tests running at 95% availability (includes maintenance downtime).
