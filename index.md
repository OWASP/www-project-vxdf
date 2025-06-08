---
layout: col-sidebar
title: OWASP VXDF (Validated Exploitable Data Flow) Format
tags: vxdf, validated exploitable flow, vulnerability management, security automation, evidence-based security, sarif, spdx, devsecops, responsible disclosure
level: 2
type: code
pitch: OWASP VXDF is an evidence-backed format for reporting *validated exploitable* code vulnerabilities, designed to cut through alert fatigue, provide precise actionable insights, and standardize proof of exploitability across the security ecosystem.
---

# OWASP VXDF: The Standard for Verifiable Exploit Evidence

## The Problem

Security teams are overwhelmed by vulnerability alerts from scanning tools (SAST, DAST, SCA). Most alerts are false positives or theoretical vulnerabilities with no practical exploit path, leading to:

- **Alert Fatigue:** Wasted time on non-critical issues
- **Delayed Remediation:** Real threats get lost in the noise
- **Developer Frustration:** Constant interruptions for non-exploitable issues
- **Inconsistent Reporting:** Incompatible formats across tools and researchers

## The Solution: VXDF

**OWASP VXDF (Validated Exploitable Data Flow)** is a standardized, machine-readable JSON format for describing **confirmed exploitable** code vulnerabilities with mandatory validation evidence.

### Key Features

- **Evidence-Based:** Focus on validated exploitable findings, not theoretical possibilities
- **Standardized Format:** Common language for describing vulnerability exploitation paths
- **Machine-Readable:** Enables automation in security tools and CI/CD pipelines
- **Actionable Intelligence:** Clear exploitation steps with concrete proof

### What VXDF Contains

- **Vulnerability Identification:** CWE mapping and weakness details
- **Affected Component:** Precise software/library/code segment information
- **Exploitation Path:** Step-by-step attack flow from source to sink
- **Validation Evidence:** Working PoC scripts, HTTP requests/responses, or other verifiable proof
- **Impact Assessment:** Contextualized severity and business impact

## Who Benefits

- **Security Teams:** Prioritize real threats, reduce noise
- **Developers:** Get actionable reports with clear evidence
- **Tool Vendors:** Provide high-fidelity results
- **Researchers:** Submit findings with verifiable proof
- **Organizations:** Improve security posture efficiently

## Project Resources

### Official Links
- **Project Website:** [vxdf.org](https://vxdf.org)
- **GitHub Repository:** [github.com/mihir-shah99/vxdf](https://github.com/mihir-shah99/vxdf)

### Documentation & Tools
- **Schema Specification:** [https://vxdf.org/schema-explorer]()
- **API Documentation:** [Normative Schema](https://github.com/mihir-shah99/vxdf/blob/main/docs/normative-schema.json)
- **Example Files:** [github.com/mihir-shah99/vxdf/blob/main/example1_flow_based.vxdf](https://github.com/mihir-shah99/vxdf/blob/main/test-data/example1_flow_based.vxdf.json)

### Community & Support
- **Discussions:** [GitHub Discussions](https://github.com/mihir-shah99/vxdf/discussions)
- **Issue Tracker:** [GitHub Issues](https://github.com/mihir-shah99/vxdf/issues)

### Integration & Implementation
- **Tool Integration Guide:** [vxdf.org/integration](https://vxdf.org/integration)
- **Developer SDKs:** Work In Progress for Python, JavaScript, Go
- **CI/CD Plugins:** Work In Progress for Jenkins, GitHub Actions, GitLab CI

## Get Involved

**For Contributors:**
- Review the [Contributing Guide](https://github.com/mihir-shah99/vxdf/blob/main/CONTRIBUTING.md)
- Check [Good First Issues](https://github.com/mihir-shah99/vxdf/labels/good%20first%20issue)
- Join our [Slack channel](https://owasp.slack.com/archives/C08T85605RS)

**For Tool Vendors:**
- Implement VXDF in your security products
- Contact us for integration support
- Access our [Vendor Partnership Program](https://vxdf.org/partners)

**For Organizations:**
- Pilot VXDF in your security workflow
- Share feedback and use cases
- Join our [Advisory Board](https://vxdf.org/advisory-board)
