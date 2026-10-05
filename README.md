# VisaBuddy

**Personalized visa eligibility and approval insights using official requirements, structured rules, and historical visa outcomes.**

VisaBuddy is a visa assessment platform designed to help applicants better understand their visa requirements, identify potential issues in their application profile, and prepare more effectively before applying.

Rather than providing a simple pass/fail prediction, VisaBuddy combines structured applicant information with official visa requirements, evidence-backed rules, and historical application outcomes to generate a more transparent assessment.

> **Disclaimer:** VisaBuddy is an independent research and decision-support project. It does not provide legal advice, guarantee visa approval, or represent any government, embassy, consulate, or visa authority.

## What VisaBuddy Does

VisaBuddy evaluates information such as:

- Passport nationality
- Country of residence
- Destination country
- Visa type
- Passport validity and issue date
- Residence permit validity
- Previous international travel
- Previous visa refusals
- Intended travel information

The platform is being designed to provide applicants with:

- Visa eligibility and requirement checks
- Personalized application assessment
- Potential risk or missing-information indicators
- Evidence-backed explanations
- Relevant document requirements
- Historical visa outcome context
- Practical steps to strengthen application readiness

## Why VisaBuddy?

Visa information is often distributed across government portals, consulates, visa centres, regulations, and country-specific guidance.

VisaBuddy aims to transform this information into a structured assessment experience.

Instead of only answering:

**"What documents do I need?"**

VisaBuddy aims to help answer:

**"Based on my specific circumstances, what requirements apply to me, what should I pay attention to, and why?"**

## How It Works

```text
Applicant Profile
       │
       ▼
Canonical Applicant Facts
       │
       ├───────────────┐
       ▼               ▼
Official Rules     Outcome Data
       │               │
       ▼               ▼
Rule Evaluation   Profile Matching
       │               │
       └───────┬───────┘
               ▼
        Visa Assessment
               │
               ▼
    Personalized Report
```

VisaBuddy separates factual eligibility requirements from historical outcome information so that statistical patterns are not presented as official visa rules.

## Evidence-First Approach

VisaBuddy is being developed around an evidence-based rule system.

Official requirements are mapped to their supporting sources before being converted into assessment rules. The project maintains structured evidence records and validation checks so that requirements can be traced back to their source.

Examples of sources used during research include:

- European Union visa regulations
- Schengen visa rules
- Official government immigration portals
- France-Visas
- Official Irish immigration guidance
- Published visa statistics

Community and historical outcome data are treated separately from official requirements.

## Current Scope

The initial assessment pathway focuses on:

**Indian passport holder → Resident in Ireland → France / Schengen short-stay tourist visa**

This narrow starting scope allows the underlying evidence model, rule engine, and assessment architecture to be validated before expanding to additional visa routes.

Planned expansion includes:

- Additional Schengen destinations
- United Kingdom
- United States
- Additional passport and residence combinations
- Additional visa categories

## Project Architecture

The project is structured around several layers:

```text
User Interface
      │
      ▼
Assessment Layer
      │
      ├── Applicant Fact Normalization
      ├── Material Question Evaluation
      ├── Eligibility / Requirement Rules
      └── Assessment Configuration
      │
      ▼
Evidence & Data Layer
      │
      ├── Official Requirements
      ├── Evidence Records
      ├── Historical Outcomes
      └── Community Data
      │
      ▼
Personalized Report
```

The architecture is intentionally designed so additional countries and visa routes can be introduced through structured configurations and evidence rather than rebuilding the application for every destination.

## Technology

Current development includes:

- JavaScript
- HTML
- CSS
- Modular rule evaluation
- Configuration-driven assessments
- CSV-based historical outcome datasets
- Automated test coverage
- Git / GitHub

The project currently prioritizes deterministic, explainable rules rather than using an LLM to make visa eligibility decisions.

## Development Status

VisaBuddy is currently under active development.

Work completed or underway includes:

- Applicant data normalization
- Canonical applicant facts
- Historical outcome-data processing
- Visa profile matching
- Evidence schema
- Official requirement research
- Rule-engine foundation
- Assessment configurations
- Material-question framework
- Automated testing
- Browser-based assessment workflow

The current version should be considered an **experimental prototype**, not a production visa advisory service.

## Roadmap

Planned development includes:

1. Complete the initial France/Schengen assessment flow
2. Strengthen evidence verification and source traceability
3. Improve personalized assessment reports
4. Expand historical and anonymous community outcome datasets
5. Introduce additional Schengen destinations
6. Add UK and US visa pathways
7. Improve country-agnostic assessment configuration
8. Explore AI-assisted explanations while keeping eligibility decisions grounded in deterministic rules and verified evidence

## Data Philosophy

VisaBuddy distinguishes between three important concepts:

**Official requirements**  
Rules and requirements derived from authoritative sources.

**Historical outcomes**  
Aggregated visa application statistics and previous application outcomes.

**Community data**  
Anonymous applicant-reported outcomes that may provide additional context but are never treated as official requirements.

This separation is intended to make assessments more transparent and reduce misleading conclusions.

## Important Disclaimer

VisaBuddy does **not** predict or guarantee the decision of an embassy, consulate, immigration authority, or visa officer.

Visa decisions can involve individual circumstances and discretionary assessment that cannot be fully represented by software.

The platform is intended to help users understand requirements and prepare their applications more effectively.

---

### Status

🚧 **Active Development**

VisaBuddy is currently being developed as an evidence-driven visa assessment and decision-support platform.
