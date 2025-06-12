# Test Strategy Report

The Test Strategy Report is a high-level document that plans how a project's testing will be conducted.

## **Introduction**

This test strategy defines the approach for verifying and validating the e-commerce website. It ensures that all functional and non-functional aspects are tested effectively, including system integration, security, and performance under real-world conditions. This document aligns testing activities with the Agile software development lifecycle to ensure continuous quality assurance throughout the project.

## Project Overview

The e-commerce platform allows users to:

- Browse products
- Add items to the cart
- Complete purchases via various payment gateways
- Track orders post-purchase

The system integrates with external payment gateways and inventory management systems and must remain performant under high user load, especially during sale events.

## SDLC Alignment

Testing is embedded within the Agile development lifecycle, executed in two-week sprints. Test planning, execution, and regression cycles are integrated with sprint activities to ensure continuous validation. Regression and non-functional testing (e.g., performance and security) occur in parallel with sprint cycles and during hardening phases before production releases.

## Objectives & Scope

- Verify functional correctness of all key user flows
- Ensure system stability under peak traffic
- Validate the security of sensitive data, especially during payment
- Confirm cross-platform compatibility
- Validate successful integration with external services

## Approach

- Functional testing will be performed using both manual and automated methods to validate user workflows.
- Exploratory and structured testing will verify different scenarios, including edge cases.
- Non-functional testing, such as performance, security, and compatibility, will be handled using specialized tools and executed in dedicated environments.
- Integration testing with third-party systems will include contract, workflow, and failure path validation.

