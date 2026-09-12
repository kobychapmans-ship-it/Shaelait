Shae'lait — Slaaneshi Aeldari BattleScribe catalogue (HH1 / Age of Darkness First Edition)
==========================================================================================
Files
-----
- Shaelait_Slaaneshi_Aeldari_HH1.cat: uncompressed BattleScribe catalogue XML.
- Shaelait_Slaaneshi_Aeldari_HH1.catz: ZIP-compressed BattleScribe catalogue containing Shaelait_Slaaneshi_Aeldari_HH1.cat.

Compatibility
-------------
Game system ID: ca571888-56a9-c58e-ddaf-54f4713538bc
Game system revision: 164
BattleScribe data version: 2.03
Designed to sit under the archived BSData Horus Heresy 1st Edition game system, like the existing HH V1 catalogues.
The source defines one bespoke Shae'lait detachment, From Raw and Rips; normal Crusade and Allied force entries are also exposed for standard HH1 use.

Implemented validation/restrictions
-----------------------------------
- From Raw and Rips: HQ 1-6, Elites 0-6, Troops 2-6, Fast Attack 0-6, Heavy Support 0-6, Lord of War 0-1.
- From Raw and Rips requires at least one non-Horror Shae'lait Master HQ through a hidden compulsory category.
- Standard Crusade Detachment: HQ 1-3, Elites 0-4, Troops 2-6, Fast Attack 0-3, Heavy Support 0-3, Lord of War 0-1.
- Standard Allied Detachment: HQ 1, Troops 1-2, Elites/Fast Attack/Heavy Support 0-1.
- Unique named units max 1 per roster.
- Circle Sovereigns max 1 per roster.
- Unit minimum/maximum sizes.
- Required Focus on Focused Shae'lait Exalted and required Perfection Pattern on Perfected Creations.
- Required Circle aspect on Soul Siphons and Dais of a Circle.
- One-per-3 / one-per-6 option groups use BattleScribe repeat modifiers where the roster structure allows exact counting.
- Whole-unit mount options and per-model costs are represented in upgrade groups.
- Daemonette dedicated transports are hidden when the unit exceeds the transport's source model-count eligibility.
- Cultist Platoon special-weapon allowance scales at one per complete ten Cultists in Cultist Squads; Mutant Overlords dynamically raises the Platoon's Mutant Rabble unit cap by one per Exalted Cultists unit in the force.
- Exalted Daemonette Vessels of Perfection, Keeper Coven Mastery upgrades, Soul Siphons and Exalted traits are capped by the number of models in their unit. Soul Siphon Circle aspects are explicit selectable upgrades.
- Daemonette Alluress Psyker upgrades are capped by the number of Alluresses actually selected.
- Weapon and wargear selections expose their associated special-rule links as well as their profiles.
- Warlord is limited to one per roster; Beelzebothor and Horror entries that cannot be Warlord do not receive the Warlord option.
- From Raw and Rips has a required zero-point Detachment Rules activation entry. From the Lab and From the Palace free traits key off that selection and are hidden outside the custom detachment. From the Palace allows exactly one free trait total, only from a tier in which that unit bought a trait, and blocks duplicate traits.
- The one Lord of War slot and the normal 25% Age of Darkness Lord of War points cap are encoded on the Lord of War force-category link; the detachment also displays an explicit reminder rule.

Rule and profile coverage
-------------------------
- Core Shae'lait faction rules and Path of Excess are linked to affected units.
- All 18 Broken Perfection traits are selectable with rules text.
- Both complete custom psychic disciplines are included and linked to Psyker units.
- All six Shae'lait Warlord Traits are selectable; Ezyrithn and Aeos use their fixed traits.
- Custom weapon rules (Swiftstrike, Languid Strike, Tendril Strikes, Neural Leak, Impaled, Bladestorm) are included.
- All roster weapon profiles, transport/chariot profiles, Soul Siphon aspects and bespoke wargear effects are included.
- Verified core HH1 USRs link directly to the archived Horus Heresy 1.0 game-system rule IDs. Source-specific Shae'lait rules and any unverified generic rules remain local reference rules rather than guessing at external IDs.

Revision 3 usability fixes
--------------------------
- Focused Shae'lait Exalted mount/chariot choices are nested on the actual character model so they appear in the character configuration panel.
- Chariot Cavalcade Seeker, Hellflayer and Exalted Seeker chariots have mandatory crew-weapon allocations matching their rider counts.
- Each crew weapon can be Lash of Despair or Excruciator pike; choosing it exposes the complete weapon profile(s) and linked special rules.

Source gaps / implementation assumptions
----------------------------------------
The completed roster states that some characters may buy weapons at their 'listed armoury cost', but the completed armoury table does not actually print prices for several generic Moderate/Higher weapons. To make the BattleScribe list buildable instead of leaving zero-cost high-end weapons, this implementation uses conservative data-only costs for those missing values. They are an implementation layer, not source-derived canon:
- Lash of Despair 15; Excruciator Pike 15.
- Higher weapons before the Exalted's source-mandated +20 premium: Soulrazor 20, Ecstasy Whip 15, Mirrorblades 20, Pain Harvester 25, Void-kiss 25, Blissfang 30.
- The Focused Exalted therefore pays 40/35/40/45/45/50 for those Higher exchanges respectively.
The original listed values are retained wherever the roster gives a price directly.

The source supplies a Favoured Prefect statline but no sentence specifying how the unit obtains one. The catalogue presents one free optional Favoured Prefect marker so the provided profile is usable; it does not change the unit's base points.

The roster prints the Dais of a Circle as a Dedicated Transport but does not identify a unit that may select it as a dedicated transport. It is therefore fully defined as a catalogue entry/profile and is selectable through the Chariot Cavalcade upgrade where the roster explicitly permits it, but no additional unit has been given invented Dais transport eligibility.

Install
-------
Import the .catz into the same BattleScribe data repository/install that contains The Horus Heresy.gst from the HH1 repository. The catalogue identifies itself as '(HH V1) Shae'lait — Slaaneshi Aeldari' and should appear as a force choice under that game system.


Revision 2 changes
==================
- Chariot Cavalcade now displays Daemonette / Exalted Daemonette rider profiles for each chariot type.
- Deterministic characteristic bonuses from selected mounts, Soul Siphons, Broken Perfection patterns, Transfigured of the Sixth Circle, Apprentice Tools, Mirrorblade pair and Vessel of Perfection are reflected in displayed profiles where the owning model/unit can be represented unambiguously. Temporary in-game bonuses remain rules text.
- Cultist Platoon Rabble is reformatted as a platoon parent with separately configurable nested Command Squad, Cultist Squads and Mutant Rabble units. Each Cultist Squad controls its own additional bodies and special weapons.
- Leader-only upgrades are hidden until the corresponding Alluress, Slave Tender or Herdmaster is selected.
