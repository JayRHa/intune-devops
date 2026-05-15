<!-- unified-readme:start -->
<div align="center">

# Intune DevOps

**DevOps pipeline integration for Microsoft Intune configuration management and deployment automation.**

Build. Release. Govern.

[![GitHub stars](https://img.shields.io/github/stars/JayRHa/IntuneDevOps?style=for-the-badge&logo=github&color=f4c542)](https://github.com/JayRHa/IntuneDevOps/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/JayRHa/IntuneDevOps?style=for-the-badge&logo=github&color=4078c0)](https://github.com/JayRHa/IntuneDevOps/network/members)
[![GitHub issues](https://img.shields.io/github/issues/JayRHa/IntuneDevOps?style=for-the-badge&logo=github&color=d73a4a)](https://github.com/JayRHa/IntuneDevOps/issues)
[![Contributors](https://img.shields.io/github/contributors/JayRHa/IntuneDevOps?style=for-the-badge&logo=github&color=28a745)](https://github.com/JayRHa/IntuneDevOps/graphs/contributors)

---

`Endpoint Management` | `PowerShell` | `Public` | `Maintained`

</div>

## What is this?

Intune DevOps supports Microsoft Intune and endpoint management workflows such as automation, troubleshooting, remediation, deployment, or reporting.

## Project Context

- Use it when Intune work should be scripted, packaged, synchronized, or made easier to repeat.
- Most workflows start from repository assets, then move through Microsoft Graph, Intune, or device-side execution.
- This repository is maintained as a practical project and reference asset.

## How It Works

The repository stores scripts or tooling, administrators configure or run them, Intune and Microsoft Graph apply the work, and endpoint results feed back into reports or follow-up actions.

```mermaid
flowchart LR
    Repo[Repository assets] --> Admin[Administrator workflow]
    Admin --> Graph[Microsoft Graph or Intune]
    Graph --> Device[Managed endpoint]
    Device --> Result[Detection, remediation, or report]
    Result --> Review[Review and iterate]
    Review --> Repo
```

## Quick Start

1. Review the project context and workflow below.
2. Clone the repository:

   ```bash
   git clone https://github.com/JayRHa/IntuneDevOps.git
   ```

3. Continue with the project-specific documentation in the next section.

---
<!-- unified-readme:end -->

<!-- project-documentation:start -->
## Project Documentation

The sections below contain the repository-specific setup, usage, and reference material for this project.

# Intune DevOps
[Check out my blog](https://jannikreinhard.com)

<p align="left">
  <a href="https://twitter.com/jannik_reinhard">
    <img src="https://img.shields.io/twitter/follow/jannik_reinhard?style=social" target="_blank" />
  </a>
    <a href="https://github.com/JayRHa">
    <img src="https://img.shields.io/github/followers/JayRHa?style=social" target="_blank" />
  </a>
</p>

## Change Log
---
- Version 0.1:
   - Support for Config Profiles, Compliance Policies, Filter, Remediation and Powershell scripts 

## Description

![Tool View](https://github.com/JayRHa/IntuneDevOps/blob/main/.images/devops.png)

## How does it work
You can find all informations how to setup and how does it work in my blog post:
https://jannikreinhard.com/
