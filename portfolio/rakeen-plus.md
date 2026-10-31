# Rakeen Plus — Pilgrim Service Workflows

**Status:** Independent exploratory prototype in development. Private repository. **Not an official product or deployment of Mashariq or Rakeen.**

## Motivation

Working with the Rakeen 4 pilgrim services team during Hajj 1447H helped me see the importance of clear request tracking, information access, and coordination between the people supporting pilgrims.

The hospitality center served **1,874 pilgrims from Bangladesh** during the season. This is a **center-wide service figure**, not an individual achievement or a product usage metric.

## What I built and explored

A web-based prototype for parts of the pilgrim-service journey, including registration, requests, staff-facing coordination, and follow-up. The private repository contains a **Next.js/React/TypeScript** application with **Prisma** and scripts for testing several domains. It also has a GitHub Actions workflow relating to mobile-shell experiments.

**Technical distinction:** test scripts and CI configuration exist, but this case study does not claim that the full suite passes, that native apps have shipped, or that the application is production-ready.

## Engineering questions to resolve

- Are role and organization boundaries correctly enforced on every sensitive operation?
- Is personal information handled with appropriate access and retention controls?
- Do UI actions reach the intended business logic and persistence without bypasses?
- What can be demonstrated using synthetic data without exposing pilgrim records?
- What would be required to move from prototype workflows to a dependable service?

## What I want to develop next

More systematic requirements analysis, automated verification, secure API design, and operational observability.

[Portfolio overview](README.md) · [LinkedIn](https://www.linkedin.com/in/rfilfilan/)
