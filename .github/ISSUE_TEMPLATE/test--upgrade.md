---
name: 'Test: Upgrade'
about: Test suite for upgrades.

---

# Upgrade test

| Version | Revision | Branch |
| --- | --- | --- |
| 3.7.0 | 3701 | 3.7 |

## RPM packages (Linux)

| Target | Item | Expected |
| --- | --- | --- |
| Manager/Agent | Install new version | Pass |
| Manager/Agent | Check_files | Pass |
| Manager/Agent | Check that the databases are purged | Pass |
| Manager/Agent | Check that the service is restarted | Pass |

- [ ] Tested.

## DEB packages (Linux)

| Target | Item | Expected |
| --- | --- | --- |
| Manager/Agent | Install new version | Pass |
| Manager/Agent | Check_files | Pass |
| Manager/Agent | Check that the databases are purged | Pass |
| Manager/Agent | Check that the service is restarted | Pass |

- [ ] Tested.

## MSI packages (Windows)

| Target | Item | Expected |
| --- | --- | --- |
| Manager/Agent | Install new version | Pass |
| Manager/Agent | Check_files | Pass |
| Manager/Agent | Check that the service is restarted | Pass |
| Manager/Agent | Install from new version at the same version | Pass |

- [ ] Tested.

## macOS

| Target | Item | Expected |
| --- | --- | --- |
| Manager/Agent | Install new version | Pass |
| Manager/Agent | Check_files | Pass |
| Manager/Agent | Check that the service is restarted | Pass |

- [ ] Tested.

## Solaris (i386)

| Target | Item | Expected |
| --- | --- | --- |
| Manager/Agent | Install new version | Pass |
| Manager/Agent | Check_files | Pass |
| Manager/Agent | Check that the service is restarted | Pass |

## Solaris (SPARC)

| Target | Item | Expected |
| --- | --- | --- |
| Manager/Agent | Install new version | Pass |
| Manager/Agent | Check_files | Pass |
| Manager/Agent | Check that the service is restarted | Pass |

- [ ] Tested.

## HP-UX

| Target | Item | Expected |
| --- | --- | --- |
| Manager/Agent | Install new version |
| Manager/Agent | Check_files | Pass |
| Manager/Agent | Check that the service is restarted | Pass |

- [ ] Tested.

## AIX

| Target | Item | Expected |
| --- | --- | --- |
| Manager/Agent | Install new version | Pass |
| Manager/Agent | Check_files | Pass |
| Manager/Agent | Check that the service is restarted | Pass |

- [ ] Tested.

## Sources

| Target | Item | Expected |
| --- | --- | --- |
| Manager/Agent | Check the upgrade building the source code | Pass |
| Manager/Agent | Check that the databases are purged | Pass |

- [ ] Tested.

## Remote upgrade (WPK)

| Target | Item | Expected |
| --- | --- | --- |
| Manager | Upgrade an agent remotely (Linux and Windows) and check the "upgrade.log"  (Use UDP and TCP) | Pass |
| Manager | Upgrade an agent with a custom WPK | Pass |
| Manager | Upgrade an agent without CA verification | Pass |
| Manager | Downgrade an agent (option `-F`) | Pass |

- [ ] Tested.
