# AI-Production-Incident-Response-System
An AI-powered Production Incident Response System that helps engineering teams detect incidents, investigate root causes, analyze failures, and recommend remediation using AI agents. Built using SNS Agent Workbench, Google Sheets, and GitHub API integration.
# AI-Powered Production Incident Response System

## Problem Statement

Engineering teams need production services that can be continuously observed and operated by AI. Existing monitoring tools detect incidents and surface alerts, but engineers still spend significant time investigating failures, correlating evidence, identifying root causes, deciding remediation, and shipping fixes.

The platform should instrument services, understand how they behave in production, detect incidents, investigate root causes, recommend and execute remediation, and drive each incident through to a validated fix.

## Project Objective

To develop an AI-powered system that assists engineers in detecting, investigating, analyzing, and resolving production incidents efficiently.

## Proposed MVP

Build three connected AI agents using SNS Agent Workbench:

1. **Intake Agent** – Collects service information.
2. **Query Agent** – Retrieves service and incident data.
3. **Incident Advisor Agent** – Investigates incidents and recommends possible solutions.

## Data Source
Google Sheets

## AI Tools
- SNS Agent Workbench
- Google Sheets
- GitHub API Tool Node

## Human Approval
A human approval step is included before remediation or incident-ticket logging.

## Expected Outcome

A no-code AI prototype that assists engineers throughout the production incident lifecycle:

Detect → Investigate → Identify Root Cause → Recommend Remediation → Validate Fix

## Learning Scope
- Basics of AI
- Design Thinking
- LLM Foundations
- Prompt Engineering
- Python (practice only)

## Reference
OnePatch – Automate on-call at agent-scale (YC 2026)
https://www.ycombinator.com/companies/onepatch
