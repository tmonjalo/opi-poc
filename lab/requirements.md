# OPI Lab Requirements

## Access

- Can SSH to server from various OPI member VPNs
- Raritan in place for all servers
  - To enable remote access to servers in case main network is down.
- Secondary remote management system enabled to supplement Raritan.
  System must support firmware updates.
  - For example, Dell's iDRAC (Dell Remote Access Controller)
- Remote access to power cyclers

## Backup

- All critical servers backed up
- Restore of critical servers must be done within a couple of hours
- Team in place trained to do backup/restore

## Capacity

- Sufficient capacity so wait queue is zero to accommodate all CI workloads
  - processing resources need to be proportional to rate of GitHub PR arrivals x average time to do builds+tests
- Sufficient excess capacity so as new users request lab capacity they can be reasonably accomodated without waiting

## Process

- End users given 2 weeks notice for major lab works
- End users given 1 week notice for regular lab maintenance works
- End users notified as soon as it is known immediate emergency lab work need to be done
- Firedrills scheduled to refresh operational knowledge to deal with emergency events
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

- Wiki showing servers, assigned owners, Raritan info, SSH access info
- Documentation in place for browsing, requesting, and releasing lab resources
  - e.g. how to request for new physical servers with power cycler
- Documentation in place for lab resources and interconnection
  - example: <https://opendcim.org/screenshots.html>

## Compliance

- Complies with all laws in jurisdiction where data center is hosted
  - e.g. need to seismic the racks if located in California
- Complies with all data privacy laws
- Complies with HIPAA (health information)
- Complies with National Institute of Technology (NIST) and Uptime Institute's certification tiers
- Complies with quality standareds, like ISO
- Complies with security standards, like SOC
- Complies with environmental management standards
- Complies with energy efficient data center designs
- Complies with operational security policies
  - e.g. card key access

## SLA

- SSH access at 99.99% availability
- Lab tech accessible 24/7

## Technical Details

- Storage area/bins in place to cache supply of lab equipement, such as cables, optical transceivers, hard drives, RAM, usb sticks, etc.
- HVAC in place with sufficient capacity to dissipate heat
  - 3 ton HVAC not sufficient for 4 racks.  Need at least 5 tuns for 4 racks
- Electrical power in place with sufficient capacity to service all lab equipment
- Sufficient power outlets so all equipment needing outlet is accounting for, inclusive of failover power supplies
- Poster identifying meaning of cable color codes
- Redundant HVAC in place in case primary HVAC dies
- From servers, can access CI controller (e.g. Jenkins)
- From servers, can access K8s cluster
- From servers, can access Artifactory
- From servers, can access JIRA
- From servers, can access open source repos
- From servers, can access various databases
- Authentication done through centralized system, such as Kerberos, as much as possible
- Authorization done through centralized system such as LDAP, as much as possible
