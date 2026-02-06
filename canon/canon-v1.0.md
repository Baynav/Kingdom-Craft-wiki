# Kingdom Server Design Canon v1.0

> ⚠️ **Authoritative Document**
> This document defines the official rules and systems of the Kingdom Server.
> If any summary, dev log, or explanation conflicts with this document,
> **this document takes precedence**.
> Future changes may only be additive (v1.x).

---

## 1. Core Vision

A **persistent, no-reset, world-based kingdom simulation** built inside Minecraft, where:
  * Players control **kingdoms**, not individual progression
  * NPC systems perform the majority of economic and structural labor
  * The world is preserved long-term (no strip-mined wastelands)
  * History, wars, alliances, and achievements permanently shape the world

Solo players and small groups must remain viable at all stages of play.

**Design Principle**
> The world itself is the content.

---

## 2. Player & Kingdom Structure

* A kingdom is the primary player identity
* Individual progression is secondary to kingdom progression

Each kingdom includes:
  * One permanent **Capital**
  * Optional **Outposts** (temporary, non-capital)
  * An NPC workforce
  * An abstracted resource economy

### Capitals

Capitals:
  * Cannot be destroyed or deleted
  * Cannot permanently change ownership
  * May suffer **temporary functional damage** during war

Capital damage may cause:
  * Reduced production
  * Increased upkeep
  * Disabled advanced functions

All damage is **recoverable**.

**Design Principle**
> Capitals preserve identity while allowing meaningful conflict.

---

## 3. Roles & Anti-Abuse Design

* Kingdom roles exist (e.g., Ruler, General, Steward)
* Roles provide bonuses tied to responsibility

Anti-abuse rules:

* Stacking multiple roles has **diminishing returns**
* Prevents single-player or zerg dominance
* Encourages specialization and cooperation

Solo and duo players receive **efficiency normalization**, not penalties.

---

## 4. Economy Foundations

### Resource Philosophy

* Resources are **tiered**:
  * Tier I: Wood, Stone, Food
  * Tier II+: Realm resources (Nether, End)
    
* NPC systems are the **primary economic engine**
* Manual gathering is:
  * Allowed
  * Intentionally inefficient
  * Used early-game, expeditions, or opportunistic discovery

### Upkeep

* All kingdoms incur upkeep costs
* Upkeep scales **linearly**
* Expansion scales **exponentially**
* NPC income is sufficient for baseline stability
* Growth requires active decisions

**Design Principle**
> Stability is passive; growth is intentional.

---

## 5. World Integrity Rules (Anti-Grief)

The world must remain visually and mechanically intact.

### Terrain & Block Abuse

* Large-scale mining is inefficient
* Lava, TNT, piston, and redstone abuse is restricted via:
  * Decay systems
  * Area protections
  * System-only structural damage

Players cannot permanently delete terrain or structures through warfare.

**Design Principle**
> World change is system-driven, not player-driven.

---

## 6. NPC Kingdoms & Degradation

### Inactivity & Degradation

Inactive kingdoms:
  * Do not disappear
  * Enter a **Dormant State**
  * Are occupied by NPC forces

Dormant kingdoms:
  * Remain contestable
  * Preserve identity and history

### Reclamation

* Returning owners may reclaim their kingdom
  * Reclamation is:
    * Structured
    * Recoverable
    * Never instant

---

## 7. PvE & Raid Windows

* NPC kingdoms follow the same raid window rules as player kingdoms
* No off-hour punishment

NPC behavior prioritizes:
  * Active players in-region
  * Trade pressure
  * Opportunistic raids

Coalitions may defend offline allies, reinforcing trust and diplomacy.

---

## 8. War System (High-Level)

### War Declaration

All wars:

* Have an attacker and defender
* Require declared objectives
* Never delete a kingdom or capital

### Combat Execution

* NPC armies perform:
  * Structural damage
  * Objective pressure
    
* Players act as:
  * Commanders
  * Force multipliers

Wars occur only during **scheduled siege windows**.

### Rewards Philosophy

* Objective-based
* Recoverable loss
* Defenders always gain something for successful defense

---

## 9. Scouting & Intelligence

### Scouting Levels

**Level I Intelligence**
  * Allows war declaration
  * Broad objectives only
  *  High uncertainty

**Level II Intelligence**
  * Allows targeted objectives
  * Reduced randomness
  * Preparation bonuses
  
**Level III Intelligence**
  * Tactical execution advantages
  * No exclusive reward unlocks

### Counter-Intel

Defenders may:
  * Detect scouts
  * Feed false information
  * Gain temporary buffs if infiltration is exposed

**Design Principle**
> Scouting is interactive, not a UI screen.

---

## 10. Realms & Resource Acquisition

### Realm Definition

* A **Realm** is a dimension (Overworld, Nether, End)

### World Gates

* Server-placed
* Finite
* Provide initial realm access
* Must be contested via Control Claims

### Kingdom Gates

* Built **inside the capital**
* One per realm (Nether / End)
* Convenience only
* Do not generate new access
* Cannot replace World Gates

### Expeditions

**NPC Expeditions**:

* Primary method of bulk resource acquisition
* May only launch through Kingdom Gates

**Manual Expeditions**:

* Allowed
* Riskier
* Supplementary

---

## 11. Control Claims & Outposts

### Outposts

Outposts are:
* Temporary influence structures
* Non-capital
* Vulnerable by design

Used to:
* Project power
* Contest World Gates
* Stage limited conflicts

### Control Claims

* Establish influence over:
  * World Gates
  * Wonders
  * Strategic zones
* Contested through limited-scope conflicts
* Smaller than kingdom wars
* 
---

## 12. World Wonders

### Structure

* Single persistent world
* Tiered Wonders:
  * Tier I: Regional
  * Tier II: Global (Cooperative)
  * Tier III: Singular Mythic

### Rules

World Wonders:
  * Cannot be sealed
  * Cannot be permanently owned
  * Are always contestable
  * *Permanently alter world systems*

**All contributors and outcomes are recorded in world history.
Central spawn may display historical achievements.**

---

## 13. Persistence & History
  * *No resets*
  * *No seasonal wipes*
  * *All wars, wonders, rulers, and outcomes are recorded*

**Design Principle**
> The world remembers everything.

---

## 14. Resource Visualization & Storage Model

### Abstract Storage (Source of Truth)
  * Used for upkeep, upgrades, and war rewards
  * Not limited by physical container space

### Visual Containers (Representation Layer)
  * *Resource buildings include visual containers (e.g., chests)*
  * *Containers display representative physical items*
  * *Containers act as **controlled withdrawal interfaces***

### Withdrawal Behavior
  * *Removing items subtracts from abstract storage*
  * *Containers do not refill if storage is empty*
  * *Full containers do **not** stop production*

### Storage Upgrades
Upgrades may increase:
  * *Maximum abstract storage*
  * *Visual container capacity*
  * *Visual refill rate*

### War Interaction With Resources
  * *War rewards affect abstract storage only*
  * *Containers provide minor tactical interaction*
  * *Post-war visuals reflect economic outcomes*

---

**END OF CANON v1.0**

