---
date: 2024-06-15
linktitle: Rules Primer
title: Rules Primer
weight: 1
---

# Mythras Rules Primer
## Characteristics
Ability scores. Yippie!

#### Strength (Str)
Physical strength.

#### Constitution (Con)
Health and hardiness.

#### Size (Siz)
Measure of mass and height.

#### Dexterity (Dex)
Agility, balance and reflexes.

#### Intelligence (Int)
Cognitive ability.

#### Power (Pow)
Soul, spirit, inner drive AND capacity for magic.

#### Charisma (Cha)
Personality and likeability. 

## Attributes
#### Action Points (Calc Dex + Int)
Every 12 (and fraction thereof) is one action point. 25 is a pretty nice breakpoint.

#### Damage Modifier (Calc Str + Siz)
Every 5 (and fraction thereof) is one die step, with the 'zero line' being at 21-25.

#### Experience Modifier (Calc Cha)
Every 6 (and fraction thereof) is +1 experience modifier, with the 'zero line' being at 7-12.

#### Healing Rate (Calc Con)
Every 6 (and fraction thereof) is 1 healing rate.

#### Height and Weight (Calc Siz)
It's a chart. Just look at it.

#### Hit Points (Calc Con + Siz)
Also don't feel like explaining this one, so just look at it.

#### Initiative Bonus (Avg Dex & Int)
Armor also affects this, but the baseline is the average of your Dex and Int (that is, (Dex + Int) / 2).

#### Luck Points (Calc Pow)
Every 6 (and fraction thereof) is 1 luck point. Restore at the start of every session.

Luck points can be used to:
- Reroll things that affect you. That includes your own rolls and other people's rolls towards you. That also includes _any_ kind of roll, not just d100 ones.
  - Additionally, on d100 rolls you can optionally swap the 10's and 1's place instead of rerolling.
- Gain 1 Action Point when you have zero. Can only be used on defensive actions. Can only be used once in an encounter.
- Turn a Major Wound into a Serious Wound instead, which makes you NOT bleeding all over the floor.

#### Magic Points (Pow)
Equal to your Pow, required to work magic.

#### Movement Rate (6 meters)
How fast you move! Always the same. Though your running / sprinting speed is affected by your Athletics % and your armor. 

## How Shit Works
### Rolling Basics
Usually, it comes down to rolling a skill. So, you roll a d100 and try to get equal to or under the skill's value. That's a **success**. Greater than, that's a **failure.**
- Rolls of 01-05 are always successes.
- Rolls of 96-00 are always failures.
- Rolls of 1/10th (rounded up) the skill's value are _critical_ successes.
- Rolls of 99-00 are fumbles. 

#### Difficulty Grades
Sometimes it's easier (or harder) to do something.
- Automatic -> No need to roll.
- Very Easy -> Double the skill value (200% total).
- Easy -> Add half again the skill value (150% total).
- Standard -> No adjustment (100% total).
- Hard -> Reduce the skill value by 1/3rd (66% total)
- Formidable -> Reduce the skill value by 1/2 (50% total)
- Herculean -> Reduce the skill value by 9/10 (10% total)
- Hopeless -> No attempt can be made. 

#### Augmenting Skills
Are you a little angler? Do you love angling? If you can angle how your knowledge / training in one skill could potentially inform another, you can add 20% of the skill to your check. This is called augmenting. This is also how you aid other people on checks. 

#### Capping Skills
In situations where your knowledge or ability is limited by some other factor, your skill might be capped to the value of a lower applicable skill. The example given in the book is someone's Lore (Strategy and Tactics) being capped by their (lower) Language skill that they have to communicate said tactics in.

#### Contested Rolls
Either Opposed Rolls or Differential Rolls.

##### Opposed
Characters involved roll their relevant skill. The winner is whoever succeeds more, and if the same level of success, whoever rolled higher.

##### Differential
A lot like opposed, except how much you're winning by matters. To explain more clearly:

| Your Result | Opponent Critical                 | Opponent Success                  | Opponent Failure            | Opponent Fumble             |
|-------------|-----------------------------------|-----------------------------------|-----------------------------|-----------------------------|
| Critical    | No benefit                        | You win 1 level of Success        | You win 2 levels of Success | You win 3 levels of Success |
| Success     | Opponent wins 1 level of Success  | No benefit                        | You win 1 level of Success  | You win 2 levels of Success |
| Failure     | Opponent wins 2 levels of Success | Opponent wins 1 level of Success  | No benefit                  | No benefit                  |
| Fumble      | Opponent wins 3 levels of Success | Opponent wins 2 levels of Success | No benefit                  | No benefit                  |

**Important to note**: Failure matched with Failure never results in levels of success for either party, even in the case of a fumble. Otherwise it's a pretty basic sliding scale of Critical as a +2, Success as a +1, Failure as a 0 and Fumbles as a -1. And then just 'subtracting' those values, hence why your critical vs. their fumble is a +3 total (+2 - -1). 

