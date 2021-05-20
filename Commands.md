# Idlescape

<details>
  <summary><code>.research</code> - Begin researching from the research tree.</summary>
<br>
  
Aliases: `.play` `.start` `.quest` `.quests` `.tutorial`

The research tree is used to unlock new mechanics, skills, item recipes, and progress through the game. Use the arrow reactions to change your selection and the tick reaction to being researching the current selection or refresh the list.


* **Research time** indicates how long the research will take to complete.
* **Items Required** indicates the required items for the research. These items are taken from the inventory.
* Research level requirements cannot be boosted for.
* Once started, the research cannot be cancelled.
* A list of researches can be found using `.inspect researches`
* To view the details of a specific research use `.inspect research <name of research>`
</details>

<details>
  <summary><code>.idle</code> - View your idle progress.</summary>
<br>
  
Aliases: `.gather` `.gathering`

Skills are split into idle and production skills. Mining, Woodcutting, Fishing, Combat, Hunter, and Thieving are all idle skills. 

* Use `.idle <name of item>` to assign a resource to gather using the idle skills.
* Once an item has been assigned to be idled, you will continue to idle. It should be noted that the assigned item will never be unassigned so continuing to assign the same item has no effect.
* Your maximum idle time is the amount of time elapsed since your last idlescape command. If you have not issued an idlescape command for longer than your maximum idle time, all progress will be paused until a command is issued. The idle timer is reset every time you issue an idlescape command. Your maximum idle time is based on your current Agility level including boosts. 
* Ingredients are displayed under the recipe being idled. The number indicates the amount you have in your inventory. Idling will pause if you do not have enough ingredients to continue.
* The items per hour displays the number of time you will complete that recipe in the next hour. If you do not have enough ingredients for the next hour, or boosts will expire, the display will be updated to the reduced number.
</details>

<details>
  <summary><code>.production</code> - View the progress of orders and actions.</summary>
<br>
  
Aliases: `.prod` `.prog` `.progress`

Skills are split into idle and production skills. Smithing, Cooking, Crafting, Herblore, Farming, Runecrafting, Enchanting, Fletching, Invention, Firemaking, and Construction are all production skills. 

* Your maximum idle time is the amount of time elapsed since your last idlescape command. If you have not issued an idlescape command for longer than your maximum idle time, all progress will be paused until a command is issued. The idle timer is reset every time you issue an idlescape command. Your maximum idle time is based on your current Agility level including boosts.
* Use the arrow reactions to change pages if your list of orders spans multiple pages.
* Use `.make [quantity] <name of item>` to begin an order. If `quantity` is unspecified it will default to 1.
* Use `.stop <name of item>` to cancel an order. You will be refunded all ingredients.
* If using a skill speed boost, the time remaining on the order will reduce at a faster rate.
</details>

<details>
  <summary><code>.stop</code> - Stop an order currently in production.</summary>
<br>
  
Aliases: `.end` `.abort`

* Use `.stop <name of item>` to cancel an order.
* You will be refunded all remaining ingredients of a cancelled order.
</details>

<details>
  <summary><code>.inventory</code> - View your inventory.</summary>
<br>
  
Aliases: `.inv` `.bag` `.bank` `.items` `.backpack`

Your inventory is where all of your items are placed. 

* Use `.inventory <search>` to search through your inventory. Use `|` to separate multiple searches. For example: `.inventory ore|bar|logs` will search for `ore`, `bar` and `logs`
* Use the arrow reactions to change pages if your inventory spans multiple pages.

</details>

<details>
  <summary><code>.stats</code> - View your Idlescape stats.</summary>
<br>
  
Aliases: `.stat` `.skill` `.skills` `.level` `.levels`

Experience in skills is gained through actions. As you gain experience your skills will level up, unlocking more content.

The columns are in the following order:

| Skill name | Level | Experience
-|-|-

</details>

<details>
  <summary><code>.worn</code> - View your worn equipment.</summary>
<br>
  
Aliases: `.gear` `.equipment`

Equipping items

