# Task 3 - Vulnerability Assessment using Nessus Essentials

## Objective

To perform a vulnerability assessment of a local machine using Nessus Essentials and identify potential security weaknesses.

## Tool Used

* Nessus Essentials
* Windows 11

## Target

Local Host

IP Address: 192.168.29.66

## Procedure

1. Installed Nessus Essentials.
2. Configured a Basic Network Scan.
3. Set target to local machine IP.
4. Executed a full vulnerability scan.
5. Reviewed vulnerability findings.
6. Researched mitigation techniques.

## Vulnerability Summary

### Example Finding 1

**Name:** Missing Security Updates

**Severity:** Medium

**Description:**
The system is missing recent security patches.

**Mitigation:**
Install the latest Windows updates.

---

### Example Finding 2

**Name:** SMB Signing Not Required

**Severity:** Medium

**Description:**
SMB communication may be vulnerable to man-in-the-middle attacks.

**Mitigation:**
Enable SMB signing via Group Policy.

---

### Example Finding 3

**Name:** Open Network Ports

**Severity:** Low

**Description:**
Several network services are exposed.

**Mitigation:**
Close unnecessary ports and services.

## Screenshots

Screenshots of the scan configuration, results dashboard, and vulnerability details are included in the screenshots folder.

## Outcome

Successfully conducted a vulnerability assessment using Nessus Essentials, identified potential risks, and researched appropriate mitigation strategies.
