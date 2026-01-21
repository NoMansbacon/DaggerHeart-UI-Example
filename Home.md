# Welcome to the DaggerHeart‑UI Example Vault

This vault is a small demo to show how **DaggerHeart‑UI** can power rich, interactive character sheets in Obsidian.  
It is not a full rules reference—just a toolkit example plus some sample data.

---

## What’s in this vault

- **Example character**
  - `Characters/Marlowe Fairwind`
  - A complete level‑1 Sorcerer (Primal Origin) note wired up with:
    - `badges`, `traits`, `vitals`, `rest`, `damage`
    - `features`, `experiences`, `consumables`
    - `domainpicker` and `equipmentpicker` blocks
  - Frontmatter and block examples match the docs, so you can copy‑paste into your own notes.

- **Domain card compendium**
  - Under `DH_Compendium/abilities/Arcana/…`
  - Under `DH_Compendium/abilities/Midnight/…`
  - Each card is formatted so the **Domain Picker** can find it by folder and tags/frontmatter, and can move cards between **vault** and **loadout** on the Marlowe sheet.

- **Equipment compendium**
  - Under `DH_Compendium/equipment/weapons/Tier 1/…`
  - Under `DH_Compendium/equipment/armor/Tier 1/…`
  - Notes are tagged and structured so the **Equipment Picker** can:
    - Discover weapons and armor by folder/tags
    - Filter by tier
    - Move items between **inventory** and **equipped** on the character note

---

## How to explore

1. **Open Marlowe’s note**

   Go to `Characters/Marlowe Fairwind` and switch to **Reading / Preview** mode to see the full UI:
   - Track HP, Stress, Armor, and Hope.
   - Use Rest & Level Up controls.
   - Spend consumables and see state persist.
   - Use the Domain and Equipment pickers to change Marlowe’s loadout.

2. **Inspect the compendium notes**

   - Open a few cards under `DH_Compendium/abilities/...` and `DH_Compendium/equipment/...`.
   - Look at their YAML and tags to see how DaggerHeart‑UI discovers them.

3. **Copy patterns into your own vault**

   - Duplicate Marlowe’s note and adjust the frontmatter to create new characters.
   - Reuse the same code blocks and change keys/paths as needed.

---

## About this example

This vault is an unofficial fan work built for the Daggerheart roleplaying game.  
It demonstrates how to structure notes so **DaggerHeart‑UI** can provide UI for your own homebrew character sheets while staying within the Daggerheart SRD.