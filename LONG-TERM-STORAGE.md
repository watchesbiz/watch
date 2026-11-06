# Running vs. Stopped: The Long-Term Storage Decision

The most argued question in watch ownership, and the one with the least data behind the arguing. This page separates what is actually known about a resting movement from what is repeated as folklore, then gives a decision rule you can apply to your own collection.

---

## First: a stopped watch is not a damaged watch

A mechanical watch that has run down is in its designed rest state. The mainspring is relaxed, the escapement is static, nothing is under load. Watches sit in dealer display cases for years, stopped, and are sold as new.

So the real question is not "will it survive" — it is **"is there anything that degrades faster while stopped than while running?"**

There are two candidates, and they behave differently.

### Candidate 1: the lubricant

`[COMMON]` Modern synthetic watch oils are specified to stay in place for years. They do not evaporate out of a sealed case, and a watchmaker will tell you that oil loss is usually the result of **migration** — oil creeping away from the pivot under capillary action — not evaporation.

Static does not cause migration on its own; running does, over years, as oil spreads and is thrown. This is the counter-intuitive part of the argument:

> **A stopped movement is not wearing its lubricant out. It is also not redistributing it.**

`[JUDGEMENT]` The practical consequence is that a watch left stopped for **many years** (five-plus, not months) can develop dry pivots at the points where oil crept away and nothing ever re-coated them. A watch that runs — even intermittently — keeps the film moving and re-wetted.

For periods measured in months, this is a non-issue either way. This is why the debate produces so much heat and so little light: both sides are right, about different time horizons.

### Candidate 2: the seals

Gaskets are elastomer. They harden with age and with ozone exposure regardless of whether the watch runs, and they deform to the shape they are held in. A caseback that has been clamped shut for eight years will have flattened gaskets whether the movement inside is running or stopped.

`[JUDGEMENT]` Running does not preserve gaskets. This is a service item, not a storage decision, and it is covered in [WATER-RESISTANCE](WATER-RESISTANCE.md).

---

## The variables that actually decide it

Four, and only one of them is about the mechanism.

| Variable | Why it decides |
|---|---|
| **How long until you wear it again** | Under a month, nothing matters. Over a year, distribution matters |
| **Complications** | Annual/perpetual calendars are the real constraint — resetting them is fiddly, and doing it wrong can damage the mechanism |
| **How many watches** | One watch in a 12-slot winder is absurd; six watches and no winder means constant resetting |
| **Whether you care about convenience or longevity** | These point in opposite directions much less than people think |

---

## The decision rule

`[JUDGEMENT]` Based on the above, with the reasoning shown so you can override it:

| Time until next wear | Recommendation | Why |
|---|---|---|
| Under 2 weeks | Either. Leave it running if it is already on a winder | No degradation either way; convenience decides |
| 2 weeks – 3 months | **Let it stop.** Wind it fully once a month | Keeps the film distributed without continuous wear; saves winder slots |
| 3 – 12 months | **Let it stop**, run it for two days each quarter | Re-wets pivots periodically; avoids a year of continuous rotation |
| Over 12 months | Stop it, and plan a service check before wearing again | Not because stopping damaged it, but because a 1-year-plus layoff is when you find out a gasket failed |
| Perpetual calendar, any duration | **Keep it running** | Reset cost and reset risk dominate everything else |

The last row is the one that genuinely justifies a winder. A perpetual calendar that stops needs its corrector pushers worked in the right order with the right tool, or a trip to a watchmaker. Avoiding that is worth a winder slot; avoiding it for a three-hand Submariner is not.

---

## If you decide to stop it: the correct procedure

1. **Wind it fully first**, then let it run down naturally. Do not stop a partly wound movement by pulling the crown — you are leaving the mainspring under partial tension for months, which is the one state with no upside.
2. **Set the crown to the running position** (pushed fully in). A crown left out is an open path for moisture and dust.
3. **Store it flat or on its side** — either is fine, but be consistent. Rate changes by position; if you always store it dial-up, the first day's rate tells you nothing anomalous.
4. **Record the date and the rate before storage.** Without a baseline you cannot tell, after six months, whether the watch drifted or was already drifting. The [maintenance log template](MAINTENANCE-LOG-TEMPLATE.md) exists for this.
5. **Do not store it in a plastic bag with a desiccant sachet touching the case.** Desiccant in direct contact with a gasket can pull moisture out of the rubber. Silica gel in the same box, not on the watch.

---

## If you decide to keep it running: the two failure modes

A winder does not need to be programmed cleverly to keep a watch healthy — it needs to **not** do two specific things.

**Under-winding.** If the total turns delivered per day are below the movement's minimum, the watch runs at low amplitude. Low amplitude is where rate instability, positional error, and eventually the "it stops overnight" complaint come from. The values live in the [TPD database](https://github.com/watchesbiz/watch-winder-tpd-database).

**Constant full wind.** A watch held permanently at maximum mainspring tension sits against its slipping clutch. That is what the clutch is for, and it is designed for it, but there is no benefit in exceeding the recommended range — the point of a TPD figure is that it is the *minimum sufficient* wind, not a target to beat.

`[JUDGEMENT]` Rest cycles are not required. A commonly repeated claim is that winders must pause for days to "let the movement rest." A movement that is running is doing exactly what it does on your wrist all day. What a rest cycle *does* usefully is reduce total rotation for watches stored long-term — a longevity preference, not a mechanical necessity.

---

## What no storage method fixes

Storage cannot substitute for service. If a watch has gone 12 years without attention, the correct next step is a watchmaker, not a better box. Storage slows environmental damage; it does not reverse wear.

---

## Related

- [STORAGE-ENVIRONMENT](STORAGE-ENVIRONMENT.md) — where to put the box once you have decided
- [SERVICE-INTERVALS](SERVICE-INTERVALS.md) — how to tell when a layoff has crossed into a service need
- [TPD Settings Database](https://github.com/watchesbiz/watch-winder-tpd-database) — the wind values referenced above
- [Single vs. double vs. quad watch winder](https://www.aurawinder.com/guide/single-vs-double-vs-quad-watch-winder/) — how many slots you actually need
