# Welfare Shield

**Second Place – Hackathon Project**

Welfare Shield is an AI-powered public fund monitoring platform designed to detect welfare fund leakage in real time.  
It converts large-scale welfare datasets into actionable intelligence that enables transparent and data-driven governance.

---

Problem Statement

Governments allocate billions of rupees to welfare programs such as pensions, scholarships, gas subsidies, and fertilizer schemes.  

However, a meaningful portion of these funds is lost due to:

- Ghost beneficiaries  
- Duplicate records  
- Regional data anomalies  
- Shared bank accounts or mobile numbers across multiple beneficiaries  

Traditional audit mechanisms are manual, reactive, and time-intensive.

---
## Proposed Solution

Welfare Shield introduces a scalable analytics engine that:

- Detects anomalous patterns in welfare datasets  
- Assigns risk scores based on density and behavioral indicators  
- Generates structured evidence packages for audit teams  
- Provides interactive visualizations for rapid decision-making  

The platform enables proactive detection instead of post-fraud investigation.

---
## System Architecture

### 1. Data Ingestion
- Data cleaning and preprocessing  
- Normalization across heterogeneous welfare schemas  
- Unified structured data layer  

### 2. Pattern Recognition
- Ensemble Machine Learning models  
- XGBoost-based classification  
- Statistical anomaly detection  
- Detection of impossible clusters (e.g., multiple beneficiaries linked to a single bank account)

### 3. Risk Scoring Framework
- Density-based risk categorization  
- Evidence-backed alerts including:
  - Transaction slices  
  - Identity linkages  
  - Contact overlaps  
  - Confidence scores  

---

## Core Features

- State-level risk heatmaps  
- Drill-down analysis to district and village level  
- Prioritization of hotspots based on expected recoverable funds  
- Cross-program scalability (Pensions, Scholarships, Gas Subsidies, Fertilizers)

---

## Technology Stack

**Frontend**
- React
- Tailwind CSS

**Backend**
- FastAPI

**Machine Learning**
- XGBoost
- Anomaly Detection Models

**Database**
- PostgreSQL
- PostGIS

---

## Impact

- Significant reduction in audit triage time  
- Improved detection of systemic fraud patterns  
- Increased transparency in welfare fund distribution  
- Scalable framework adaptable across multiple government programs  

---

## Future Roadmap
- Integration with Direct Benefit Transfer (DBT) logs  
- Bank reconciliation mechanisms  
- Automated investigator workflows  
- Predictive interdiction to block suspicious disbursements before release  

## Team
Team 404 Not Found  
-Sriman Keerthi
- Ghousiya Begum  
- Siri Adusumalli  
---
## Vision

When fund leakage is minimized, public trust is restored.  
Welfare Shield aims to make governance measurable, transparent, and accountable.
