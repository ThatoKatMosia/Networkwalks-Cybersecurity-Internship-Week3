# Networkwalks Cybersecurity Internship - Week 3

Practical exercises on password security, authentication, and hash analysis.
This repository documents the learning outcomes and workflow from the Week 3
lab; it does not contain recovered passwords, hashes, or challenge flags.

## Lab overview

The exercises used a supplied training PDF to explore how password-protected
documents store verifiable password hashes and how weak passwords can be
identified during an authorized dictionary-attack demonstration.

## Learning objectives

- Distinguish a password hash from an encrypted document.
- Understand, at a high level, how dictionary-based password testing works.
- Recognize why short, common, or reused passwords are vulnerable.
- Handle recovered values and lab evidence responsibly.

## Repository guide

| Path | Description |
| --- | --- |
| [`docs/lab-report.md`](docs/lab-report.md) | Scope, workflow, observations, and takeaways |
| [`evidence/README.md`](evidence/README.md) | Evidence handling and redaction guidance |

## Tools used

- John the Ripper Jumbo with the Johnny graphical interface
- A PDF hash-extraction utility supplied or referenced by the lab
- The provided training PDF and dictionary data

Tool versions and commands are intentionally not recorded where they might
expose local machine details or sensitive lab material.

## Authorization and safety

All testing described here was limited to the training material provided for
the exercise. Do not use these techniques on documents, accounts, hashes, or
systems without explicit authorization. Do not publish recovered passwords,
hashes, flags, or unredacted screenshots.
