# Extraction Schema — DC Prime Earth Canon Audit

## Purpose

This schema defines the categories of information to extract from the session document (`Salvage System x DC.md`) for canon auditing. Each extracted element will be classified by **origin** (canonical DC, fabricated/embellished, or original creation) and tagged with a **confidence level** based on available sourcing.

---

## Confidence Tags

| Tag | Meaning |
|-----|---------|
| `[DC-CANON]` | Verified against published DC source material with citation |
| `[DC-CONFIDENT]` | Strongly matches known DC canon; specific citation not yet confirmed |
| `[DC-PROBABLE]` | Likely canonical but details may be embellished or combined from multiple sources |
| `[DC-UNCERTAIN]` | Cannot confirm from published sources; may be AI-generated extrapolation |
| `[FABRICATED]` | Not found in any DC source; appears to be session-generated content |
| `[OC]` | Original character/concept belonging to the player's creative work |

---

## Category 1: Characters

### Fields per entry:
- **Name**: Character name as used in session
- **DC Canon Name** (if different): Official name in published comics
- **Origin**: `DC-CANON` / `FABRICATED` / `OC`
- **Role in Session**: How they appear or are referenced
- **Canon Status**: Alive/dead/status in the era the session targets
- **Canon Accuracy Notes**: Does their portrayal match published characterization?
- **First Appearance (DC)**: Comic issue citation if canonical
- **Discrepancies**: Any deviations from published canon

### Subcategories:
- **1A: DC Canonical Characters** — Characters from published DC Comics (e.g., Zatanna, Batman, Constantine, Wonder Woman, Amanda Waller, Crazy Jane)
- **1B: Fabricated Characters** — Characters presented as if canonical but not found in DC sources
- **1C: Original Characters (OC)** — The Salvage System and its members (Steve, Stephanie, Serenity, Jason, Sarah, The Chemist, The Cook, The Metal Guy, The Negotiator, The Security Guy, unnamed/fluid members)

---

## Category 2: Locations

### Fields per entry:
- **Name**: Location as referenced in session
- **DC Canon Name** (if different)
- **Origin**: `DC-CANON` / `FABRICATED` / `OC`
- **Canon Accuracy Notes**: Does the location's description match published canon?
- **First Appearance (DC)**: Comic issue citation if canonical

### Subcategories:
- **2A: DC Canonical Locations** — Published locations (e.g., House of Mystery, Gotham City, Shadowcrest, Themyscira, Atlantis, Kahndaq)
- **2B: Fabricated Locations** — Locations presented as canonical but not found in sources
- **2C: OC-Associated Locations** — The System's apartment/workshop, the safe, workstations

---

## Category 3: Organizations & Teams

### Fields per entry:
- **Name**: Organization as referenced in session
- **Origin**: `DC-CANON` / `FABRICATED` / `OC`
- **Role in Session**: How they function in the narrative
- **Canon Roster** (if applicable): Published membership vs. session-stated membership
- **Canon Accuracy Notes**: Does the organization's portrayal match published canon?
- **Discrepancies**: Roster errors, jurisdictional misattributions, etc.

### Subcategories:
- **3A: DC Canonical Organizations** — Justice League, Justice League Dark, ARGUS, DEO, STAR Labs, Doom Patrol, Green Lantern Corps, Parliament of Trees, Lords of Order/Chaos, Court of Owls
- **3B: Fabricated Organizations** — Organizations presented as canonical but not found in sources
- **3C: OC Organizations** — The Salvage System as an internal community/governance structure

---

## Category 4: Events & Plot Points

### Fields per entry:
- **Event Name**: As referenced in session
- **Type**: `DC-CANON-EVENT` / `SESSION-EVENT` / `REFERENCED-EVENT`
- **Canon Citation**: Published source if canonical event
- **Session Usage**: How the event is used or referenced in the narrative
- **Accuracy Notes**: Does the session's reference match published event details?
- **Debris/Salvage Connection**: What materials the session claims came from this event