#### Group Rolls
Three different kinds, to suit different needs, speeds and situations.

##### Team Roll
One roll, for the lowest % of the group. Makes the most sense where one failure would result in the whole group failing. 

##### Sorting Roll
One roll, whoever would pass under that roll passes, whoever wouldn't, wouldn't.

##### Proportional
The skill % is the % of people who pass. I.E. 90% Athletics for a squad of highly trained soldiers, then 90% of them succeed. There's no roll here. Makes the most sense for a large group of 'individual' attempts. The example given is said soldiers trying to climb a steep and difficult mountain.

### How The Fuck Do I Read Equipment Entries
Yeah. Me too. By the way, Milieu means what kind of civilization you could see this in. 

#### Armor
They're either Flexible or Rigid. And then break down via construction type. That's pretty self-explanatory. By the way, the armor locations are:
- 1. Left / 2. Right Leg
- 3. Left / 4. Right Arm
- 5. Abdomen
- 6. Chest
- 7. Head

Anyways, terms:
- AP -> Armor Points, the number of armor points granted to that location. Armor points are basically flat DR. Taking big hits is bad!
- ENC -> Encumbrance: Reduces init by total ENC / 5 rounded up, affects running, sprinting, climbing, and swimming speeds. 
- Cost Per Location -> Cost (in SP) to cover a single location with this kind of armor
- Suit ENC -> If you bought the whole 'suit' for every location, the total ENC
- Cost -> The total cost, as above
- Armor Penalty -> The total armor penalty (total ENC / 5 rounded up) for the whole suit

#### Melee Weapons
Either one-handed, shields, or two-handed.

- Damage -> Damage it does if it is successful
- Size -> Used for parrying / countering parries. Big weapons are harder to parry, big things are better are parrying.
- Reach -> Used for keeping distance on an opponent, higher reach makes you harder to engage, and gives you an (initial) advantage
- Combat Effects -> What kind of special combat effects you get
- ENC -> Our good friend encumbrance
- AP/HP -> Armor Points and Hit Points for the item itself
- Traits -> Special things this weapon does, some good, some bad.
- Cost -> Cost in SP

#### Ranged Weapons
They look pretty similar, shocking.

- Damage -> See above.
- Damage Modifier -> Whether your Damage Modifier Attribute applies.
- Force -> A force mod which determines whether you can bypass shields or fuck 'em up.
- Range -> Close / Effective / Long range of the weapon. Long makes you do half damage.
- Load -> Number of turns are required to load / reload the weapon.
- Combat Effects -> See above.
- Impaling Size -> The effective size of the weapon if it succeeds in an impaling attack.
- ENC -> See above.
- AP/HP -> See above.
- Cost -> See above.

### How Do I Kill People
Combat is essentially a series of differential rolls with a lot of 'choices' on what you do with those extra successes you garner. The long and short of it is that:
1. On their turn, the attacker spends an Action Point, rolls their Combat Style, and notes the result.
2. If they want to, the defender spends an Action Point, rolls against their Combat Style and notes the result.
3. The success level of the results are compared as per a Differential Roll.
4. Any difference grants the combatants with the superior roll one or more Special Effects.
5. If the attacker achieved a success or critical, they may roll weapon damage and apply their damage modifier (if any). If applicable, a hit location is determined for the attack.
6. If the defender achieved a success or critical, reduce any damage inflicted according to the Parry rules.

Some things to note here:
- Both sides can succeed and have something happen (like damage, or Special Effects).
  - The differential roll is used to determine Special Effects, but nothing else. Damage happens if the attack is successful, parrying happens if the defending is successful.
- You choose to parry AFTER you see the results of the attack. Choosing not to parry / not being able to parry is an automatic failure on your side.
  - Failure matched with Failure is 0, Failure matched with Critical Failure is also 0, so to get an advantage you have to at least _try_ to parry.
  - Why would you parry a missed attack? To inflict Special Effects on your opponent. 

#### What Do Combat Styles Actually Do?
- Each Combat Style grants access to multiple weapons, depending on the style.
- Each Combat Style gives one or more 'traits' which are situational benefits. 
  - Example: Daredevil: May use Evade to dodge blows in hand-to-hand combat without ending up prone.

#### Initiative, Rounds and Actions
The 'timekeeping' of combat is divided into Combat Rounds (5 seconds) with Turns within those Combat Rounds. The 'countdown' through initiative values is a Cycle. 
- Initiative is rolled at the start of the fight, and usually sticks. There is a way to reroll it (you have to withdraw, and then spend an Action to reassess the situation). Done by rolling a d10 + Initiative Bonus - Armor Penalties. Ties mean acting concurrently.
- Once it cycles down to your turn in initiative, you can take a single Proactive action, likely spending an Action Point.
- Then, you have Reactive actions, you can make any number of reactions per cycle (but only one per triggering threat), as long as you have Action Points to spend.
- Once the end of the cycle is reached, a new cycle begins if combatants still have Action Points to spend. This continues on and on until all Action Points are exhausted, upon which a new 5 second Combat Round begins. 

