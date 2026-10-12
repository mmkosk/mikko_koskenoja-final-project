# A/B Experiment Brief, Riverty business-unit case

## Parameters
| Parameter | Decision |
|---|---|
| Feature under test | Riverty card |
| Persona | A financially stable heavy BNPL user who runs Klarna, PayPal and Riverty at the same time. |
| Expected outcome | Increase in engaged overview sessions |
| Primary success metric | Weekly overview rate |
| Baseline rate | 10% |
| Guardrail metric | BNPL volume per heavy user |
| Guardrail boundary | 560€ |
| Second guardrail | · |
| Minimum Detectable Effect | 2% |
| Sample size per arm | 100 |
| Traffic split | 50 / 50 |
| Test duration | 14 days |
| Significance threshold | p < 0.05 |

## Control vs. Variant
- **Control (A):** The merchant name shows the resolved merchant. If none resolves, it shows the raw descriptor with an “Unverified name” tag.
- **Variant (B):** 100% of rows have a name. 0 guessed names.
- **Held constant (isolation check):** no other changes

## Hypothesis
> I believe that Riverty card for A financially stable heavy BNPL user who runs Klarna, PayPal and Riverty at the same time. will result in Increase in engaged overview sessions, as measured by a 2% change in Weekly overview rate within 14 days. We will protect BNPL volume per heavy user throughout the test.

## Shipping criteria
> We will **ship** if Weekly overview rate improves by ≥ 2% at p < 0.05 and BNPL volume per heavy user does not reach 560€ after 14 days.
> We will **iterate** if direction is positive but lift is below the MDE.
> We will **kill** if the primary metric shows no improvement or moves negatively.
> The read date is fixed at the end of 14 days, no results reviewed before this date.
