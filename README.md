# App Architecture & Security Audit

A professional guidance skill for auditing architecture, security, readiness for production, and implementation quality in web, mobile, API, and backend projects.

This repository contains a reusable prompt/skill intended to guide an AI agent to:

- audit an existing application or system;
- assess architecture and security posture;
- identify what is verified, incomplete, missing, unconfirmed, or not applicable;
- prioritize risks and recommendations;
- work with explicit authorization and evidence-based conclusions;
- avoid changing code or environments without clear approval.

## Purpose

The skill is designed for situations where the team needs a structured and disciplined evaluation of:

- software architecture;
- authentication and authorization;
- data protection and privacy;
- API and backend security;
- configuration and secrets handling;
- CI/CD and deployment readiness;
- test coverage and risk prioritization;
- production readiness and incident response posture.

## Core principles

- Understand before recommending.
- Verify before concluding.
- Separate facts, assumptions, and recommendations.
- Apply controls proportionally to the risk and the actual stack.
- Never claim that something was tested or validated without evidence.
- Default to read-only analysis unless the user explicitly authorizes changes.
- Be transparent about limitations and missing information.

## Default operating mode

The default behavior is analysis and guidance only.

The AI should not:

- edit source code without explicit instruction;
- alter production systems without approval;
- install or update dependencies without guidance;
- deploy or change environment settings by default;
- perform destructive or intrusive testing outside the authorized scope.

## Scope of use

This skill is useful for:

- auditing an existing project;
- planning a new application or SaaS;
- reviewing architecture and security decisions;
- assessing readiness for production;
- building a checklist of engineering and security controls;
- preparing a structured review for stakeholders, engineering leads, and product owners.

## File contents

This repository includes the main skill guidance in markdown format, designed to be copied into an agent, prompt, or internal AI workflow.

## Suggested usage

Copy the skill content into your AI agent, workflow, or internal prompt system and use it in one of these contexts:

- project audit;
- architecture review;
- security review;
- migration assessment;
- pre-production checklist;
- implementation planning;
- technical due diligence.

## Example prompts

- Review this application architecture and identify critical security risks.
- Audit this project for authentication, authorization, and data protection gaps.
- Tell me what is verified, missing, or still unconfirmed in this codebase.
- Assess whether this project is ready for production and explain the reasoning.
- Help me build a secure architecture for a new SaaS from zero.

## Notes

This is a guidance skill, not a substitute for:

- formal security audits;
- legal or compliance review;
- specialized penetration testing;
- code execution without authorization;
- testing on production systems.

The goal is to create a disciplined, evidence-based, and risk-aware evaluation framework.

## License

This repository is public for sharing and reuse. Please adapt it to your own workflow and standards as needed.
