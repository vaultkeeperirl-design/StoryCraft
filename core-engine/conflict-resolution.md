# Conflict Resolution

Conflict in StoryCraft arises when characters face opposition that cannot be resolved with a single roll. This includes physical combat, heated debates, chase scenes, or complex negotiations.

## The Turn Structure
Conflict is divided into **Rounds**. A Round represents roughly 6-10 seconds of in-game time.

During a Round, every character takes one **Turn**.
On their Turn, a character can perform:
1.  **One Move Action**
2.  **One Standard Action**
3.  **Any number of Free Actions** (speaking a few words, dropping an item).

### Initiative
At the start of a conflict, determine the turn order.
*   **Formula:** Roll `1d20 + Agility`.
*   **Ties:** Characters with higher Agility go first. If still tied, players decide amongst themselves; GMs decide for NPCs.

*Note: For social conflicts or mental battles, the GM may call for `1d20 + Intellect` or `1d20 + Will` instead.*

---

## Movement & Range
StoryCraft uses abstract ranges to keep combat fluid without improved grid tracking.

### Range Bands
1.  **Close**: Within arm's reach. (Melee combat, whispering).
2.  **Near**: Within a few steps or a short dash. (Throwing a knife, shouting).
3.  **Far**: Within sight but requires significant movement to reach. (Rifle shot, shouting loudly).
4.  **Extreme**: Barely visible. (Sniper range).

### Move Action
*   **Move:** Shift from **Close** to **Near**, or **Near** to **Far** (1 band).
*   **Engage/Disengage:** Move into or out of **Close** range with an enemy.

---

## Actions
The **Standard Action** is the main effort of a character's turn.

### Common Actions
*   **Attack**: Make a combat check against an enemy.
*   **Defend**: Focus on survival. Attacks against you have **Disadvantage** until your next turn.
*   **Dash**: Take a second **Move Action** instead of a Standard Action.
*   **Assist**: Help an ally. They gain **Advantage** on their next check.
*   **Skill Check**: Use a skill (e.g., *Medicine* to stabilize an ally, *Tech* to hack a door, *Intimidation* to demoralize).
*   **Use Item**: Drink a potion, light a torch, or reload a weapon.

---

## Attacking & Defending
Combat follows the standard Core Check formula.

**Attack Roll:** `[Attribute] + [Combat Skill] + 1d20`
**vs.**
**Defense (DC):** `10 + Agility + Combat Skill Rank`

*   **Combat Skill Rank**: The rank of your highest relevant defensive skill (e.g., *Acrobatics* to dodge, *Melee Combat* to parry).
*   **Melee Attacks**: Use **Might** or **Agility** (depending on weapon) vs Target's Defense.
*   **Ranged Attacks**: Use **Agility** vs Target's Defense.

*Note: Defense scales with your skill to keep combat balanced. Armor or Shields may add further bonuses.*

### Damage
If the Attack Roll equals or exceeds the Defense, the attack hits.
1.  **Roll Weapon Damage** (e.g., 1d6, 1d8, 1d10).
2.  **Add Attribute Modifier** (Usually Might for melee, Agility for ranged).
3.  **Subtract from Target's Vitality**.

*   **Critical Hit (Natural 20):** Double the total damage.

---

## Health & Recovery
Characters track two health pools.

### Vitality (Physical Health)
Represents physical toughness, stamina, and structural integrity.
*   **Max Vitality:** `20 + Might`
*   **0 Vitality:** The character is **Incapacitated**. They fall unconscious and may face critical injury or death if attacked further.

### Resolve (Mental Health)
Represents willpower, composure, and social standing.
*   **Max Resolve:** `20 + Will`
*   **0 Resolve:** The character is **Broken**. They may flee, surrender, or suffer a mental breakdown.

### Recovery
*   **Short Rest (1 Hour):** Spend time binding wounds or calming down. Recover `1d8 + Might` (Vitality) or `1d8 + Will` (Resolve). Can only be done once per day per pool.
*   **Long Rest (8 Hours):** Full sleep and food. Restore **all** Vitality and Resolve to maximum.
