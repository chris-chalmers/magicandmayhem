## Magic and Mayhem Extension guide

# Magic and Mayhem: Community Content Creator’s Guide

Welcome to the **Magic and Mayhem** community! This guide is designed for players and creators who want to expand the game with custom cards, dungeons, and narrative modules. Since the game is hosted on GitHub, we use a structured format to ensure everyone’s homebrew content remains compatible with the core system.

---

## 1. The Core Philosophy: Cooperation & Chaos
Magic and Mayhem is built on **Collaborative Play**. When designing content, keep these rules of thumb in mind:

* **Cooperative Abilities:** Designing a "Lone Wolf" character is discouraged. Instead, focus on abilities that set up teammates for success or require two or more players to trigger.

* **Designing Cooperative "Synergy" Abilities**
The heart of **Magic and Mayhem** is the "Synergy" system. When creating Player cards, try to include at least one ability that interacts with another player's status.

* *Example:* **"Flash Freeze"** — Deals 2 damage. If another player has already applied **[Drenched]** to this target, the target is **[Immobilized]** for 1 turn.

* When designing monsters or bosses, give them a secret weakness that two or more players can exploit in concert. Make it not so easy to discover what that weakness is. Magical item or weapon treasure cards should help players help each other.
*Example:* **"Fire Dragon"** — Takes double damage if another player has already applied **[Frozen]** to this target.

---

## 2. Card Categories & Visual Standards
To maintain a cohesive look across the game, all community-submitted cards should follow the established color coding and dimensions. 


### Card Types
Magic and Mayhem cards come in 5 types. Feel free to make up and add your own! Keep in mind, the "card backs" are provided to print your cards with the same backs as the originals. You'll have to design a new card back image to go with any new card types you come up with!
>
* Player
* Monster
* Boss
* Treasure
* Dungeon
* [Story drive modules may have extra ###"Narrative"### cards for players to read when they land on a specific dungeon card or uncover a feature that needs more explanation]

### Ability Colors
See the chart in Rules_ Magic and Mayhem.pdf 
These are attached to players or treasure cards to specify which are compatible.
* Purple - Strong Magic
* Pink - Adept Magic
* Red - Heavy Weapons
* Orange - Light Weapons
* Green - Epic Skills
* Blue - Agile Skills

### Technical Specifications
* **Physical Size:** 4.25" x 5.5" (Large format).
* **Art Style:** Do whatever you want - seriously!
* **Design Element:** Each card back should use the images in the card-backs folder: Players, Monsters, Bosses Treasure and Dungeon. This is so users can't tell it's one of your special cards when they are in the deck (unless you want them to!). 


---

## 3. Creating a Custom Player
When creating a new player card for Magic and Mayhem, please provide the following details in a stat block on the front of the card: 

> ### [Player Name] 
> ### [Race or Class (elf, dwarf, fighter, rogue)] 
>
> **HP:** - [This specifies the max number of "life tokens" the player can have. It can be modified with power ups or magic items. ].
>
> **MOV - [Ability Name]:** [This specifies how many spaces the player can move per turn].
>
> **DAM - [This specifies how much damage the player does when it attacks] 
>
> **RAN - [This specifies from how far away the player can attack] 
>
> **Type - [This specifies the type of attack (some monsters can be immune or extra sensitive to different types)] 
>
> **Special Ability(ies) - [These are special attacks or actions this player has that are unique to them] 
>
### 3D Models
You can generate 3D printable models for your player using an online service like meshy.ai, Eldritch Foundry, or looking for free models on popular 3D printing websites like thingiverse.com. 

---

## 4. Creating a Custom Monster
When creating a monster card for Magic and Mayhem, please provide the following details in a stat block on the front of the card: 

> ### [Monster Name] 
>
> **HP:** - [This specifies how many "life tokens" the monster has ].
>
> **MOV** - [This specifies how many spaces the monster can move per turn].
>
> **DAM** - [This specifies how much damage the monster does when it attacks] (Monsters could have multiple attacks that are decided by rolling the die).
>
> **RAN** - [This specifies from how far away the monster can attack] 
>
> **Type** - [This specifies the type of attack (some players can be immune or extra sensitive to different types)] 
>
If you are creating a TRAP card, just write what kind of effect the trap has on players that trigger it, and what range its effect has.

---

## 5. Creating a Custom Treasure
Treasure cards are the life blood of the game, they give the players extra abilities to use in cooperation against monsters or the dungeon itself. Describe 

> ### [Monster Name]

---

## 6. GitHub Submission Workflow
Even though this isn't a software project, we use GitHub to track versions of the rulebook and manage community assets.

1.  **Fork the Repo:** Create your own copy of the `magicandmayhem` repository.
2.  **Add Your Content:** * Place text-based content (Rules, Lore, Stat Blocks) in the `/content/homebrew` folder as `.md` files.
    * Place card art and templates in the `/assets/community-cards` folder.
3.  **Submit a Pull Request (PR):**
    * Title your PR with the category (e.g., `[MONSTER] The Cackling Hag`).
    * In the description, explain how you balanced the card against existing Bosses or Players.

