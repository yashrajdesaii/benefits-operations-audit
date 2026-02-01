# Eligibility Rules (v1)

## Health (Medical), Dental, Vision
Eligible if:
- employment_type = FT
- hours_per_week >= 30

## 401(k)
Eligible if:
- employment_type in (FT, PT)
- hours_per_week >= 20

## Interns
- Interns are not eligible for benefits in v1 (for simplicity)

## Coverage Tier Rules (dependents_count)
- Employee: dependents_count = 0
- Employee+Spouse: dependents_count >= 1 (treat spouse as 1 dependent in this mock)
- Employee+Child: dependents_count >= 1
- Family: dependents_count >= 2

