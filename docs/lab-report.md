# Week 3 Lab Report: Password Hash Analysis

## Objective

Explore password protection on a lab-provided PDF, observe the role of password
hashes, and demonstrate why weak passwords are susceptible to dictionary-based
guessing.

## Scope

- **Target:** The training PDF supplied for this exercise
- **Method:** Inspect the lab artifact and use the provided password-auditing
  tools to test dictionary candidates
- **Authorization:** Course lab material only

No third-party documents, accounts, or services were tested.

## Tools and workflow

The exercise used John the Ripper Jumbo through its Johnny graphical interface,
along with a PDF hash-extraction utility referenced by the lab.

At a high level, the workflow was:

1. Prepare the supplied training document for password-hash analysis using the
   lab's extraction utility.
2. Load the lab artifact into the auditing tool and confirm it was recognized.
3. Run the authorized dictionary-based exercise against that artifact.
4. Verify the lab result with the supplied document and record the learning
   outcome without copying the recovered value into this repository.

This report omits exact hashes, candidate lists, recovered passwords, flags,
local file paths, and machine-specific settings.

## Observations

- Password hashes can be checked against candidate passwords; they are not
  the same thing as encrypting or decrypting a document.
- A common or predictable password can be found quickly when it appears in a
  candidate dictionary.
- Tool output and screenshots may reveal sensitive values even when the
  surrounding notes do not.

## Takeaways

- Use long, unique passwords and a password manager rather than predictable
  words or reused credentials.
- Treat hashes and recovered passwords as sensitive information.
- Share lab evidence only after checking it for passwords, hashes, flags, and
  personal or machine-specific details.

## Evidence

Screenshots are not included because the supplied captures expose challenge
values and/or local environment details. See
[`../evidence/README.md`](../evidence/README.md) for safe evidence-handling
guidance.
