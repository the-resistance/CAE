# ALGORITHMIC SPECIFICATION
## Convergent Archetype Framework (CAF)

Version: 1.0.0  
Author: Kevin Mahan  
Location: Las Vegas, Nevada  
Contact: repos@khalisti.ai  

---

# 1. Purpose

This document formalizes the mathematical and structural logic behind the Convergent Archetype Framework (CAF).

CAF is a symbolic aggregation system designed to measure compatibility and trait convergence across independent classification domains.

---

# 2. Definitions

Domain:  
An independent symbolic classification system (e.g., Western Astrology, Chinese Zodiac).

DomainScore:  
Compatibility output from a domain (0–10 scale).

DomainWeight:  
Assigned influence of a domain within total calculation.

ActiveDomains:  
Domains with sufficient data to compute.

TraitVector:  
Mapped trait strengths for an individual per domain.

ConfidenceFactor:  
Scalar (0–1) representing data completeness.

---

# 3. Compatibility Calculation

## 3.1 Normalized Model

Used when domain completeness varies.

FinalScore =  
Σ (DomainScore × DomainWeight)  
/  
Σ (ActiveDomainWeights)

Prevents dominance from incomplete systems.

---

## 3.2 Non-Normalized Model

Used when full birth data exists.

FinalRawScore =  
Σ (DomainScore × DomainWeight)

Preserves structural signal strength.

---

# 4. Multi-System Alignment Theory (MSA)

TraitStrength(T) =  
SupportingDomains(T)  
/  
ActiveDomains

If 6 out of 8 domains reinforce “Analytical Thinking,”

TraitStrength = 6 / 8 = 0.75

High convergence = reinforced archetype.

---

# 5. Conflict Detection

ConflictIndex =  
OpposingDomainSignals / ActiveDomains

Used to identify internal structural tension.

---

# 6. Confidence Index

Confidence =  
(ActiveDomains / TotalDomains)  
×  
DataCompletenessFactor

DataCompletenessFactor:

- Full date/time/location: 1.0  
- Missing time: 0.85  
- Missing location: 0.9  
- Date only: 0.7  

CompatibilityScore and ConfidenceScore remain independent outputs.

---

# 7. Tier Classification

90–100: Structural Convergence  
80–89: Strong Alignment  
70–79: Viable Alignment  
60–69: Conditional  
50–59: Low Harmony  
<50: High Friction  

---

# 8. Structural Principles

- No domain supremacy.
- Equal baseline weighting unless literature refinement indicates otherwise.
- All scoring matrices must be documented and versioned.
- No silent weight changes between versions.

---

End of Algorithmic Specification v1.0.0
