# demo-reporting-service

> **BOSS Demo Microservice — Tier 3 (Supporting)**
>
> Simulates the Reporting / Logging Service in the BOSS application ecosystem

---

## Overview

This repository is part of the **BOSS Versioning System** demo. It represents a **Tier 3 Supporting** microservice — changes here carry the lowest weight in determining the BOSS application version

## Branch Structure

| Branch | Environment | Version Impact |
|--------|-------------|----------------|
| `develop` | DEV | Right-most digit bumps (e.g. `2.0.0 → 2.0.1`) |
| `release/qa` | QA | No version bump — testing only |
| `uat` | UAT (Pre-Production) | **Middle digit bumps** (e.g. `2.0.3 → 2.1.0`) — triggers BOSS aggregator |

## PR Labels

| Label | Meaning | BOSS Impact (Tier 3) |
|-------|---------|----------------------|
| `breaking-change` | Any label | **PATCH bump** |
| `feature` | Any label | **PATCH bump** |
| `enhancement` | Any label | **PATCH bump** |
| `bugfix` | Any label | **PATCH bump** |

## BOSS Tier Assignment

- **Tier**: 3 — Supporting
- **Simulates**: Reporting / Logging Service
- **Priority**: Low — non-critical, changes always result in PATCH bump.

