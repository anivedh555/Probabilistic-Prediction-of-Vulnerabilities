# Probabilistic-Prediction-of-Vulnerabilities

1. Feature Engineering

CVSS v3 and Qualys severity

EPSS exploit probability

CISA Known Exploited Vulnerabilities (KEV)

Exploit availability (PoC / weaponisation)

Internet exposure and lateral-movement potential

Asset criticality and infrastructure role

Vulnerability age (risk drift)

2. Sigmoid Risk Scoring

Non-linear risk scoring using a calibrated logistic equation

Produces a continuous 0–100 risk score

Prevents “everything is critical” syndrome common with CVSS-only models

3. Probabilistic Business-Criticality Prediction

Logistic regression model estimating
P(vulnerability is business-critical)

Outputs interpretable probabilities instead of binary labels

Designed for executive escalation, emergency patching, and SLA decisions

Coefficient-based explainability (odds ratios, feature influence)

4. Actionable Outputs

Priority bands (P0–P3) with remediation SLAs

Risk explanations highlighting key drivers (e.g. KEV + exposure + EPSS)

Patch-team-friendly prioritisation rather than raw vulnerability counts
