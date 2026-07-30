# FlyByWire A32NX

Personal procedures for flying the FlyByWire A32NX in MSFS, gate to gate.

## Flight Planning

- Routes and performance: [SimBrief](https://www.simbrief.com/)
- Charts: [ChartFox](http://chartfox.org/)

## Procedures

| # | Phase | You are |
| --- | --- | --- |
| 1 | [Starting the Aircraft](1-starting-the-aircraft.md) | cold and dark → boarding |
| 2 | [Preparing the MCDU](2-preparing-the-mcdu.md) | at the stand, programming the FMS |
| 3 | [Engine Start and Taxi](3-engine-start-and-taxi.md) | pushback → holding point |
| 4 | [Takeoff, Climb and Cruise](4-takeoff-climb-and-cruise.md) | holding point → cruise |
| 5 | [Descent, Approach and Landing](5-descent-approach-and-landing.md) | top of descent → runway |
| 6 | [After Landing and Taxi to Gate](6-after-landing-and-taxi-to-gate.md) | vacated → taxiing in |
| 7 | [Powering Down](7-powering-down.md) | at the stand → cold and dark |

## Reference

- [Controls Reference](controls.md) — every control, its panel, and its
  documentation link.
- [Abbreviations](glossary.md) — what the flight deck labels stand for, from
  `EXT PWR` to `TA/RA`.
- [Lights by Phase](lights.md) — the full light state matrix.
- [SOP Deltas](sop-deltas.md) — where this lean flow differs from the official
  84-page FlyByWire SOP, and what it leaves out.
- [ATC Communications](../vatsim/atc-communications.md) — call-and-response
  scripts for VATSIM.

## Flight Companion

`companion.html` is an interactive version of everything above, generated from
these markdown files — tick items off as you fly, on a second monitor or tablet.
Progress is saved in the browser, and the ATC worksheet fills the radio calls in
for you. Every abbreviation carries its full name underneath — *external power*
under `EXT PWR`, *retracted* under `RET` — which the **Full names** button in the
header hides once you no longer need it.

```sh
node tools/build-companion.mjs   # rebuild after editing any note
open companion.html
```

## Conventions

Procedure tables read as **control → action → condition**:

| Control | Action | Condition |
| --- | --- | --- |
| [EXT PWR](controls.md#electrical) pushbutton | set **ON** | if AVAIL |

- **verify** means it should already be in that position — look, do not touch.
- **set** / **adjust** / **press** means act.
- The bold value is the target state.
- `–` in a condition column means unconditional.
