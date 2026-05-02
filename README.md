# Traveler Concierge — Product Plan v3

A comprehensive product design brief for a post-booking travel concierge app concept. Covers feature specification, task flows, UI comps, and system architecture across four travel phases and three booking types.

---

## What This Is

Traveler Concierge is a proactive, learning travel assistant concept that surfaces the right information at exactly the right moment — without the traveler having to ask.

- **Proactive notifications** timed to real data signals, not clocks
- **Apple Live Activity** — Dynamic Island, Lock Screen, Smart Stack, watchOS
- **Expedia Group integration** — concierge module embedded in the OTA trip view
- **Disruption flows** — agent-style ranked options, draft message review before send
- **Multi-traveler system** — role-based permissions, acknowledgment visibility, SMS fallback
- **Personalization layer** — passive and explicit learning, transparent memory view
- **International architecture** — V1 domestic, built to scale without a rebuild

---

## Document Sections

| # | Section | Description |
|---|---------|-------------|
| 00 | Changelog | v1 → v2 → v3 summary |
| 01 | Feature Matrix | 5–7 tasks per booking type per phase |
| 02 | Task Flow | Day-of sequence across all three bookings |
| 03 | Concierge Logic | Timing rules, signals, handoff, privacy |
| 04 | Apple Live Activity | 6-state machine, surface specs |
| 05 | Disruption Flows | Decision tree, option cards, draft message, multi-surface diagram |
| 06 | Multi-Traveler | Permission model, acknowledgment, SMS fallback |
| 07 | Personalization | Passive signals, explicit moments, memory view |
| 08 | International | V1→V3 roadmap, requirements, data schema |
| 09 | Design Principles | Eight governing decisions |
| 10 | Open Questions | 7 resolved · 4 remaining |

---

## Booking Types

- ✈️ **Flight** — Pre-departure through arrival and baggage claim
- 🏨 **Hotel** — 5 days out through check-in and digital room key
- 🚗 **Car Rental** — Insurance briefing through shuttle, pickup, and return

---

## Design System

**Expedia Group light UI:**
- Primary `#1B4CC4` · Yellow `#FFC72C` · Surface `#F5F5F5` · Success `#00763D` · Warning `#D35700`
- Icons: EG-DS outlined style · 1.8pt stroke · rounded terminals

**Apple HIG specs:**
- Dynamic Island compact: 126×37pt · pill radius
- Dynamic Island expanded: ~44pt radius · flows from pill
- Lock Screen widget: 14pt radius · system material · 358pt reference width
- Smart Stack medium: 338×158pt · 22pt radius
- watchOS: Modular complication · large face region

---

## Viewing

Open `index.html` in any modern browser. No build step or dependencies.

Hosted via GitHub Pages at:
`https://[username].github.io/[repository-name]/`

---

## Version History

| Version | Summary |
|---------|---------|
| v1 | Initial concept, feature matrix, task flows, dark-theme comps |
| v2 | Apple LA spec rebuild, Expedia light UI, Expedia-style iconography |
| v3 | Disruption flows, multi-traveler, personalization, international architecture |

---

## License

Licensed under **Creative Commons Attribution-NonCommercial 4.0 International**.

[![CC BY-NC 4.0](https://licensebuttons.net/l/by-nc/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc/4.0/)

Free to share and adapt for non-commercial purposes with attribution. See [LICENSE](LICENSE) for full terms.

---

*Not affiliated with Expedia Group or Apple Inc. Design references are illustrative and non-commercial.*