### Subcategories:
- **4A: DC Canonical Events Referenced** — Court of Owls, Night of the Owls, Death of the Family, Zero Year, Forever Evil, Batman Eternal, Endgame, Dark Nights: Metal, Blackest Night, Absolute Power, etc.
- **4B: Session-Original Plot Events** — Zatanna's meet-and-greet encounter, the extraction to House of Mystery, JLD briefing, Waller's surveillance, etc.
- **4C: Timeline Markers** — Indicators of when the session takes place relative to DC continuity

---

## Category 5: Relationships & Dynamics

### Fields per entry:
- **Parties**: Who is involved
- **Type**: Interpersonal / Factional / Institutional / Adversarial
- **Canon Basis**: Is this relationship published in DC canon?
- **Session Portrayal**: How the relationship functions in the narrative
- **Accuracy Notes**: Does it match published relationship dynamics?

### Subcategories:
- **5A: Canon Character Relationships** — Zatanna-Constantine (romantic history), Batman-Oracle, Batman-Alfred, Constantine-Papa Midnite, Wonder Woman-JLD leadership, Waller-ARGUS, Silas Stone-Cyborg
- **5B: OC-Canon Relationships** — Salvage System's relationship with Zatanna, Batman, Constantine, Wonder Woman (via briefing), Waller (adversarial)
- **5C: Factional Dynamics** — JLD vs. ARGUS, JLD vs. main Justice League jurisdictional boundaries, magical community politics (traditional houses vs. syncretic practice)

---

## Category 6: Powers, Abilities & Limitations

### Fields per entry:
- **Character/Entity**: Who possesses the ability
- **Ability**: Description as presented in session
- **Canon Basis**: Published source for the ability
- **Accuracy Notes**: Does the session's portrayal match published power levels/mechanics?
- **Discrepancies**: Over/under-powered, wrong mechanics, fabricated abilities

### Subcategories:
- **6A: DC Character Powers** — Zatanna's logomancy/backwards speech, Homo Magi heritage, non-verbal casting; Constantine's street magic/trickery; Batman's detective/tech abilities; Wonder Woman's capabilities
- **6B: OC Powers & Capabilities** — Salvage System's hybrid tech-magic integration, co-fronting cognitive advantages, fluid plurality as structural advantage, Element X discovery
- **6C: Power Scaling & Interactions** — How the session positions OC capabilities relative to DC characters (sub-street-level combat, world-destabilizing knowledge asymmetry)

---

## Category 7: Items, Tech & Artifacts

### Fields per entry:
- **Item Name**: As referenced in session
- **Origin**: `DC-CANON` / `FABRICATED` / `OC`
- **Canon Description**: Published properties if canonical
- **Session Description**: How the session describes the item
- **Accuracy Notes**: Does the session's description match published canon?

### Subcategories:
- **7A: DC Canonical Items** — Batarangs (Mark VII), Mother Box fragments, Kryptonian sunstone, Nth Metal, Dionesium, Joker toxin, Talon reanimation compounds, Scarecrow fear toxin, Apokoliptian tech, Reach biotech, Crime Syndicate antimatter tech, Element X
- **7B: OC-Created Items** — The hybrid phone, the motorcycle, the van, the dozen supersuits, the grimoire, the zettelkasten, the magitech security system (cameras), the magitech entertainment system, magitech smart home assistant, the safe, proof-of-concept weapons, the USB database
- **7C: Fabricated Items** — Items presented as canonical DC artifacts but not found in published sources

---

## Category 8: Universe Rules & Systems

### Fields per entry:
- **Rule/System**: Description of the rule as presented
- **Domain**: Magic / Cosmic / Technological / Political / Institutional
- **Canon Basis**: Published source establishing this rule
- **Session Application**: How the session applies or extends the rule
- **Accuracy Notes**: Match to published canon, extrapolation vs. fabrication

