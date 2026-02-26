# RuleSmith's Journal

## 2024-05-22 - Standardizing Skill Progression
**Learning:** Foundational skill systems require predictable math to ensure scalability across settings.
**Action:** Implemented a fixed-rank system (Untrained +0, Trained +2, Expert +4, Master +6). This ensures that characters from a Fantasy setting (e.g., Swordsmanship) and a Sci-Fi setting (e.g., Piloting) operate on the same mathematical scale, allowing for cross-genre compatibility without breaking the Difficulty Class (DC) curve.

## 2024-05-23 - Standardizing Difficulty Classes
**Learning:** Without a unified DC scale, module compatibility breaks down (e.g., a "Hard" lock in Sci-Fi might be trivial compared to a "Hard" enchantment in Fantasy).
**Action:** Codified a universal DC ladder (5/10/15/20/25/30) and Circumstantial Modifiers (Advantage/Disadvantage) to replace arbitrary flat bonuses. This ensures that a DC 15 check has the same statistical weight regardless of the setting.

## 2024-05-24 - Standardizing Attribute Generation
**Learning:** The Core Engine listed Attributes (Might, Agility, Intellect, Will) but lacked a method to generate them, leaving a critical gap in character creation.
**Action:** Implemented three standard Attribute Arrays (Standard, Specialist, Versatile) and an Attribute Scale (-1 to +5). This ensures all characters start with a mathematically balanced baseline while allowing for different playstyles (well-rounded vs. focused), eliminating the randomness of rolling for stats which can break the DC curve.

## 2024-05-25 - Streamlining Conflict Resolution
**Learning:** Opposed rolls for every attack slow down combat significantly and create variable Difficulty Classes that are hard to predict.
**Action:** Implemented a Static Defense system (10 + Agility + Modifiers) to replace opposed rolls for standard attacks. This aligns combat with the Core Check formula (Roll vs DC), speeds up gameplay, and allows players to roll all attacks, keeping the focus on their actions.

## 2024-05-26 - Standardizing Defense Scaling
**Learning:** Fixed Defense (10 + Agility) fails to scale with high-level Attack bonuses (Attribute + Skill), leading to a near 100% hit rate for Expert/Master characters.
**Action:** Revised Defense formula to `10 + Agility + Combat Skill Rank`. This ensures that defensive capabilities grow alongside offensive power, maintaining a balanced success rate across all tiers of play.

## 2024-05-27 - Developing the Fantasy Magic System
**Learning:** Complex spell slot tables or point buy systems create barrier to entry and slow down play.
**Action:** Implemented a simplified **Mana System** (Pool = Level + Attribute). This scales naturally with character progression without requiring lookup tables. Spells cost their Level in Mana, making the math instant (Rank 1 = 1 Mana).

## 2024-05-27 - Modular Skill Integration
**Learning:** Genre-specific mechanics often require skills not present in the Core Engine (e.g., Magic, Hacking).
**Action:** Established the pattern that Setting Plug-ins can inject new skills (e.g., **Arcana**, **Faith**) into the skill list. Also reinforced using existing Core Skills (e.g., **Insight** for Elven senses) to avoid skill bloat where possible.
