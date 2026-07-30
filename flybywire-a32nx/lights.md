# Lights by Phase

The same handful of light switches gets touched in almost every phase, so they
live here as one matrix instead of being repeated across seven procedure pages.
The procedure pages still say *when* to act; this page is the single source of
truth for *what state*.

`–` means no action in that phase (the previous state carries over).

## Exterior

| Light | Prep | Start and Taxi | Takeoff | Initial Climb | Above 10,000 ft | Descent 10,000 ft | Final (G/S green) | After Landing | Shutdown |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [NAV & LOGO](controls.md#exterior-lighting) | **ON** | – | ON | – | – | – | – | – | **OFF** |
| [STROBE](controls.md#exterior-lighting) | **AUTO** | – | **ON** | – | – | – | – | **AUTO** | – |
| [BEACON](controls.md#exterior-lighting) | **OFF** | **ON** | – | – | – | – | – | – | **OFF** |
| [WING](controls.md#exterior-lighting) | – | – | **OFF** | – | – | – | – | – | – |
| [RWY TURN OFF](controls.md#exterior-lighting) | – | **ON** | ON | **OFF** | – | – | **ON** | ON | **OFF** |
| [NOSE](controls.md#exterior-lighting) | – | **TAXI** | **T.O.** | **OFF** | – | – | **T.O.** | **TAXI** | **OFF** |
| [LAND L & R](controls.md#exterior-lighting) | – | – | **ON** | – | **OFF** | **ON** | – | **OFF** | – |

- **BEACON** goes ON at start clearance, before pushback or engine start, and OFF
  once the engines have spooled down at the gate.
- **STROBE** sits at AUTO on the ground and goes **ON** for line-up. Select ON
  whenever you cross a runway, taxiing out or in.
- **NOSE** and **RWY TURN OFF** go OFF in the climb at S speed, at the same time
  the ground spoilers are disarmed.

## Interior and Signs

| Control | Prep | Above 10,000 ft | Descent 10,000 ft | Shutdown |
| --- | --- | --- | --- | --- |
| [SEAT BELTS](controls.md#signs) | **ON** | as required | **ON** | **OFF** |
| [NO SMOKING](controls.md#signs) | **AUTO** | – | – | **OFF** |
| [EMER EXIT LT](controls.md#signs) | **ARM** | – | – | **OFF** |
| [OVHD INTEG LT](controls.md#interior-lighting) | **BRT** | – | – | – |
| [INTEG LT](controls.md#displays) | **BRT** | – | – | – |

## Notes

- **NAV & LOGO and RWY TURN OFF appear twice.** Both are set before the takeoff
  block and set again in it. If nothing changed them in between, the second
  entry is a verify rather than an action — the SOP repeats them the same way.
- **WING is only ever set OFF** (at takeoff) and never turned on, so that entry
  is effectively a verify.
- **NO SMOKING sits at AUTO**, which ties it to landing gear position. Leaving
  either sign off AUTO prevents the emergency batteries from charging.
