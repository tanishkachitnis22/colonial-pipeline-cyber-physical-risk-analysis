# Cyber–Physical Vulnerability Assessment of the Colonial Pipeline

## Overview
This research examines the Colonial Pipeline incident as a cyber–physical systems failure, demonstrating how cyber compromise in IT environments can cascade into physical shutdowns, supply disruption, and national-level economic impact.

The study models cyber and physical risks separately using cascade and flow network representations, then integrates risk reduction and investment optimization using the Mission-Based Risk Assessment (MBRA) framework and fault tree analysis.

## Why This Matters
The 2021 Colonial Pipeline ransomware incident demonstrated that cyber events do not need to directly compromise Operational Technology (OT) to cause physical disruption. Precautionary shutdowns alone can propagate severe downstream impacts.

This work shows how cyber risk, physical vulnerability, and infrastructure topology interact to create asymmetric, cascading failures in critical energy systems.

## Methodology
- **Cyber risk modeling:** Undirected cascade network representing bidirectional IT/OT dependency
- **Physical risk modeling:** Directed flow network representing fuel transport dependencies
- **Network analysis:** Degree, betweenness, eigenvector centrality, spectral radius
- **Resilience modeling:** Fractal dimension and critical vulnerability estimation
- **Risk optimization:** MBRA-based prevention and response budget allocation
- **Failure analysis:** Fault Tree Analysis for cyber and physical attack scenarios

## Key Findings
- High-betweenness nodes (Houston, Atlanta) dominate both cyber cascade risk and physical disruption potential
- Cyber incidents propagate through control dependencies, while physical failures propagate strictly downstream
- Targeted investment at backbone and junction nodes produces disproportionate risk reduction
- Physical disruptions produce larger immediate system impact, while cyber events amplify uncertainty and operational shutdown risk

## Practical Implications
- Cybersecurity investments should be prioritized by network criticality, not uniform distribution
- IT-only breaches can justify physical shutdown when OT segmentation and visibility are insufficient
- MBRA provides a defensible framework for CISO and infrastructure operators to justify risk-based funding decisions

## Artifacts
- Full research paper (PDF)
