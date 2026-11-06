# Magnetisation: Diagnosis and Fix

A mechanical watch that suddenly gains 15–60 minutes per day is **magnetised, not broken** — roughly nine times out of ten, and it is the cheapest fault in horology to fix. Most people send the watch for a full service before checking.

This page covers how to diagnose it at home in ten minutes, which household objects actually cause it, and what demagnetising can and cannot repair.

The hardware side — how a winder's motor is isolated so it does not cause this in the first place — is covered separately in [Are watch winders safe?](https://www.aurawinder.com/guide/are-watch-winders-safe/)

---

## The signature symptom

| Behaviour | Magnetised | Needs service |
|---|---|---|
| Rate error | Large and sudden: +15 to +60 min/day, occasionally more | Progressive drift over months |
| Positional variation | **Small** — the error is similar in all positions | Large — dial up vs. crown down differ by 30 s+ |
| Amplitude | Often normal or high | Falling |
| Onset | Overnight, after a specific event | Gradual |
| Regulation | Watchmaker can regulate it back, and it drifts again | Regulating holds |

The tell is the **combination**: a huge rate error that is *consistent across positions* points to the hairspring coils sticking to each other, which shortens the effective spring and speeds the watch up uniformly. Wear produces the opposite pattern.

---

## Diagnosing it yourself

You need no tools beyond a smartphone.

**Step 1 — the compass test.**
Open a compass app (the built-in iOS/Android one works) and bring the watch close, slowly, from 30 cm to touching. A magnetised watch will deflect the needle noticeably — a few degrees is ambiguous, a hard swing is not. Test each side: dial, caseback, both flanks. Magnetisation is often local, one part of the case.

This test is crude and can produce false negatives on weakly magnetised watches, but a positive is reliable.

**Step 2 — the rate test.**
Use any timegrapher app or a real timegrapher if you have one. Measure in at least two positions, dial up and crown down, and compare:

- Both positions fast by roughly the same large amount → magnetisation, strongly suspected
- One position fast, the other acceptable → positional error, this is regulation territory
- Both slow → not magnetisation (magnetisation almost always gains)

**Step 3 — the 24-hour confirm.**
Set the watch to a known reference, leave it dial-up and undisturbed for 24 hours away from electronics, then measure. Then measure again for a second 24 hours in the same position. A magnetised watch will be consistently, massively fast. A disturbed watch may settle.

---

## What actually magnetises a watch

Field strength falls off with the square of distance, so most "dangerous" objects are harmless at 20 cm and damaging at 2 cm.

| Source | Risk | Notes |
|---|---|---|
| **MagSafe charger / magnetic phone mount** | High | The strongest common household magnet. A watch left on a charging pad overnight is the single most common cause now |
| **Laptop lid magnets** | Moderate | Closing a watch in a laptop, or leaving it on the palm rest |
| **Tablet keyboard covers** | Moderate | The magnet array runs the full width |
| **Speakers and headphones** | Moderate | Subwoofers and studio monitors more than small earbuds |
| **Cabinet door catches, magnetic knife strips** | Moderate | Wall-mounted, at exactly hand height |
| **Electric motors nearby** | Low at distance | Hairdryers, blenders, vacuum cleaners — an issue only in prolonged proximity |
| **Fridge magnets** | Low | Too weak in practice, unless the magnet is a rare-earth type |
| **Airport / shop security gates** | Very low | Widely feared, rarely confirmed — the field is strong but the exposure is a second |
| **MRI rooms** | Catastrophic | Never. Not a storage question |

`[STD]` **ISO 764** defines a "magnetic resistant" watch as one that keeps time within tolerance after exposure to a **4,800 A/m** direct-current field (roughly 60 gauss). That is a modest field — it protects against everyday proximity, not against a MagSafe puck pressed against the case. ISO 764 is not a permanent immunity, and it says nothing about what happens after the watch has already been exposed.

Silicon hairsprings (Omega Si14, Patek Spiromax, and the silicon escapements now common across brands) are far more resistant than alloy hairsprings, but "far more" is not "immune" — the steel components around them can still retain magnetism and disturb rate. See the anti-magnetic notes in the [TPD database](https://github.com/watchesbiz/watch-winder-tpd-database) for per-caliber hairspring material.

---

## Demagnetising: procedure

A demagnetiser is a cheap device (a coil in a box) and the procedure takes under a minute. If you own more than one mechanical watch, buying one is rational — it will pay for itself the first time.

1. **Remove the watch from any winder** and take it off any metal surface. Metal nearby distorts the field.
2. **Turn the demagnetiser on** and hold the watch about 5 cm above the plate.
3. **Move the watch slowly through the field**, dial facing the plate, for a few seconds.
4. **Withdraw it slowly to at least 30 cm before turning the device off.** This step is the one people skip, and skipping it is why demagnetising "doesn't work" — switching off while the watch is still close can re-magnetise it.
5. **Turn the watch over and repeat**, caseback facing the plate.
6. **Re-test with the compass**, then measure the rate over 24 hours.

If the rate is now normal, done. If it improved but is still fast, repeat once. If two attempts make no difference at all, magnetism was probably not the cause — move to the service diagnostic in [SERVICE-INTERVALS](SERVICE-INTERVALS.md).

### What demagnetising cannot fix

| Situation | Why demag fails |
|---|---|
| Hairspring coils are physically touching and deformed | Needs a watchmaker to separate and reshape |
| The watch was magnetised repeatedly over years and the spring is now permanently set | Replacement, not demagnetising |
| The rate is wrong in *one* position only | That is regulation, not magnetism |
| A small steel part (a screw, a regulator index) is now magnetised and attracting swarf | Needs opening and cleaning |

`[JUDGEMENT]` One demagnetising attempt, maybe two. After that, the probability that you are treating the wrong fault is higher than the probability that a third pass will work.

---

## Prevention, ranked by effectiveness

1. **Distance.** Nothing magnetic within 20 cm of where the watch lives. This one rule covers most of the table above.
2. **Do not charge a phone next to the watch.** MagSafe pads and magnetic stands are the dominant modern cause.
3. **Check your winder.** A poorly shielded motor or a magnetic clasp on the door is a slow, continuous exposure — worse than a one-off event because it repeats every cycle. Test with a compass held inside the empty winder while it runs.
4. **Do not store watches in a laptop bag.** Lid magnets plus daily transport.
5. **Annual compass check.** Ten seconds, catches a change in your storage arrangement before it costs you a service.

---

## Related

- [Are watch winders safe?](https://www.aurawinder.com/guide/are-watch-winders-safe/) — motor isolation and shielding on the device side
- [STORAGE-ENVIRONMENT](STORAGE-ENVIRONMENT.md) — the other environmental hazards, ranked
- [SERVICE-INTERVALS](SERVICE-INTERVALS.md) — what to do when demagnetising does not fix the rate
- [TPD database: hairspring and anti-magnetic notes](https://github.com/watchesbiz/watch-winder-tpd-database) — per-caliber hairspring material
