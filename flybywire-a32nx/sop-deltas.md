# SOP Deltas

These notes are a deliberately lean single-pilot flow, not the full
[FlyByWire A32NX SOP](https://docs.flybywiresim.com/pilots-corner/) (rev.
30 NOV 2021, 84 pages). This page records where they differ, so the gaps are
known rather than accidental. SOP sections are cited by name.

Everything the SOP specifies for the phases these notes cover has now been
adopted. What remains below under [Not covered](#not-covered) is skipped by
choice.

## Corrections taken from the SOP

| Item | Was | Now | SOP section |
| --- | --- | --- | --- |
| APU BLEED in prep | "if COVID" | **once APU AVAIL** — and never with an LP/HP ground air unit connected | Preliminary Cockpit Preparation → Air Conditioning |
| BEACON | ON at takeoff | **ON at start clearance**, before anything moves; OFF at the gate once engines spool down | Before Pushback or Start → Exterior Lights; Parking |
| Engine start order | ENG 1 then ENG 2 | **ENG 2 first**, then ENG 1 — pressurises the yellow hydraulic system | Automatic Engine Start |
| PACK 1 & 2 | "as required" at takeoff, never restored | **OFF** for takeoff, back **ON** at thrust reduction altitude (PACK 2 ≥ 10 s after PACK 1) | Before Takeoff; Takeoff → At Thrust Reduction Altitude |
| STROBE after landing | "ON or AUTO" | **AUTO** when leaving the runway; **ON** whenever crossing a runway | After Landing → Exterior lights |
| Reverse thrust | REV FULL, idle at 60 kt | **REV MAX** at touchdown, **REV IDLE at 70 kt**, stow at taxi speed | Manual Landing |
| Autobrake release | manual brake at 40 kt | **disengage before 20 kt** | Manual Landing → Before 20 Knots |
| SEAT BELTS at 10,000 ft descending | "as required" | **ON** | Descent → At 10 000 feet |
| Radar after landing | not covered | **WX RADAR and PWS OFF** — avoids radiating ground crew | After Landing |
| NO SMOKING sign | ON | **AUTO** — off-AUTO signs stop the emergency batteries charging | Cockpit Preparation → Signs |
| Centre tank fuel | CTR TK PUMP always ON | **FUEL MODE SEL verify AUTO**; below 200 kg / 440 lb in the centre tank, MODE SEL **MAN** and CTR TK PUMP 1 & 2 **OFF** | Cockpit Preparation → Fuel |
| Batteries | "set ON" | **set AUTO**, then verify charge **below 60 A and decreasing** on the ECAM ELEC page | Cockpit Preparation → Electrical |
| Approach flaps and gear | V<sub>FE</sub> − 15 and S speed, keyed off FMA colour | restructured by **green dot speed** → **2,000 ft AGL** → **flaps at 2** → **gear down** | Intermediate/Final Approach - General |
| Autopilot on approach | AP 1 only | **both AP 1 and AP 2** engaged at APPR, with LOC and G/S armed and go-around altitude set | Approach Using LOC G/S Guidance |
| Transponder at the gate | left in AUTO | **STBY** | Parking |
| Engine cooldown | not covered | **5 min** between start and takeoff; **3 min** at idle before shutdown after high thrust | After Start; Parking |
| Takeoff PERF entries | FLAPS, FLEX, V1, VR, V2 | adds **T.O SHIFT**, **THR RED/ACC**, **ENG OUT ACC**, **FLAPS/THS** | Takeoff Data Insertion |

Picked up incidentally while making the above changes, all from
*Parking*: ENG and WING ANTI ICE **OFF**, BRK FAN **OFF**, EXT PWR **ON** only
*if the APU is unavailable* (previously "if AVAIL"), and APU BLEED ON placed
before engine shutdown rather than after.

## Not covered

Whole SOP sections these notes skip by choice:

- **Exterior inspection** — the full walkaround.
- **Preliminary cockpit preparation detail** — battery voltage check against the
  25.5 V threshold, oxygen / hydraulic / oil quantity checks on the ECAM, CVR
  test, oxygen mask test, cockpit door test, ISIS and clock checks,
  A/SKID & N/W STRG ON, PROBE/WINDOW HEAT AUTO, PACK FLOW selection,
  RCDR GND CTL, ATC SYS selection, audio control panels, circuit breaker panels,
  logbook and MEL/CDL.
- **Briefings and crosschecks** — takeoff briefing, approach briefing, loadsheet
  and performance crosschecks, and the PF/PM task split the SOP is written
  around, including the standard callouts (thrust set, one hundred knots, V1,
  positive climb, one hundred above, minimum).
- **Approach modes other than LOC G/S** — FINAL APP guidance, FPA guidance, and
  the guidance-mode-per-approach-type matrix.
- **Go around**, **autoland**, and **degraded guidance procedures** for CAT II
  and CAT III.
