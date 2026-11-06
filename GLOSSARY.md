# Glossary: Only the Terms That Change a Decision

Not a dictionary. Every entry here is included because **misunderstanding it leads to a specific, expensive mistake** — and each entry names that mistake.

---

## Measurement

| Term | What it is | Why it matters |
|---|---|---|
| **Amplitude** | How far the balance wheel swings, in degrees, typically 270–315° for a healthy movement | The earliest wear indicator. Fails before rate does. Below 240° means book a service even if it still keeps time — see [SERVICE-INTERVALS](SERVICE-INTERVALS.md) |
| **Rate** | Daily deviation in seconds per day (s/d) | What everyone checks and the least informative number on its own. Meaningless without position and amplitude |
| **Beat error** | Asymmetry between the tick and the tock, in milliseconds | Above ~1.0 ms, the escapement is out of adjustment. Affects starting reliability more than rate |
| **Positional variation** | The spread in rate between dial-up, crown-down, etc. | A large spread means regulation or wear. A small spread with a huge error means magnetism — see [MAGNETISM](MAGNETISM.md) |
| **Timegrapher** | The instrument (or app) that measures the above from the movement's sound | A phone app with the mic against the caseback is adequate. Guessing without one is not diagnosis |
| **Lift angle** | A movement-specific constant the timegrapher needs to compute amplitude correctly | Wrong lift angle means a wrong amplitude reading. Most apps let you set it, and most people never do |

---

## Winding

| Term | What it is | Why it matters |
|---|---|---|
| **TPD** | Turns per day — total rotations delivered to the winding mechanism in 24 h | The core setting. Too low and the watch runs at low amplitude; see the [TPD database](https://github.com/watchesbiz/watch-winder-tpd-database) |
| **Uni-directional winding** | The rotor winds in one direction only (e.g. Patek Cal. 240) | A bi-directional programme wastes half its turns. This is the single most common misconfiguration |
| **Bi-directional winding** | Winding in both rotation directions | Not "better" — just different. Correct for most modern movements, wrong for uni-directional ones |
| **Power reserve** | Hours the watch runs from full wind | If measured reserve is below 80% of rated, the mainspring is set or there is drag — a service signal |
| **Slipping clutch** | The mechanism that prevents over-winding | Why over-winding does not break a watch — but is also why there is no benefit in exceeding the TPD range |
| **Hacking seconds** | The seconds hand stops when the crown is pulled | Needed for precise time setting. Its absence on some movements is normal, not a fault |

---

## Calendars — where mistakes get expensive

| Term | What it is | Why it matters |
|---|---|---|
| **Quick-set date** | Date changes rapidly by turning the crown in one position | Safe to use, except in a forbidden window |
| **No-quick-set date** | Date change requires winding the hands forward through 24 hours | Common on vintage. There is no shortcut, and forcing the crown damages the mechanism |
| **Forbidden window** | Roughly 9 pm to 3 am, when date-change gears are engaged | **Changing the date in this window can strip teeth.** The most common self-inflicted damage in watch ownership |
| **Annual calendar** | Corrects for month length, needs one adjustment a year (February) | Cheaper than perpetual, but still needs correct setting |
| **Perpetual calendar** | Accounts for leap years indefinitely | The strongest argument for keeping a watch on a winder — resetting one requires the corrector pushers, in order, with a tool. Get it wrong and it is a repair, not a reset |
| **Triple-date** | Day, date and month in three windows | More correctors, more reset complexity, more to get wrong |

---

## Water and sealing

| Term | What it is | Why it matters |
|---|---|---|
| **Gasket / O-ring** | The elastomer seal at caseback, crown, crystal, pushers | The whole of water resistance. Hardens with age; must be replaced whenever the case is opened — see [WATER-RESISTANCE](WATER-RESISTANCE.md) |
| **ATM** | Atmospheres, 1 ATM ≈ 10 m of static water pressure | The rating is static and factory-new. A 5 ATM watch is not a swimming watch once the gaskets are old |
| **ISO 22810** | Standard for general water-resistant watches | The baseline marking. Says nothing about diving |
| **ISO 6425** | Diving watch standard | The only standard permitting "DIVER'S" on the dial. A 200 m watch without it is not a dive instrument |
| **Helium escape valve** | A one-way valve for saturation divers living in a pressurised habitat | Irrelevant unless you are saturation diving. Having one does not make a watch more waterproof for swimming |
| **Pressure test** | Bench verification of the seal, in bar or ATM | Cheap, fast, and the only way to know. "Passed" without a number is not a result |

---

## Magnetism

| Term | What it is | Why it matters |
|---|---|---|
| **Magnetisation** | Residual magnetism in steel components, usually the hairspring | Makes the watch gain massively and uniformly. Fixable in under a minute — see [MAGNETISM](MAGNETISM.md) |
| **ISO 764** | "Magnetic resistant" standard: 4,800 A/m (≈60 gauss) | A modest field. Protects against proximity, not against a MagSafe puck pressed to the case. Not permanent immunity |
| **Silicon hairspring** | Hairspring etched from silicon rather than drawn alloy | Far more resistant to magnetism and to temperature. Not immune — surrounding steel parts can still be affected |
| **Demagnetiser** | A coil device that randomises residual magnetism | Cheap and effective, if you withdraw the watch before switching it off |

---

## Case, crystal, service

| Term | What it is | Why it matters |
|---|---|---|
| **Overhaul / full service** | Complete disassembly, clean, re-lubricate, re-seal, regulate | What "service" should mean. If a quote does not include this, ask what it does include |
| **Regulation** | Adjusting rate via the regulator | Does **not** add oil. Regulating a dry movement hides the problem and accelerates wear |
| **Sapphire / mineral / acrylic crystal** | Case glass types, hardest to softest | Sapphire resists scratches but chips; acrylic scratches easily and can be polished back; mineral is between and cheap to replace |
| **Incabloc / shock resistance** | Spring-loaded jewel settings that absorb impact | Standard on modern movements. Does not protect against a hard knock to the case flank |
| **PVD / gold plating** | Thin surface coating | Microns thick. Wears through and cannot be economically repaired — store without rubbing |
| **Box and papers** | Original packaging and warranty documentation | A real resale premium and the easiest proof of ownership. The box is an asset, not packaging — see [INSURANCE-AND-RECORDS](INSURANCE-AND-RECORDS.md) |

---

## Related

- [SERVICE-INTERVALS](SERVICE-INTERVALS.md) — amplitude, rate and the six thresholds
- [MAGNETISM](MAGNETISM.md) — diagnosis and demagnetising
- [WATER-RESISTANCE](WATER-RESISTANCE.md) — gasket life and pressure testing
- [TPD database](https://github.com/watchesbiz/watch-winder-tpd-database) — per-caliber TPD and direction values
