---
permalink: /projects/
title: "Projects"
author_profile: true
---

## CloudGuard - AWS IAM Risk Analyzer

A lightweight, zero-dependency Python tool that scans AWS IAM policy documents for misconfigurations, privilege-escalation paths, and overly permissive access patterns. Designed for offline use in code review, CI pipelines, and pre-deployment checks.

**Detects:** Full admin access, wildcard permissions, known privilege-escalation chains (PassRole, AssumeRole, Lambda abuse), NotAction/NotResource anti-patterns, missing condition constraints.

**Tech:** Python 3.7+, zero external dependencies, CI-ready exit codes.

[View on GitHub](https://github.com/blackshieldcore/cloudguard)
