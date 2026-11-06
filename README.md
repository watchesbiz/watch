# Mechanical Watch Care & Storage Reference

Practical reference for people who own automatic watches and have to decide **where the watch lives, how often it runs, and when it goes to a watchmaker.** Written as decision frameworks and checkable ranges rather than general advice.

This repository is the companion to [**watch-winder-tpd-database**](https://github.com/watchesbiz/watch-winder-tpd-database), and the two cover different questions:

| | This repository | TPD database |
|---|---|---|
| Question answered | *How should the watch be stored and maintained?* | *How many turns per day does the movement need?* |
| Covers | Environment, magnetism diagnosis, service intervals, water resistance, straps, long-term storage | Caliber-level TPD values, winding direction, hairspring material |
| Format | Decision frameworks, checklists, copyable templates | Data tables (reference → caliber → TPD → direction) |

If you arrived looking for TPD numbers, go to the other repository first. If you already know your movement's settings and now need to decide whether the watch should sit in a winder, a drawer, or a safe — start here.

---

## 📁 Repository contents

| File | What's in it | Focus |
|---|---|---|
| [`STORAGE-ENVIRONMENT.md`](STORAGE-ENVIRONMENT.md) | Temperature, humidity, light, vibration — the four variables that actually degrade a stored watch, with workable ranges | Environment |
| [`LONG-TERM-STORAGE.md`](LONG-TERM-STORAGE.md) | Running vs. stopped: what actually happens to oils and seals over months, and how to choose | Decision |
| [`MAGNETISM.md`](MAGNETISM.md) | Diagnosing magnetisation at home, the household sources that matter, demagnetising procedure, what ISO 764 does and doesn't promise | Diagnosis |
| [`SERVICE-INTERVALS.md`](SERVICE-INTERVALS.md) | Why "every 5 years" is a myth in both directions, how to read the watch instead of the calendar | Maintenance |
| [`WATER-RESISTANCE.md`](WATER-RESISTANCE.md) | What the depth ratings mean once gaskets age, and why a 100 m watch fails in a shower | Specs |
| [`STRAPS-AND-BRACELETS.md`](STRAPS-AND-BRACELETS.md) | Leather, steel, rubber and fabric storage — where each one fails | Materials |
| [`TRAVEL-AND-CASES.md`](TRAVEL-AND-CASES.md) | Travel rolls, hard cases, safes and the heat problem inside a closed box | Transport |
| [`INSURANCE-AND-RECORDS.md`](INSURANCE-AND-RECORDS.md) | What insurers ask for, what to photograph, how to keep a defensible record | Records |
| [`MAINTENANCE-LOG-TEMPLATE.md`](MAINTENANCE-LOG-TEMPLATE.md) | A copyable service log — the single highest-value habit for resale and for diagnosis | Template |
| [`GLOSSARY.md`](GLOSSARY.md) | Only the terms that change a decision. Not a dictionary | Reference |
| [`index.html`](index.html) | Landing page served by GitHub Pages | Entry point |

---

## 🧭 The four questions this repository answers

Most ownership problems reduce to one of these. Pick the one that matches your situation.

**1. "Should it run or should it stop?"**
A stopped watch is not a damaged watch. A running watch is not automatically a healthy one. What matters is duration and how the lubricant behaves at low amplitude — covered in [LONG-TERM-STORAGE](LONG-TERM-STORAGE.md).

**2. "Is it broken or is it magnetised?"**
A mechanical watch that jumps to +15–60 minutes per day is usually magnetised, not worn out. This is a 10-minute check, not a service — [MAGNETISM](MAGNETISM.md).

**3. "When does it need a service?"**
Not on a fixed calendar. On symptoms: amplitude, rate stability across positions, and how the crown feels. [SERVICE-INTERVALS](SERVICE-INTERVALS.md) explains what to measure.

**4. "Where can I safely put it?"**
Heat and humidity do more damage to stored watches than movement does. A safe, a bathroom drawer, and a windowsill are three very different environments — [STORAGE-ENVIRONMENT](STORAGE-ENVIRONMENT.md).

---

## 🧾 Data conventions used here

Where a number appears, it is tagged by source strength so you can judge how much to trust it:

| Tag | Meaning |
|---|---|
| `[STD]` | Defined by a published standard (ISO 764, ISO 22810, etc.) |
| `[COMMON]` | Widely repeated industry range; directionally right, not a spec |
| `[SYMPTOM]` | Observed behaviour you can verify yourself with a phone or a timegrapher |
| `[JUDGEMENT]` | An editorial call, stated as such, with the reasoning shown |

Nothing in this repository is a manufacturer spec sheet, and no service price is quoted — those vary too much by market and by watchmaker to state responsibly.

---

## 🔗 Related resources

- [**Watch Winder TPD Settings Database**](https://github.com/watchesbiz/watch-winder-tpd-database) — the companion repository: TPD values and winding direction per caliber
- [TPD settings database (searchable)](https://www.aurawinder.com/watch-winder-tpd-settings-database/) — the same data in filterable form
- [Are watch winders safe? Anti-magnetisation and motor isolation](https://www.aurawinder.com/guide/are-watch-winders-safe/) — the hardware-side counterpart to [MAGNETISM](MAGNETISM.md)
- [How to clean and maintain a watch winder](https://www.aurawinder.com/guide/how-to-clean-and-maintain-a-watch-winder/) — maintaining the device rather than the watch
- [Full guide index](https://www.aurawinder.com/guide/) — capacity, rotation direction, quiet motors, materials

---

## 🤝 Contributing

Corrections are welcome, especially from watchmakers. If a range here is wrong, open an issue with the movement or material involved and, ideally, a manufacturer document or a measured reading. Specificity beats volume — a single verified correction is worth more than ten additions.

## ⚖️ License

MIT — free to use for personal research and for building storage products that respect the movement.

---

Maintained by [Aurawinder](https://www.aurawinder.com), which builds quiet, high-torque watch winders and publishes reference material for collectors.