### Subcategories:
- **8A: Magic Systems** — Logomancy (Zatanna), sympathetic magic, divine magic (Olympian, Ishtarite, Christian), ambient magic, backwards-speech mechanics, blood-cost structures, cross-tradition integration rules, ward mechanics, dimensional pocket creation, teleportion spells
- **8B: Cosmic Systems** — Element X as universal substrate, World Forge, Speed Force, Emotional Spectrum, Dark Multiverse
- **8C: Technological Systems** — Apokoliptian-Kryptonian interface problems, Mother Box computational paradigms, sunstone crystallography, Reach biotech integration
- **8D: Political & Institutional Systems** — JLD jurisdiction vs. main Justice League, ARGUS authority and mandate, magical community traditional houses/lineages, government meta-human surveillance frameworks, Homo Magi designation
- **8E: Forensic & Detection Systems** — Magical signature scanning, DNA/fingerprint forensics, scrying, counter-surveillance methods

---

## Category 9: Player Declarations

These are statements the player explicitly made about their OC that define the narrative canon of the Salvage System, regardless of what the GM-Claude generated.

### Fields per entry:
- **Declaration**: The specific statement
- **Session Location**: Where in the document it appears
- **Type**: `WORLDBUILDING` / `CHARACTER-TRAIT` / `BOUNDARY` / `CORRECTION` / `PLOT-DIRECTION`
- **Impact**: How this declaration shaped the narrative

### Key player declarations to extract:
- The System is non-traumagenic endogenous DID
- Plurality is a structural advantage, not a disorder
- All members front and create their own work
- Steve is the designated external speaker for singlets
- Stephanie is trans lesbian, dislikes church
- System members have fluid boundaries (not discrete compartments)
- Co-fronting occurs (multiple members simultaneously present)
- New members emerge from combinations (e.g., Sarah = Christianity + femininity)
- Some members have no names, just roles (The Chemist)
- Salvage was necessity, not preference — civilian without connections
- Research focus, not weaponization
- Art/personal cultural work is private, technical research is shareable
- The System thinks about security because they live in Gotham
- Willing to destroy dangerous stockpile rather than let Waller have it
- "Different people being passed the phone" as the analogy for switching
- Do not ask by name — ask by topic/expertise
- Plan to renegotiate arrangement after immediate crisis

---

## Category 10: Unresolved Threads & Hooks

### Fields per entry:
- **Thread**: Description of the unresolved element
- **Type**: `PLOT-HOOK` / `CANON-QUESTION` / `CHARACTER-ARC` / `WORLDBUILDING-GAP`
- **Status**: Open / Partially Addressed / Implied
- **Dependencies**: What needs to be resolved for this thread to progress

### Known threads to extract:
- Waller's response to JLD extraction
- Wonder Woman's 6-hour briefing (never shown in session)
- Papa Midnite's role in managing magical community reaction
- Traditional magical houses' response to syncretic practice
- What the System considers "advanced" work (never revealed)
- Batman's full analysis of the database
- Constantine's examination of the grimoire in detail
- Oracle's ongoing intelligence gathering on ARGUS
- Long-term protection arrangement renegotiation
- The System's research capabilities with proper materials (untested)
- Whether Waller already knows about the DID
- Distribution of the dangerous materials from the safe
- The Salvage System's actual upper limits of capability

---

## Extraction Process

### Phase 1: Raw Extraction
Go through the session document sequentially and log every element into the appropriate category above. Tag each with origin and confidence level.

### Phase 2: Canon Compliance Check
Cross-reference every `DC-CANON` tagged element against published sources. Verify accuracy. Flag discrepancies.

### Phase 3: Resolution
For each discrepancy, determine: Is it a GM-Claude error? A deliberate creative choice? An ambiguity that could be resolved either way?

### Phase 4: Context Files
Produce clean reference documents that separate verified canon from session-specific creative content, so the player knows exactly what is real DC lore and what was generated for the story.