* Use `.equip <item name>` to equip an item.
* Use `.unequip <slot name>` to unequip an item. Unequip uses the slot name rather than the item name since items can be in multiple slots.
* Equipping an item to a slot already in use will unequip the currently worn item.
* Some items use multiple slots. For example: two-handed weapons use both the mainhand and offhand slots.
* **Attack** determines how hard you hit a monster.
* **Defence** determines how hard a monster hits you.
* **Max kills** determines the maximum number of kills you can achieve per hour. Equip items with the **kill cap** stat to raise it. If your **attack** is high enough to get more kills per hour than your **kill cap**, the number is capped down to your **max kills**.

</details>
  
<details>
  <summary><code>.equip</code> - Equip a piece of equipment.</summary>
<br>
  
Aliases: `.wear` `.wield` `.weild`

* Use `.equip <item name>` to equip an item.
* Use `.unequip <slot name>` to unequip an item. Unequip uses the slot name rather than the item name since items can be in multiple slots.
* Equipping an item to a slot already in use will unequip the currently worn item.
* Some items use multiple slots. For example: two-handed weapons use both the mainhand and offhand slots.

</details>
  
<details>
  <summary><code>.unequip</code> - Unequip a piece of equipment in a worn slot.</summary>
<br>
  
Aliases: `.unwear` `.unwield` `.unweild`

* Use `.unequip <slot name>` to unequip an item. Unequip uses the slot name rather than the item name since items can be in multiple slots.
* Use `.equip <item name>` to equip an item.
* `slot name` can either be the name of the slot or its alias.

Slot name|Aliases|Unlock
-|-|-
Head|`helm`|
Cape|`back`|
Neck|`amulet` `ammy`|
Mainhand|`mh` `weapon`|
Offhand|`oh` `shield`|
Body|`top` `torso`|
Legs|`bottom` `bottoms`|
Hands|`glove` `gloves`|
Feet|`boot` `boots`|
Ring||
Ammo||
Consumable 1|`food 1` `consumable1` `c1`|
Consumable 2|`food 2` `consumable2` `c2`|Level 30 Combat
Consumable 3|`food 3` `consumable3` `c3`|Level 70 Combat
Pickaxe||Completion of the 'Pickaxes' research
Hatchet||Completion of the 'Hatchets' research
Fishing rod||Completion of the 'Fishing rods' research

  </details>

<details>
  <summary><code>.boosts</code> - View your active boosts.</summary>
<br>

</details>
  
<details>
  <summary><code>.buffs</code> - View your active buff sources.</summary>
<br>


</details>  
  
<details>
  <summary><code>.daily</code> - Claim any unlocked dailies.</summary>
<br>

* This command can be used once every 24 hours.
* **Daily streak** is the number of consecutive days you have claimed dailies.
* Streaks are reset if you have not claimed a daily for more than 36 hours.
* Each daily streak grants a 25% increase in daily rewards.
* Streaks are capped at 8 days, for a maximum of 200% increase in daily rewards.

Daily|Base Quantity|Unlock
-|-|-
Coins|500|
Bucket of sand|80|Completion of the 'Hand in the Sand' research

</details>
  
<details>
  <summary><code>.use</code> - Use an item.</summary>
<br>

Syntax: `.use [quantity] <item>`

* If `quantity` is unspecified it will default to 1.
* Items that can be used are denoted by the 'use' icon in your `.inventory`
* **Add buff** items, such as potions, grant you boosts for a certain duration. You can view your active buffs using `.buffs`
* **Lootbox** items, such as seedboxes, can be opened using this command. You can view the drop table of the lootbox using `.inspect item <name of item>`
 
</details>

<details>
  <summary><code>.inspect</code> - Inspect an item, monster, component, or research.</summary>
<br>

  `.inspect collection <name of collection>` - Inspect a collection. Identical to `.collection view`

  `.inspect component <name of item>` - View a list of items that disassemble into a component.

  `.inspect item <name of item>` - Inspect an item.

  `.inspect monster <name of monster>` - Inspect a monster.

  `.inspect research <name of research>` - Inspect a research.

  `.inspect researches` - View a list of all researches.

  `.inspect skill <name of skill>` - Inspect a skill to view the unlock table.

</details>
  
<details>
  <summary><code>.</code> - </summary>
<br>
  
Aliases:

</details>

`.collection` - 

`.disassemble` - 

`.shop` - 

`.ge` - 

`.inspect` - 

`.leaderboard` - 
