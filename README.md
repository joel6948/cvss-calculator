# CVSS v3.1 Calculator

## What is CVSS?
CVSS (Common Vulnerability Scoring System) is the industry 
standard for measuring the severity of security vulnerabilities. 
It provides a numerical score from 0.0 to 10.0 that helps 
security teams prioritise which vulnerabilities to fix first.

## What does this tool do?
A web based CVSS v3.1 Base Score calculator that allows 
security analysts to calculate vulnerability severity scores 
by selecting metrics through an interactive interface. 
Generates the official CVSS vector string and displays 
a color coded severity badge.

## 🔗 Live Demo
**[Try it here → joel6948.github.io/cvss-calculator](https://joel6948.github.io/cvss-calculator/)**

## Features
- Interactive metric selection — no typing required
- Live score calculation as you select metrics
- Color coded severity badge
- CVSS vector string with one click copy
- Quick presets for famous CVEs:
  - Log4Shell (CVE-2021-44228) — 10.0 Critical
  - EternalBlue (CVE-2017-0144) — 8.1 High
  - PrintNightmare (CVE-2021-34527) — 8.8 High
  - Heartbleed (CVE-2014-0160) — 7.5 High

## Severity Ratings
| Score | Severity |
|-------|----------|
| 0.0 | None |
| 0.1 - 3.9 | Low |
| 4.0 - 6.9 | Medium |
| 7.0 - 8.9 | High |
| 9.0 - 10.0 | Critical |

## Example CVE Scores
| CVE | Name | Score | Severity |
|-----|------|-------|----------|
| CVE-2021-44228 | Log4Shell | 10.0 | Critical |
| CVE-2017-0144 | EternalBlue | 8.1 | High |
| CVE-2021-34527 | PrintNightmare | 8.8 | High |
| CVE-2014-0160 | Heartbleed | 7.5 | High |

## CVSS Base Metrics Explained
| Metric | Description |
|--------|-------------|
| Attack Vector | How the vulnerability is exploited |
| Attack Complexity | How difficult the attack is |
| Privileges Required | What access level is needed |
| User Interaction | Whether victim action is needed |
| Scope | Whether other components are affected |
| Confidentiality | Impact on data exposure |
| Integrity | Impact on data modification |
| Availability | Impact on system disruption |

## Technologies Used
- HTML5
- CSS3
- JavaScript
- Hosted on GitHub Pages
