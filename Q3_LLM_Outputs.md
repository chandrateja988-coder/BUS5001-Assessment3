# Q3 — LLM ESG Message Triage Experiment Log

## Model Used
GPT-4o via ChatGPT interface

## Revised Prompt
- Added explicit urgency definitions (LOW/MEDIUM/HIGH/CRITICAL)
- Added JSON-only output instruction
- Added data sensitivity risk field
- Added hallucination prevention instruction

## Message 1
**Input:** "There is a water leak in Building C that has been running all morning."
**Output:**
- issue_category: Environmental Management
- urgency_level: HIGH
- sentiment: Neutral
- followup_required: Yes
- recommended_team: Facilities and Maintenance
- escalation_reason: Continuous resource waste and potential building damage
- data_sensitivity_risk: Low

## Message 2
**Input:** "The recycling bins are contaminated again and nobody is checking them."
**Output:**
- issue_category: Waste Management
- urgency_level: LOW
- sentiment: Frustrated
- followup_required: true
- recommended_team: Facilities and Waste Management
- escalation_reason: Repeated contamination and lack of monitoring

## Message 3
**Input:** "The accessible entrance near the main building has been blocked for two days."
**Output:**
- issue_category: Accessibility & Facilities Compliance
- urgency_level: HIGH
- sentiment: Neutral
- followup_required: YES
- recommended_team: Facilities Management / Diversity & Inclusion Compliance
- escalation_reason: Ongoing compliance and physical barrier issue
