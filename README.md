# AI-Driven Adaptive Cyber Deception System

**Artificial Intelligence · Cybersecurity · Machine Learning · Contextual Bandits**

An interdisciplinary senior graduation project investigating adaptive cyber deception through machine-learning classification and feedback-driven decoy selection.

**Status:** Senior Project I — Research, Requirements & System Design  
**Implementation:** Planned for Senior Project II  
**Source Code:** Not Available in This Showcase

## Project Overview

Traditional honeypots collect interaction logs but commonly expose static decoys.

This project proposes an isolated educational laboratory that analyzes simulated SSH session behavior and selects synthetic decoy content based on predicted session interests.

The research focuses on whether adaptive selection provides measurable advantages over fixed or rule-based approaches.

## Proposed System Architecture

The planned system combines:

- **Cowrie Honeypot:** Captures controlled SSH interactions and session logs.
- **Behavior Classification:** Uses session-level features and a proposed Random Forest classifier.
- **Adaptive Decoy Selection:** Selects synthetic Finance or Admin portals.
- **Contextual Bandit:** Learns from observed portal engagement.
- **Operator Dashboard:** Presents session timelines, decisions, predictions, and experiment results.

All experiments are intended for an isolated, authorized environment using synthetic data.

## Planned Policy Comparison

| Policy | Selection Approach |
|---|---|
| Fixed | Uses a predefined decoy |
| Rule-Based | Applies deterministic behavioral rules |
| ML-Only | Uses supervised classification |
| ML + Bandit | Combines model predictions with feedback learning |

## Completed Academic Work

Senior Project I documents:

- Problem definition and research objectives.
- Literature review and feasibility study.
- Functional and non-functional requirements.
- System architecture and component responsibilities.
- Use-case, context, sequence, and data-flow diagrams.
- Proposed evaluation methodology and safety constraints.

## Current Limitations

The system implementation, model training, contextual-bandit experiments, and performance measurements have not yet been completed.

No model accuracy, engagement improvement, or operational deployment is claimed.

## Planned Next Phase

Senior Project II will focus on building the isolated laboratory, implementing the classification and decoy-selection components, integrating the mock portals and dashboard, and comparing the four policies through controlled experiments.

## Academic Team

An interdisciplinary three-member graduation project at Effat University, covering Artificial Intelligence, Cybersecurity, and General Computer Science.

**Yasser Alassad — Artificial Intelligence Track**

The team collaborates on the overall research and design. Individual implementation contributions will be updated as the project progresses.

## Safety & Ethics

This project is intended exclusively for authorized educational cybersecurity experiments. It does not involve real attacker targeting, real organizational credentials, or production deployment.

## Developer

**Yasser Alassad**  
Computer Science — Artificial Intelligence Specialization  
Effat University

[GitHub](https://github.com/yasser1555) · [LinkedIn](https://www.linkedin.com/in/yasser-alassad/) · [Portfolio](https://yasser-alassad-portfolio.vercel.app/)
