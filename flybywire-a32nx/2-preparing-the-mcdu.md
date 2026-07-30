# 2 · Preparing the MCDU

Walk the MCDU pages in order. Most of it comes in from the SimBrief OFP, so the
work is mainly verifying what arrived.

Flight plan and charts: [SimBrief](https://www.simbrief.com/) ·
[ChartFox](http://chartfox.org/)

## Import the SimBrief OFP

| Page | Action |
| --- | --- |
| [MCDU MENU / ATSU / AOC MENU](controls.md#atsu-and-aoc) | select **INIT/PRES** → **INIT DATA REQ** |

## INIT A

| Field | Action |
| --- | --- |
| [INIT REQUEST](controls.md#init) | select to auto-populate |
| [CRZ FL](controls.md#init) | verify set |

## F-PLN

| Field | Action |
| --- | --- |
| [DEPARTURE](controls.md#flight-plan) | set as planned |
| [ARRIVAL](controls.md#flight-plan) | set as planned |
| Discontinuities | clear if any |
| [ND mode](controls.md#efis-control-panel) selector | verify **PLAN** to walk the route |

## INIT B / FUEL PRED

| Field | Action |
| --- | --- |
| [BLOCK](controls.md#init) | set as loaded |
| [ZFW / ZFWCG](controls.md#init) | select to auto-populate |

## PERF — Takeoff

Calculate the numbers in **flyPad / Performance / Takeoff** first, then enter
them:

| Field | Action | Condition |
| --- | --- | --- |
| [T.O SHIFT](controls.md#performance) | set | as required — intersection departure |
| [V1](controls.md#performance) | set | – |
| [VR](controls.md#performance) | set | – |
| [V2](controls.md#performance) | set | – |
| [FLEX TO TEMP](controls.md#performance) | set | – |
| [THR RED/ACC](controls.md#performance) | set or verify | – |
| [ENG OUT ACC](controls.md#performance) | set or verify | as required |
| [FLAPS/THS](controls.md#performance) | set | takeoff flaps and trim reminder |

## Pages with no action

**DATA** · **SEC F-PLN** · **RAD NAV** — RAD NAV should already be populated
from the flight plan, so verify rather than type.

## Clearance

Request IFR clearance from Delivery — see
[ATC Communications › Clearance Delivery](../vatsim/atc-communications.md#1--clearance-delivery-startup).

> [!NOTE]
> flyPad: perform the **BEFORE START** checklist.

---

Previous: [1 · Starting the Aircraft](1-starting-the-aircraft.md) ·
Next: [3 · Engine Start and Taxi](3-engine-start-and-taxi.md) ·
[Index](README.md)
