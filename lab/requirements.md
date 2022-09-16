# OPI Lab Requirements

## Access

- SSH connection is available through VPN.
- Emergency console can be enabled for remote access in case of issue.

## Backup

- All critical servers backed up
- Restore of critical servers must be done within a couple of hours
- Team in place trained to do backup/restore

## Capacity

- Sufficient capacity so wait queue is zero to accommodate all CI workloads
  - processing resources need to be proportional to rate of GitHub PR arrivals x average time to do builds+tests
- Sufficient excess capacity so as new users request lab capacity they can be reasonably accomodated without waiting
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

- SSH access at 99.99% availability
- Lab tech accessible 24/7
