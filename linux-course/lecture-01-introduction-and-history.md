# Lecture 01 — Introduction and Linux History

**Instructor:** Eng. Alaa Mohammed
**Course:** Red Hat System Administration (RHCSA-aligned, code 124)

---

## Course Overview

Targets data engineers, support engineers, sysadmins, and DevOps engineers.
Linux is the foundation — required before moving on to Docker, Kubernetes, and OpenShift.

The course covers:
- Command line (where 80–90% of real work happens)
- Built-in help (`man`, `--help`) — no internet needed
- Files, users, groups, permissions
- SSH and remote access
- File system management

---

## Open Source — Why It Matters

- Source code is public; anyone can read, modify, redistribute.
- Companies like VMware, Huawei, and most networking vendors build on the Linux kernel.
- Nobody starts from zero — everyone builds on prior work.

---

## Brief History

| Year | Event |
|------|-------|
| 1969 | AT&T Bell Labs starts Multics, then creates Unix in the 1970s (written in C) |
| 1970s | Berkeley takes Unix and creates BSD |
| 1982 | AT&T closes Unix, makes it commercial |
| 1980s | Richard Stallman founds GNU project + GPL license |
| 1991 | Linus Torvalds writes the Linux kernel as a student in Finland |

The name **Linux** = **Linus** + **Unix**.

---

## GPL (General Public License) — Two Core Rules

1. If you use open source code, you must share your modifications back.
2. You must credit the original authors.

---

## Unix vs Linux

| Aspect       | Unix                                  | Linux                          |
|--------------|---------------------------------------|--------------------------------|
| Source       | Closed                                | Open source                    |
| Cost         | Expensive (HW + OS + app + support)   | Free (pay only for support)    |
| Hardware     | Locked (HP-UX → HP, AIX → IBM)        | Runs on any hardware           |
| Distributions| HP-UX, AIX, Solaris                   | Hundreds (RHEL, Ubuntu, SUSE)  |
| Used in      | Banks, oil & gas, legacy systems      | Cloud, servers, everywhere     |

---

## Linux Distribution Families

**Red Hat family**
Fedora (lab / testing) → RHEL (commercial) → CentOS (community, discontinued) → **Rocky Linux** (CentOS replacement)

**SUSE family**
openSUSE → SUSE Enterprise

**Debian family**
Debian → Ubuntu

**Security-focused**
Kali Linux — ships with 200–300 pre-installed security tools

> Tip: `distrowatch.com` lists 400+ distributions with rankings and screenshots.

---

## Red Hat Release Cycle

- **Fedora** = open project, new release every 6 months (testing ground)
- Features that stabilize move into **RHEL**
- Best practice: stay one version behind the latest to avoid bugs

---

## Linux Architecture
