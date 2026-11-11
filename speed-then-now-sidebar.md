# Speed, Then and Now — Verified Sidebar

*All facts below checked against live data on pre-flight: F1 API records, Met Museum collection API, and web search.*

## Driver Spotlight: Lewis Hamilton ✅ VERIFIED

From the F1 driver record (`getDriverInfo` for `driverId: hamilton`):
- `permanentNumber`: "44" — **correct**
- `nationality`: "British" — **correct**
- `dateOfBirth`: "1985-01-07" — **correct**
- Bonus: driver code `HAM`, givenName: Lewis, familyName: Hamilton.

All three draft details hold up. Safe to print as-is.

## Is Anything Live in F1 Right Now? ⚠️ Nothing live at this moment

- `getCurrentSessionStatus` returned an **empty object `{}`** — no active F1 session right now.
- `getLiveCarData` returned an **empty array `[]`** — no car telemetry feed is streaming.

**Plain answer for the newsletter:** as of this check, there is no live F1 session or live car data. Don't promise readers a "live laps" box this weekend; by Saturday morning it may well be different. Link to the F1 live timing page instead.

## Art Corner: Chariots Were the First Speed Machines ✅

Primary pick — from the Metropolitan Museum of Art collection (Object ID **247020**, department: Greek and Roman Art; medium: bronze, ivory; credit line: Rogers Fund, 1903):
- **Title:** Bronze chariot inlaid with ivory
- **Maker/Culture:** Etruscan (ca. 500 BC, 6th century BC; found at Monteleone di Spoleto)
- **Date:** ca. 500 BC (Archaic period, Etruscan)
- The Met's tags include Achilles and Thetis — this was a ceremonial war chariot.
- Image: https://images.metmuseum.org/CRDImages/gr/original/DP137936.jpg

Also verified in the Met's collection (Object ID 250666, Greek and Roman Art, Rogers Fund 1918, medium: bronze, silver, copper; tags: Medusa):
- **Title:** Bronze ornament from a chariot pole

*Sidebar line:* "Speed had a silhouette long before it had an engine note. The Met's Etruscan bronze chariot — inlaid with ivory, ca. 500 BC — sat in Monteleone di Spoleto nearly 2,500 years before Hamilton's #44."

## History: It All Started at Silverstone in 1950 ✅ VERIFIED

Web search confirms: the inaugural Formula One World Championship race was run on **13 May 1950 at Silverstone** — the **1950 British Grand Prix** — won by **Nino Farina** in an Alfa Romeo, in front of King George VI. Your draft line is accurate on both the year and the circuit.

## Verdict Box

| Draft line | Status |
|---|---|
| Hamilton: No. 44, British, born 1985-01-07 | ✅ Verified against F1 data |
| Live F1 session + telemetry right now | ⚠️ Nothing live — empty status + empty telemetry |
| Chariots were the first speed machines | ✅ Met Museum: Etruscan bronze chariot, ca. 500 BC (Obj. 247020; also Obj. 250666) |
| It all started at Silverstone in 1950 | ✅ Verified: 13 May 1950, Silverstone GP, Farina won |

*Speed, then and now — fact-checked before send. No guesswork here.*