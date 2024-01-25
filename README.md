# SCCM (MECM) Attack Techniques
This repository serves as a central location for all known attack and defense techniques related to SCCM.

## SCCM Attacks Matrix
|  Reconaissance                                                               | Resource Development                                                         | Initial Access                                                               | Execution                                                                           | Persistence                                                                        | Privilege Escalation                                                         | Defense Evasion                                                            | Credential Access                                                                             | Discovery                                                                     | Lateral Movement                                                                      | Collection	                                                            | Command and Control                                                       | Exfiltration                                                              | Impact                                                                              |
|:---:	                                                                       |:---:                                                                         |:---:                                                                         |:---:	                                                                               |:---:                                                                               |:---:	                                                                       |:---:                                                                       |:---:	                                                                                        |:---:	                                                                        |:---:	                                                                                |:---:	                                                                    |:---:	                                                                    |:---:	                                                                    |:---:	                                                                              |
|                                                                              |                                                                              | [CRED01](./attack-techniques/CRED01/credential01-description.md)             |   	                                                                               |   	                                                                                | [CRED01](./attack-techniques/CRED01/credential01-description.md)             |   	                                                                        | [CRED01](./attack-techniques/CRED01/credential01-description.md)                              |   	                                                                        | [TAKEOVER01](./attack-techniques/TAKEOVER01/takeover01-description.md)                |   	                                                                    |   	                                                                    |   	                                                                    |   	                                                                              |
|   	                                                                       |   	                                                                          |   	                                                                         |   	                                                                               |   	                                                                                | [CRED02](./attack-techniques/CRED02/credential02-description.md)             |   	                                                                        | [CRED02](./attack-techniques/CRED02/credential02-description.md)                              |   	                                                                        | [TAKEOVER02](./attack-techniques/TAKEOVER02/takeover02-description.md)                |   	                                                                    |   	                                                                    |   	                                                                    |   	                                                                              |
|   	                                                                       |   	                                                                          |   	                                                                         |   	                                                                               |   	                                                                                | [CRED03](./attack-techniques/CRED03/credential03-description.md)             |   	                                                                        | [CRED03](./attack-techniques/CRED03/credential03-description.md)                              |   	                                                                        | [TAKEOVER03](./attack-techniques/TAKEOVER03/takeover03-description.md)                |   	                                                                    |   	                                                                    |   	                                                                    |   	                                                                              |
|   	                                                                       |   	                                                                          |   	                                                                         |   	                                                                               |   	                                                                                | [CRED04](./attack-techniques/CRED04/credential04-description.md)             |   	                                                                        | [CRED04](./attack-techniques/CRED04/credential04-description.md)                              |   	                                                                        |   	                                                                                |   	                                                                    |   	                                                                    |   	                                                                    |   	                                                                              |
|   	                                                                       |   	                                                                          |   	                                                                         |   	                                                                               |   	                                                                                | [TAKEOVER01](./attack-techniques/TAKEOVER01/takeover01-description.md)       |   	                                                                        |   	                                                                                        |   	                                                                        |   	                                                                                |   	                                                                    |   	                                                                    |   	                                                                    |   	                                                                              |
|   	                                                                       |   	                                                                          |   	                                                                         |   	                                                                               |   	                                                                                | [TAKEOVER02](./attack-techniques/TAKEOVER02/takeover02-description.md)       |   	                                                                        |   	                                                                                        |   	                                                                        |   	                                                                                |   	                                                                    |   	                                                                    |   	                                                                    |   	                                                                              |
|   	                                                                       |   	                                                                          |   	                                                                         |   	                                                                               |   	                                                                                | [TAKEOVER03](./attack-techniques/TAKEOVER03/takeover03-description.md)       |   	                                                                        |   	                                                                                        |   	                                                                        |   	                                                                                |   	                                                                    |   	                                                                    |   	                                                                    |   	                                                                              |
|   	                                                                       |   	                                                                          |   	                                                                         |   	                                                                               |   	                                                                                |   	                                                                       |   	                                                                        |   	                                                                                        |   	                                                                        |   	                                                                                |   	                                                                    |   	                                                                    |   	                                                                    |   	                                                                              |
|   	                                                                       |   	                                                                          |   	                                                                         |   	                                                                               |   	                                                                                |   	                                                                       |   	                                                                        |   	                                                                                        |   	                                                                        |   	                                                                                |   	                                                                    |   	                                                                    |   	                                                                    |   	                                                                              |
|   	                                                                       |   	                                                                          |   	                                                                         |   	                                                                               |   	                                                                                |   	                                                                       |   	                                                                        |   	                                                                                        |   	                                                                        |   	                                                                                |   	                                                                    |   	                                                                    |   	                                                                    |   	                                                                              |
|   	                                                                       |   	                                                                          |   	                                                                         |   	                                                                               |   	                                                                                |   	                                                                       |   	                                                                        |   	                                                                                        |   	                                                                        |   	                                                                                |   	                                                                    |   	                                                                    |   	                                                                    |   	                                                                              |
|   	                                                                       |   	                                                                          |   	                                                                         |   	                                                                               |   	                                                                                |   	                                                                       |   	                                                                        |   	                                                                                        |   	                                                                        |   	                                                                                |   	                                                                    |   	                                                                    |   	                                                                    |   	                                                                              |
|   	                                                                       |   	                                                                          |   	                                                                         |   	                                                                               |   	                                                                                |   	                                                                       |   	                                                                        |   	                                                                                        |   	                                                                        |   	                                                                                |   	                                                                    |   	                                                                    |   	                                                                    |   	                                                                              |                                                                     
|   	                                                                       |   	                                                                          |   	                                                                         |   	                                                                               |   	                                                                                |   	                                                                       |   	                                                                        |   	                                                                                        |   	                                                                        |   	                                                                                |   	                                                                    |   	                                                                    |   	                                                                    |   	                                                                              |                                                                         