# Technology Control Plan (TCP)

## Purpose
This document defines how controlled technologies, AI systems, and sensitive data are identified, isolated, and protected across environments.

## Controlled Categories
- Export-controlled technology (ITAR/EAR)
- Controlled Unclassified Information (CUI)
- Proprietary AI models and training data
- Source code tied to sensitive systems

## Core Principles
1. Classification – identify what is controlled
2. Isolation – separate controlled environments
3. Access Control – restrict and monitor access

## Environment Segregation
- Controlled Environment (restricted systems, models, data)
- Uncontrolled Environment (general engineering, public tools)

## Access Controls
- Role-based access
- MFA enforcement
- Logging and monitoring

## Data Handling
- Controlled data stored only in approved environments
- No use of unapproved tools (e.g. public AI tools)
- Restricted transfer between environments

## Communication Controls
- Controlled discussions limited to authorized personnel
- No sensitive discussions in open/public environments

## Governance
- Periodic review of access
- Change tracking for systems and personnel
- Incident escalation procedures
