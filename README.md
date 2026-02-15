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

<img width="1178" height="920" alt="Screenshot 2026-02-06 135016" src="https://github.com/user-attachments/assets/d462a1f1-0c02-41c7-ae03-467bb395ef28" />
<img width="1058" height="743" alt="Screenshot 2026-02-06 135005" src="https://github.com/user-attachments/assets/be45cc28-e66b-4546-93c8-064d87309217" />
<img width="713" height="361" alt="Screenshot 2026-02-06 144054" src="https://github.com/user-attachments/assets/45da7991-c53f-455a-8f9f-903bd355c94a" />
<img width="996" height="296" alt="Screenshot 2026-02-06 142631" src="https://github.com/user-attachments/assets/a81a4e72-faa2-400c-94db-3655a8aae1e1" />
<img width="984" height="555" alt="Screenshot 2026-02-06 142610" src="https://github.com/user-attachments/assets/7a029541-3203-4e0c-8983-5b26ddc9d07b" />
<img width="901" height="246" alt="S<img width="1685" height="931" alt="Screenshot 2026-02-06 134925" src="https://github.com/user-attachments/assets/48ae6878-14d4-4f2a-8cfb-3520d5382afa" />
creenshot 2026-02-06 142504" src="https://github.com/user-attachments/assets/74f1c216-ed61-464a-90a8-cb2c1f8711e6" />
<img width="1065" height="831" alt="Screenshot 2026-02-06 135135" src="https://github.com/user-attachments/assets/396c0562-6115-4d2a-aa28-3089fb330856" />
<img width="1023" height="921" alt="Screenshot 2026-02-06 135118" src="https://github.com/user-attachments/assets/6c<img width="1685" height="931" alt="Screenshot 2026-02-06 134925" src="https://github.com/user-attachments/assets/cf51412c-3<img width="1348" height="913" alt="Screenshot 2026-02-06 134935" src="https://github.com/user-attachments/assets/a58eff3f-5d16-43f2-9754-1feead1bf403" />
821-4f47-8a24-6a20bb0b88d4" />
d124de-140a-4402-aaa2-0b73c20453a0" />
<img width="1053" height="829" alt="Screenshot 2026-02-06 135056" src="https://github.com/user-attachments/assets/0c3e9047-26d9-43f6-809e-3a2f41e0d234" />
<img width="1132" height="880" alt="Screenshot 2026-02-06 135044" src="https://github.com/user-attachments/assets/80fe5456-299b-4b86-a1bb-eac5b3b25e67" />


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
