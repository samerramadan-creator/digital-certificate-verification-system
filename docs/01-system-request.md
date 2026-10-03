# System Request — Digital Certificate Verification System

| | |
|---|---|
| **Project** | Digital Certificate Verification System |
| **Course** | System Analysis |
| **Institution** | Faculty of Computers and Information, Menoufia University |
| **Prepared by** | Samer |
| **Document** | System Request (Phase 2 of the SRS roadmap) |
| **Status** | Draft v1.0 |

---

## 1. Project Sponsor

**Faculty of Computers and Information, Menoufia University** (Faculty Administration and Student Affairs).

The sponsor is the body that issues graduation certificates. It provides the funding, the official graduate records, and the institutional support the system needs.

---

## 2. Business Need

Verifying a graduate's certificate is currently a manual process based on paper documents, official letters, and phone calls. This causes several problems:

- **Slow turnaround.** A single verification request can take days.
- **Vulnerability to forgery.** Paper certificates are easy to copy or alter, and there is no quick way to prove authenticity.
- **Heavy staff workload.** Student Affairs staff spend time answering repetitive verification requests.
- **No self-service option.** Employers and other universities have no fast, reliable way to check a certificate themselves.

---

## 3. Business Requirements

The system must provide the following capabilities:

| ID | Requirement |
|----|-------------|
| BR-1 | Issue a digital certificate record for each graduate, with a unique verification code and a QR code. |
| BR-2 | Provide a public verification page where any party (employer, university, agency) can verify a certificate by entering its code or scanning its QR code. |
| BR-3 | Provide an admin dashboard for Student Affairs staff to add, update, and revoke certificates. |
| BR-4 | Keep an audit log of all verification attempts and administrative actions. |
| BR-5 | Protect graduate data and prevent unauthorized modification of certificate records. |

---

## 4. Business Value

**Tangible benefits**

- Verification time drops from days to seconds.
- Less staff time spent on manual verification requests.
- Fewer paper-based processes and printing costs.

**Intangible benefits**

- Reduced risk of certificate forgery.
- Stronger reputation for the Faculty and the University through digital transformation.
- Greater trust from employers and partner institutions.

---

## 5. Special Issues and Constraints

| Area | Consideration |
|------|---------------|
| **Privacy** | Graduate personal data must be protected, and the public page should expose only the minimum information needed to confirm validity. |
| **Integration** | The system must connect with, or import data from, the existing student records database. |
| **Legacy data** | Certificates issued before the system exists will need to be digitized and entered. |
| **Change management** | Staff will need training and support to move from manual to digital verification. |
| **Security** | Certificate records must be tamper-resistant, with strict access control for administrators. |

---

*Next phase: [Feasibility Study](02-feasibility-study.md)*
