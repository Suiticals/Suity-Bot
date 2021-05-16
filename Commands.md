# Idlescape

<details>
  <summary><code>.research</code> - Begin researching from the research tree.</summary>
<br>
  
Aliases: `.play` `.start` `.quest` `.quests` `.tutorial`

The research tree is used to unlock new mechanics, skills, item recipes, and progress through the game. Use the arrow reactions to change your selection and the tick reaction to being researching the current selection or refresh the list.


* `Research time` indicates how long the research will take to complete.
* `Items Required` indicates the required items for the research. These items are taken from the inventory.
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
  
Aliases: `.stat` `.skill` `.skills` `.level` `.level`

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
* `Attack` determines how hard you hit a monster.
* `Defence` determines how hard a monster hits you.
* `Max kills` determines the maximum number of kills you can achieve per hour. Equip items with the `kill cap` stat to raise it. If your attack is high enough to get more kills per hour than your `kill cap`, the number is capped down to your `max kills`

</details>

<details>
  <summary><code>.boosts</code> - .</summary>

Drop down contents
</details>

<details>
  <summary><code>.buffs</code> - .</summary>

Drop down contents
</details> 

`.collection` - 

`.daily` - 

`.disassemble` - 

`.equip` - 

`.unequip` - 

`.shop` - 

`.ge` - 

`.inspect` - 

`.leaderboard` - 

`.use` - 
