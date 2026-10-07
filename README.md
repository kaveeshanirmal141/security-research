# Security Research

> Vulnerability research, CVE discoveries, bug bounty research, proof-of-concepts, and technical security investigations.

This repository contains my publicly disclosed security research, including CVE discoveries, vulnerability analysis, proof-of-concepts, and technical write-ups.

My focus is on understanding how real-world software breaks, identifying security vulnerabilities, and documenting the research clearly.

> [!NOTE]
> This repository contains only **original research that is publicly disclosable**. Duplicate findings, confidential reports, and vulnerabilities still under responsible disclosure are intentionally excluded.

## Research Focus

My current research focuses on:

- WebApp security
- WordPress and third-party plugins
- Authentication and authorization
- Broken Access Control and IDOR
- SQL Injection
- Privilege escalation
- Remote code executions
- Vulnerability discovery and root cause analysis

The scope will evolve as my research expands into new areas.

## CVE Discoveries

| CVE | Product | Vulnerability | Severity | Status |
|---|---|---|---|---|
| [CVE-XXXX-XXXXX](./CVE-XXXX-XXXXX) | Product Name | Vulnerability Type | TBD | Published |

> [!IMPORTANT]
> Every CVE listed here represents research that was independently discovered and publicly disclosed through the appropriate disclosure process.

Individual CVE directories contain the available technical analysis, affected versions, impact, proof-of-concept, disclosure timeline, and references.

## Research

Beyond CVE discoveries, this repository contains independent security research and technical investigations.

Where appropriate, each research entry covers:

1. Discovery
2. Root cause
3. Exploitation
4. Impact
5. Responsible disclosure
6. Public documentation

The goal is not simply to find vulnerabilities, but to understand **why they exist and how they can be prevented**.

## Repository Structure

```text
security-research/
│
├── CVE-XXXX-XXXXX/
│   ├── README.md
│   ├── poc/
│   └── screenshots/
│
├── CVE-XXXX-XXXXX/
│   ├── README.md
│   └── poc/
│
└── research/
    └── ...
```

Each vulnerability is documented independently so the research can be understood without requiring access to the original vulnerability report.

## What You Will Find

Depending on the disclosure status and available information, individual research entries may contain:

- Vulnerability overview
- Affected versions
- Root cause analysis
- Attack scenario
- Security impact
- Proof-of-concept
- Reproduction steps
- Screenshots
- Fixed versions
- Official CVE references

## Responsible Disclosure

Security research should improve software, not harm its users.

My general disclosure process is:

1. Identify and verify the vulnerability
2. Minimize impact during testing (and testing i isolated env's like Docker's)
3. Report the vulnerability to the appropriate vendor or CNA
4. Allow reasonable time for remediation
5. Coordinate public disclosure where applicable
6. Publish only information that is safe and authorized to disclose

> [!WARNING]
> The proof-of-concepts and techniques in this repository are intended for **authorized security research and educational purposes only**. Do not use them against systems without explicit permission. Please BE ETHICAL !!

## Research Philosophy

> Find it. Understand it. Report it. Document it.

Finding a vulnerability is only part of the process.

The real value comes from understanding the underlying security failure, demonstrating its impact, communicating it clearly, and helping prevent similar vulnerabilities from appearing again.

## Recognition

Publicly disclosed research may result in:

- CVE assignments
- Vendor acknowledgements
- Security advisories
- Researcher credits
- Bug bounty acknowledgements

Recognition is secondary to the research itself.

## References

Official CVE records, vendor advisories, security patches, and other primary sources are linked within each individual research entry.

## Disclaimer

> [!CAUTION]
> All research in this repository is provided for educational, defensive, and authorized security research purposes. The author is not responsible for misuse of the information contained within this repository.

---

<p align="center">
  Security research is about breaking things responsibly so they can be built stronger.
</p>
