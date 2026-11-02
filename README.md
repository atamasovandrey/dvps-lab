# dvps-lab

A hands-on lab for learning DevOps practices.

## Hosts

| Host   | IP             | Role                                          |
|--------|----------------|-----------------------------------------------|
| mgmt   | 192.168.56.103 | Management: all administration runs from here |
| app-01 | 192.168.56.101 | Application server                            |
| db-01  | 192.168.56.102 | Database server                               |

## Access

- SSH key authentication only. Password and root login are disabled.
- Only the keys of mgmt and my Windows workstation are authorized on app-01 and db-01.
- The servers have no SSH access to each other, so compromising one does not give SSH access to the other (least privilege).