So, to summarize, you take Proactive actions on your turn, like attacking someone. And you can take defensive, Reactive actions off of your turn. Both of these things cost Action Points, so if you want to attack a lot, you have to give up some Action Points that you would normally use for defense, and likewise, if you're defending yourself from an onslaught, you might find yourself unable to attack. I'm just going to list the Proactive / Reactive actions, mostly for bookkeeping purposes. No descriptions here.
- Proactive: Attack, Brace, Cast Magic, Change Range, Delay, Dither, Hold Magic, Mount, Move, Outmanoeuvre, Ready Weapon, Regain Footing, Struggle
- Reactive: Counter Spell, Evade, Interrupt, Parry
- Free Action: Assess Situation, Drop Weapon, Signal, Speak, Use Luck Point, Ward Location

#### Parrying and Attacking
Parrying is fairly simple. It reduces the damage you _would_ take based on the size of what you're using to parry vs. what's attacking you.
- Parrying an attack with a weapon or shield of equal or greater Size deflects _all_ damage.
- Parrying an attack with a weapon or shield of one Size less deflects _half_ damage.
- Parrying an attack with a weapon or shield of two or more Sizes less fails to deflect any damage (though on a Critical Success you can Enhance Parry).

#### Special Effects
There's a whole bunch of them. There's also a cheatsheet of them, somewhere, so that's probably best. The summary chart kind of helps. Some things to note:
- They're divided into Offensive / Defensive (or both)
- Some can only be done with specific kinds of weapons
- Some can only be done on specifics kinds of rolls (so criticals / fumbles)
  - Easy example is 'Circumvent Parry' which can only be done on Attack Criticals and it... circumvents any parry attempt entirely. Wow!

It's vaguely important to note that critical parries / critical attacks don't do anything special on their own. All the benefit comes from the Special Effects. To emulate a traditional critical against a failed parry, you'd probably pick something like Bypass Armor (ignore AP in location hit) + Maximize Damage (maximize one dice of damage from the weapon). Which is almost certainly inflicting an injury on your opponent. 

#### Weapon Choice
- Two-handed weapons tend to have the best reach and do the most damage, but leave you very vulnerable if you lose access to even one arm.
- Shields are the best defensive weapons, and are able to block ranged weapons.
- Two-weapon fighting gives ~options~, and some security if you lose a weapon. 
- Ranged weapons are safe and can attack from afar, but at the cost of a lower rate of fire.
- Unarmed attacks are a solid backup against an opponent closing in on your weapon's reach, or when you're disarmed.

#### Wounds and Damage
- Minor Wound: Hit location still has hit points left.
- Serious Wound: Hit location has 0 or below hit points.
  - These fuck you up, even if you do pass the related Endurance check.
- Major Wound: Hit location is reduced to a negative # of hit points equal to or greater than it's starting hit points.
  - e.g. A location with 8 hit points that is reduced to -1 from a single hit is a serious wound. If it were to get hit again and go to -8, that's a major wound.
  - These REALLY fuck you up, and you need to make a check vs. dying. And you're also bleeding to death. Don't let this happen to you!
- In summary, taking damage is "fine", since you're not taking any real penalties till a hit location has 0. So, given armor, you can probably take a weak hit to a hit location once.  

#### Reach
A difference of one size in reach means nothing, as far as I'm aware. So all of this applies to 2 or more size steps.
- Categories are Touch, Short, Medium, Long and Very Long, sometimes creatures are even larger.
- Longer has engaged Shorter within their reach:
  - The wielder of the Shorter weapon cannot directly attack the wielder of the longer. They need to close the gap first via Special Effect or specific action.
- Shorter has engaged Longer within their reach:
  - The Longer's weapon size is treated as (difference between weapon reaches) smaller and only deals 1d3+1 damage, due to needed to strike with the other end of the weapon, and guard from an awkward position.
- Closing Distance
  - Close Range Special Effect (requires Special Effect generation)
  - Change Range: Combat action (costing AP), opponent can attempt to counter if they have Action Points
    - Opposed Evade skill test
    - The opponent can instead _attack_, making this instead Combat Style vs. Evade, working like a standard differential roll.
      - No matter what the distance is bridged, even if the attack succeeds. 

#### Hit Locations
As you may (or may not) have noticed, different locations have different hit points and AP. These hit locations are chosen randomly (unless of course, you use the 'Choose Location' Special Effect). That's all. It's a d20 chart, just for the record. 6 of the locations (legs, abdomen, chest, arms) are 15%, head is 10%.