# Electrical Service Capacity

**Sources:** Email correspondence with a licensed EV installer (EV Charging Solutions, LLC, ROC# 325685), Dec 12-18, 2024, based on photographs of the main panel. Cross-referenced with `04-electrical.md`, `07-pool-spa.md`, `08-solar.md`, `09-ev-charging.md`.

> This tile answers the practical question: **can another 240V circuit be added to the house?** Short answer: **not as the panel currently sits.**

## Bottom line
- Main service: **200A**.
- A licensed EV installer calculated the panel at **216A - over the 200A limit** - before the EV charger was added.
- Adding another 240V circuit is **not advisable as-is**. The realistic paths are to reduce existing load or upgrade the service (the installer recommended 400A).

## Documented figures
| Item | Value |
|---|---|
| Main service size | 200A |
| Existing calculated load | 216A (over the 200A limit) |
| Calculated load if the 50A RV plug is removed | 196A (just under) |
| Installer conclusion | Charging could not be added without removing both the 80A circuit and the 50A RV outlet |
| Recommended fix | Upgrade main service to 400A (multi-week process with permitting + APS coordination; cost redacted) |

The 216A figure was a **screening estimate from panel photos**, not a stamped load calculation. A formal calculation using demand factors often yields a lower number. Treat it as directional, not final.

## Existing 240V loads on record
- EV charger: 2-pole 50A breaker, 32A continuous draw (`09-ev-charging.md`)
- Pool heat-pump hookup: 80A (`07-pool-spa.md`)
- RV garage: 240V outlet - identified by the installer as a 50A RV plug (`04-electrical.md`)
- Solar: 9.84 kW, Tesla inverter, backfeeding the panel (`08-solar.md`). Solar backfeed plus total load both have to fit within the panel bus bar rating (the electrical-code "120% rule"), which an electrician verifies.

## Open questions (resolve before adding any 240V load)
1. **What the 80A circuit feeds.** The installer flagged it as a large "future use" pull. The homeowner reported that the pool company ran a backyard line for a hot tub that was never installed, and separately that the pool heat/cool function is unused. If the 80A is an unused stub, removing it from the calc frees a large block of capacity. If it is the working pool heat pump, it is real load. This single point swings the answer.
2. **How the EV charger was ultimately added.** A second company installed the NEMA 14-50 on a 50A circuit days after the first installer said the panel was over capacity. It is unconfirmed whether they reused existing capacity or added a new circuit. The recorded install shows a ~90 ft home run to the main panel, which resembles a new circuit. Worth confirming - an overloaded panel is a safety issue.

## Recommended next step
Have a licensed electrician perform a **formal load calculation** and confirm: the actual service rating, the true connected/demand load, the number of open breaker spaces, and the bus bar rating (accounting for the solar backfeed). That result determines whether any new 240V circuit can be added or whether a service upgrade is required.

## Status vs. other files
This tile supersedes the "service amperage: not specified" entry in `04-electrical.md` and partially resolves item 4 in `_meta/open-gaps.md`. A stamped load calculation and the formal panel schedule are still outstanding.
