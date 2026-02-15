# SwasthyaMarg – Health Pathway

Voice-First, Location-Aware AI Health Triage & Referral System for India

---

## Overview

SwasthyaMarg is an India-first, voice-enabled, AI-assisted health triage and referral platform designed to improve early health screening and correct routing to care.

The system enables users to speak their health inputs instead of typing, receive explainable risk prioritization (not diagnosis), and get guided to the nearest appropriate healthcare facility. It includes a structured feedback loop that allows the system to improve over time.

SwasthyaMarg is designed as decision-support infrastructure for public health deployment across villages, campuses, and industrial environments.

---

## Problem

India’s healthcare challenge is not primarily a shortage of hospitals, but delayed screening, inconsistent triage, and misdirected patient flow.

Many individuals:
- Do not know how serious their condition is
- Do not know where to seek care first
- Face literacy and language barriers
- Cannot effectively use text-heavy digital systems

This results in:
- Overcrowded tertiary hospitals
- Underutilized Primary Health Centers (PHCs)
- Delayed intervention for high-risk cases

SwasthyaMarg addresses accessibility, triage standardization, and efficient referral.

---

## Core Features

- Voice-first health input (Speech-to-Text)
- Natural language number and unit understanding
- Explainable rule-based AI triage
- Location-aware healthcare facility recommendation
- Spoken guidance (Text-to-Speech)
- Feedback-driven continuous improvement
- Institutional dashboard for monitoring and analytics

---

## System Workflow

1. User provides spoken health inputs.
2. Speech-to-Text converts audio into structured text.
3. Language model extracts numerical meaning and identifies units.
4. Inputs are normalized into standardized medical formats.
5. Triage engine assigns a risk level.
6. Referral engine identifies the nearest appropriate facility.
7. System provides actionable guidance.
8. User feedback is collected post-referral.
9. Aggregated insights support system improvement.

---

## Architecture

### Frontend

Mobile Application (Expo – React Native)
- Guided screening flow
- Voice capture
- Risk result display
- Referral guidance
- Feedback submission

Web Dashboard
- Screening statistics
- Risk distribution
- Referral analytics
- Feedback tracking

### Backend

Stateless REST APIs providing:

- Speech-to-Text processing
- Natural language and unit parsing (LLaMA-4 assisted)
- Explainable rule-based triage engine
- Location-based referral engine
- Feedback and analytics module

The architecture is modular and scalable for cloud deployment.

---

## AI Components

### Speech-to-Text
Converts spoken health inputs into structured text.

### Natural Language Understanding (LLaMA-4)
Extracts numerical values and identifies units from conversational input.
Normalizes all values into standardized formats before triage.

### Explainable Rule-Based AI
Assigns Low, Moderate, or High risk using predefined medical thresholds.
Provides reasoning for each decision.

### Decision Intelligence
Combines risk level and approximate location to recommend the appropriate level of care.

AI is used as decision-support infrastructure, not as a diagnostic system.

---

## Technology Stack

### Software
- Expo (React Native)
- Web dashboard frontend
- Node.js or FastAPI backend
- REST API architecture
- LLaMA-4 language processing layer
- Speech-to-Text and Text-to-Speech modules
- Rule-based AI logic

### Optional Hardware
- Smartphone or tablet
- Digital thermometer
- Pulse oximeter
- Blood pressure monitor

System remains functional even without connected sensors.

---

## Deployment Model

SwasthyaMarg can be deployed in:
- Rural villages
- Primary Health Centers
- Industrial facilities
- University campuses
- Public health camps

Deployment options:
- Cloud-based infrastructure
- Containerized services (Docker)
- Hybrid edge-cloud setups for low connectivity regions

Designed for horizontal scalability.

---

## Security and Privacy

- No personal identifiers required
- Approximate location only
- No disease diagnosis
- Transparent and explainable triage logic
- Privacy-conscious architecture

---

## Impact

Immediate Impact:
- Faster triage decisions
- Reduced manual screening load
- Clear referral pathways

System-Level Impact:
- Reduced hospital congestion
- Improved PHC utilization
- Standardized triage across locations

Long-Term Impact:
- Data-informed public health planning
- Efficient healthcare resource allocation
- Scalable national health pathway model

---

## Disclaimer

SwasthyaMarg provides health risk screening and referral guidance.
It does not diagnose medical conditions or replace professional medical consultation.
