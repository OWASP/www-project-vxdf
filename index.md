---

layout: col-sidebar
title: OWASP VXDF
tags: example-tag
level: 2
type: code
pitch: A very brief, one-line description of your project

---

VXDF (Validated eXploitable Data Flow) is a next-generation open-source framework and engine designed to validate whether reported security vulnerabilities are actually exploitable. It normalizes findings from tools like SARIF, ZAP, and others, and uses dynamic verification to replay and validate attacks. VXDF outputs standardized, schema-compliant JSON files containing exploit evidence, enabling security engineers to focus on real risks rather than theoretical alerts. It bridges static analysis, dynamic analysis, and SCA tooling into a unified validation layer.

### Road Map
v0.1 (Current): Working prototype with SARIF support, XSS/path traversal validators, and a React dashboard.
v0.2: Expanded validator coverage (SSRF, SQLi), VXDF schema refinement, CLI tooling, and API documentation.
v0.3: VXDF specification formalization and submission to OWASP; community onboarding and contribution guidelines.
v1.0: Official VXDF spec release, plugin SDK for validators, integrations with third-party tools (Snyk, Burp, etc.), and optional GitHub Actions integration.
