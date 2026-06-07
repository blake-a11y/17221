# Electrical - As-Built (from panel photographs)

**Source:** Homeowner photographs of the exterior service equipment, the main panel interior (dead front removed), and the panel spec/permit labels. Cross-referenced with `04-electrical.md`, `04a-electrical-capacity.md`, `06-hvac.md`, `08-solar.md`.

## Service and main panel
| Item | Value |
|---|---|
| Service size | 200A (Eaton CSR 25k main breaker, 2-pole, 120/240V, "Service Disconnect") |
| Panel | Eaton MBE4040B200-series, meter-main combination |
| Panel rating | 200A max, 120/240 VAC, single-phase, 3-wire |
| Spaces | 40 |
| Enclosure | Type 3R (outdoor / rainproof) |
| Meter socket rating | 170A continuous |

This confirms the 200A service that the EV installer's photo estimate reported (see `04a-electrical-capacity.md`).

## Circuit directory (from handwritten panel labels)
Amperages are only partly legible in the photographs and should be verified at the panel. Labels as written:

- Left bank: Bed4 / Bath3 / Hall; Garage x2 GFI; Laundry / Attic / O/S GFI; North Air Handler; South Air Handler; Front North A/C #1; Back South A/C #2; Mini Split; Sub Panel; RV Plug.
- Right bank: Bath GFI; Kit A GFI; Kit B GFI; DW / Disp; Micro; Hood; Refer; Holiday; Washer; Dryer; Cooktop; Oven.

Notable confirmations:
- A Sub Panel feed and an RV Plug circuit are present, matching the EV installer's note of "a 50A subpanel and an 80A circuit."
- An inverter backfeed breaker is present, marked "Inverter Output Connection - Do Not Relocate."

## HVAC equipment (count and layout)
Two central split systems plus one mini-split:
- North Air Handler + Front North A/C #1
- South Air Handler + Back South A/C #2
- Mini Split (third zone)

Matches the three A/C symbols on the rear-landscape plan. Tonnage, SEER, and models are still not specified. See `06-hvac.md`.

## Solar interconnection
| Item | Value |
|---|---|
| Meter | Bi-directional APS meter, FOCUS AXRe-SD, Class 200, 240V (net-metered) |
| AC disconnects | Two Siemens 100A 240V disconnects - one DER-side / bi-directional-meter disconnect, one utility disconnect |
| PV AC disconnect rating | 48A at 240V (inverter AC output) |
| Backfeed | Inverter output breaker in the main panel ("do not relocate") |

Both the total load and the solar backfeed must fit within the panel bus rating (the code "120% rule"); a licensed electrician verifies this in any load calculation.

## Authority having jurisdiction
Maricopa County (Building Safety Division / Inspection Services Division, 602-506-3301). Green county inspection stickers are affixed to the panel, one hand-marked with the property address. This confirms the AHJ is Maricopa County and resolves the prior conflict where an EV document referenced "City of Waddell" (Waddell is unincorporated county). Inspection/approval dates on the stickers are partially legible (2023).

## Other labels observed
- Eaton "Service Entrance Barrier Kits" and arc-fault breaker owner-instruction stickers.
- Northwest Exterminating Company termite pre-treatment sticker (LIC# C4410BCE).

## Still outstanding
- Stamped load calculation and a verified breaker-by-breaker amperage schedule (licensed electrician).
- HVAC tonnage / SEER / model numbers.
- Builder construction-set electrical documents (panel schedule, service/load calc) requested from Elliott Homes.

Redaction note: meter serial number, inspector names/signatures, and account identifiers omitted; this repo is public.
