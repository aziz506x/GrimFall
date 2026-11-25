# GrimFall

**A Warhammer Fantasy strategy game in the style of Travian, built to play solo and offline on your phone.**

GrimFall is a single-player game that runs in your web browser. You build up cities, recruit an army, raid, besiege and conquer settlements, research new technology, and lead the war against Chaos. The game is set in the Old World of Warhammer Fantasy and borrows ideas from *Travian* and *Total War: Warhammer III*.

The whole game is one self-contained HTML file (`index.html`). It needs no server, no account and no internet connection once loaded, and it saves your progress on your device automatically.

---

## Contents

1. [Getting started](#getting-started)
2. [The four factions](#the-four-factions)
3. [Building your cities](#building-your-cities)
4. [Gold and the treasury](#gold-and-the-treasury)
5. [Armies and combat](#armies-and-combat)
6. [Sieges](#sieges)
7. [Lords, items and exploration](#lords-items-and-exploration)
8. [The world map](#the-world-map)
9. [Defending your realm](#defending-your-realm)
10. [Growing your realm](#growing-your-realm)
11. [Agents](#agents)
12. [The War Against Chaos](#the-war-against-chaos)
13. [The endgame](#the-endgame)
14. [Settings, difficulty and game speed](#settings-difficulty-and-game-speed)
15. [Saving your progress](#saving-your-progress)

---

## Getting started

- **Play online:** open the game's GitHub Pages link (once Pages is turned on for this repository).
- **Play offline:** download `index.html` and open it in any modern browser.
- **On iPhone:** open the game in Safari, tap **Share**, then **Add to Home Screen**. It then launches full-screen like an app.

At the start you choose a faction, a difficulty and a name for your capital. Every new campaign gets a new, randomly generated version of the Old World.

The game keeps running while you're away. When you come back, a **"While you were away"** summary shows everything that happened in the meantime.

---

## The four factions

| Faction | Bonus | Legendary Lord | Special mechanic |
|---|---|---|---|
| 🦅 **The Empire** | Construction is 10% faster | Karl Franz (+10% army offense) | **Imperial Decrees**: issue edicts such as +20% production, −25% construction time, −30% training time or +20% garrison defense |
| 🦢 **High Elves** | +15% resource production, +10% wall defense | Tyrion (+5% offense, +15% defense for the city he guards) | **Influence**: spend it on tribute from Lothern, court intrigue, Swordmaster reinforcements, a defensive Shield of Saphery, envoys that make a neutral faction your ally, or healing for your Lords |
| 👹 **Greenskins** | +20% plunder, 25% faster recruitment | Grimgor Ironhide (+2% offense per victory in a row, up to +20%) | **WAAAGH!**: battles build up Fightiness, and at 100 you can call a WAAAGH! for +25% army offense |
| ⚒️ **Dwarfs** | +15% defense for all troops, slightly stronger walls, +20% Iron and Clay. Troops march slowly | Thorgrim Grudgebearer (+10% defense for the city he guards, +1% offense per settled grudge, up to +15%) | **Book of Grudges** and the **Lost Holds** (see below) |

Each faction has its own units, building art, city names, research tree, agents, Regiments of Renown and road to the Chaos Wastes.

**No mirror match:** your own faction never appears as an AI rival. The other playable factions do appear as AI powers: play the Empire and the AI High Elves hold Ulthuan; play the High Elves and the AI Empire holds Altdorf; play the Dwarfs and both are present. Greenskins are the exception, because the Rival Greenskins (other Orc tribes) remain as an AI faction.

### ⚒️ Dwarfs: the Book of Grudges
- **Units:** Dwarf Warriors, Quarrellers, Thunderers, Ironbreakers, Hammerers, Gyrocopters and Gyrobombers (from the **Gyrocopter Hangar**), Grudge Throwers, the Thunderbarge war machine, and Prospectors for new cities. Dwarfs field no monsters, so their top unit is a machine.
- **Grudges:** every raid, siege or holding taken from you is written in the Book against that faction.
- **Settling a grudge:** beat that faction in battle, whether you win an attack on them or defeat their raid or siege. Each settled grudge gives ⭐ 200 Renown, gold, and +1% offense to Thorgrim (up to +15%).
- **Festering:** grudges left open for more than 3 game days fester, costing −2% production each (up to −10%).
- **The Lost Holds:** Karak Varn, Mount Gunbad and Karak Ungor start in Greenskin hands. Claim one with a Lord to reclaim it. A reclaimed hold gets **+25% Iron and Clay**, ⭐ 1,000 Renown, and settles an ancient grudge.
- Open the Book from the 📕 panel on the City screen.

---

## Building your cities

### Resources
There are four resources: 🪵 **Timber**, 🧱 **Clay**, ⛏️ **Iron** and 🌾 **Crop**. Each city has 18 resource fields that you upgrade up to level 10.

Crop feeds your people and your army. If a city's net Crop production drops to zero or below, recruitment stops. If its Crop store runs out, troops starve.

### Viewing your city
- **City:** an isometric picture of your city. Buildings change their look at levels 5, 10 and 15.
- **Fields:** a picture of your farmland. Fields change their look at levels 3, 6 and 9.
- **List:** a compact view of your resource fields, grouped by type, and your buildings.

A green dot marks every field and building you can upgrade right now.

### Construction
You start with 3 builder slots per city. Keep level 5 adds a fourth and level 10 adds a fifth.

- **Build plan:** queue upgrades you can't afford yet. Each one starts automatically once the resources and a free builder are available.
- **🤖 Auto-build:** set separately for each city in the Build tab. Choose **Fields**, **Buildings** or **Balanced**, and a reserve (0%, 25% or 50% of storage) it will never spend. It fills idle builders with the cheapest upgrade in that mode, upgrading a Crop field first when food runs low and the Warehouse or Granary when storage is full. Balanced counts fields at half price so your economy keeps growing. It never builds the Residence, pauses during a siege, and always lets your own queue and build plans go first. "Apply to all cities" copies the setting to your whole realm.
- **🪙 Rush:** finish any construction, training batch or research instantly with gold.

### Buildings

| Building | What it does |
|---|---|
| 🏰 Keep | Makes construction faster and adds builder slots |
| 📦 Warehouse / 🛢️ Granary | Storage for Timber, Clay and Iron / storage for Crop |
| ⚔️ Barracks · 🐎 Stables · ⚙️ Workshop | Train infantry, cavalry, and siege engines and monsters |
| ⚒️ Smithy | Researches weapon and armour upgrades for each unit type |
| 📚 Academy | Your faction's research tree (Imperial Academy, Library of Hoeth, Shaman's Den) |
| 🏛️ Residence | Trains Settlers to found new cities |
| 🎪 Town Hall | Holds Feasts and Great Festivals that earn Renown |
| 🏪 Marketplace | Treasury, Armoury and Mercenaries; trade carts between your cities; barter with factions; automatic supply |
| 🕳️ Cranny | Hides resources, and some gold, from raiders |
| 🪤 Trapper | Captures raiders before a battle |
| 🛡️ City Walls | Multiplies your garrison's defense and sets the size of the free militia |
| 🗼 Watchtower | Earlier raid warnings, better intelligence, and a wider view of enemy armies on the map |
| ⚓ Harbour | Coastal cities only: lets armies from this city sail the sea lanes |
| ⛪ Temple | Cleanses corruption (Shrine of Sigmar, Shrine of Asuryan, Idol of Gork). At level 5 it can destroy Chaos relics |

### Corruption
Chaos taint spreads from the north, and it spreads faster once the invasion begins. Corruption cuts a city's production. Temples, Holy Shrine sites, the Great Temple monument and some technologies fight it.

### Objectives
There are 29 objectives, from "Break ground" to late-game goals. Each one pays a resource reward when you claim it.

---

## Gold and the treasury

Gold is shared by your whole realm. The 🪙 counter in the header shows your treasury and turns red when you are losing gold. Tap it to open the treasury.

### Earning gold
- **Taxes:** every city pays more as its Keep, Marketplace and Harbour level up. Owned Trade Ports add more.
- **Plunder:** raids and assaults bring gold, and sacking a capital brings double.
- **Exploring:** ruins and adventures pay gold.
- **Diplomacy:** ransoming captives pays gold, and allied tribute includes gold (double from Cathay and the Southern Realms).
- **Selling:** sell surplus resources at the Marketplace.

### Spending gold
- **💰 Treasury:** buy resources. Each purchase makes the next one 10% dearer, and the price resets each game day.
- **⚔️ Armoury:** five pieces of gear for your Lords, restocked every game day. You can sell spare gear back.
- **🪖 Mercenaries:** hire Tilean Pikemen, Estalian Crossbows, Norscan Marauders, Ironbreakers, Winged Lancers or Ogre Bulls straight into a city. They eat no Crop but cost gold every hour, and 10% desert each hour your treasury is empty. Only factions not at war with you will sell them.
- **🔨 Rush:** finish construction, training or research instantly.
- **🤝 Diplomacy:** send gold gifts, or pay a faction to go to war with one of your enemies for 10 game days.
- **🗡️ Fund a revolt:** in an enemy settlement, cutting its garrison by 30%, stalling its growth and damaging its recruitment.
- **👑 Lords:** recruit a Lord or heal a wounded one with gold instead of resources.
- **🏛️ Monuments:** one-time great works with realm-wide bonuses:

  | Monument | Bonus |
  |---|---|
  | 🗿 Hall of Heroes | +10% Renown |
  | ⛪ Great Temple | −10 corruption in every city |
  | 🏦 Merchant Guildhall | +15% tax income |
  | ⚒️ War Forge | +5% attack for all your troops |

**War prices:** shop, mercenary and rush prices creep up as the campaign goes on (up to +80%), and plunder gold slowly shrinks in the late game.

---

## Armies and combat

### Units
Each faction has eight or nine combat units, including infantry, ranged troops, cavalry, elite troops, siege engines and a top-tier large unit: a monster such as the High Elves' **Sun Dragon**, or a war machine such as the Empire's **Steam Tank** and the Dwarfs' **Thunderbarge**. Each also has Settlers for founding cities, plus the hireable mercenaries.

Every unit has offense, defense against infantry, defense against cavalry, speed, carry capacity and Crop upkeep. The Army tab lists the troops you have first, then your training options.

### Unit matchups
Units have combat roles that counter each other:

- 🔱 **Anti-large:** up to +50% offense and defense against cavalry and monsters.
- 🐎 **Cavalry:** up to +25% offense against ranged units.
- 🦣 **Large** (monsters, and ⚙️ war machines): up to +25% offense against infantry, ranged units and siege engines.
- 🏹 **Ranged:** +30% defense when fighting behind walls.
- 💣 **Siege:** breaks down enemy walls during an assault.

These bonuses grow with how much of the enemy army is of the type being countered. Battle reports list the matchups that applied.

### Raid, assault or siege
- **🏹 Raid:** a quick strike for plunder. Both sides take partial losses.
- **⚔️ Assault:** a fight to the death. Winning razes an ordinary settlement and sacks a capital. A Lord can claim an ordinary settlement as a new city.
- **🏰 Siege:** for walled towns, capitals and the Citadel. See [Sieges](#sieges).

### 💥 Demolition orders
When you raid or attack an enemy settlement, you can order your siege engines and monsters to tear down its 🧱 Walls, 🗼 Defences, ⚔️ Recruitment or 💰 Commerce after a victory. Raids do half as much damage.

A winning Assault razes ordinary settlements anyway, so demolition matters most on raids and against capitals. The AI does the same to your cities, and its strength depends on difficulty.

### 🧪 Battle forecast and simulator
Before you send an army, the game shows the chance of winning (Certain, Likely, Coin-toss or Defeat), the expected losses and how much loot your survivors can carry. The forecast estimates the enemy **as it will be when you arrive**, including any troops it regrows on the way. The simulator lets you test any army against any target, real or custom.

### Ways to make your army stronger
- **⚒️ Smithy upgrades:** research each unit type up to level 20, with +2% offense and defense per level. Upgrades apply in every city.
- **🎖️ Veterancy:** surviving units earn experience and rank up from Recruit through Blooded, Seasoned, Veteran and Elite to ★★★★★ Legendary, gaining +3% stats per rank.
- **🔬 Research** and the **⚒️ War Forge** monument.

### 🏅 Regiments of Renown
Each faction has three unique elite regiments, unlocked by reaching goals such as winning 60 battles or repelling 15 raids.

| Empire | High Elves | Greenskins |
|---|---|---|
| Carroburg Greatswords | Keepers of the Flame | Grimgor's 'Ard Boyz |
| Emperor's Wolves | Bladelords of Hoeth | Snagla's Grabbas |
| Royal Altdorf Gryphites | Sons of Caledor | Da Krimson Killerz |

Regiments of Renown have 1.5× the stats of the unit they're based on and always count as at least ★★★ Seasoned. At most 20 of each can be alive at once.

### 📋 Raid lists
Save a list of targets for each city, each with its own set army, and launch every raid with one tap. The ✨ button suggests the smallest army that is certain to win, and "Launch all" skips any target the forecast says you'd lose.

---

## Sieges

### Besieging an enemy
Choose **🏰 Siege** when sending an army to a walled town, a capital or the Citadel.

1. Your army camps outside for up to 24 game hours, or as little as 6 if you bring many siege engines and monsters.
2. From halfway through the siege, the garrison starves.
3. Your engineers build siege works: 🪵 palisade and stakes (defense against relief armies), 🐏 rams (lower walls), 🗼 siege towers (halve the wall bonus) and 🎯 catapults (kill defenders before the assault).
4. Nearby settlements of the same faction may send a relief army to break your siege.
5. When the timer ends, your army storms the city.

Led by a Lord with **Claim** ticked, a siege can capture even an **enemy capital**, worth 🪙1,500 gold and ⭐500 Renown. You can lift a siege at any time.

### When the AI besieges you
AI sieges begin once raids have started (day 15 on Normal) and you hold at least two cities.

1. You get a report as soon as the siege host sets out, at least 12 game hours before it arrives.
2. The AI gathers troops from several of its nearby settlements and sizes its army to win both a sally and an assault.
3. If your city has grown too strong by the time it arrives, the host turns back, or sends for reinforcements if it is only slightly short.
4. The siege lasts 18–30 game hours. Production halves, the enemy builds its own siege works, and your garrison goes hungry from halfway through.
5. Your options:
   - **⚔️ Sally out:** your garrison and militia attack in the open, best before the palisade goes up.
   - **⚔️ Break the siege:** send an army from another city.
   - **🪙 Buy them off** with gold.
   - **Hold:** trust your walls.
6. If the assault succeeds, an ordinary city falls and becomes theirs; you can retake it later with a Lord. **Your capital is never captured, only sacked:** stores burned, gold looted and buildings torn down.

---

## Lords, items and exploration

- **Lords** lead your armies, guard your cities, gain experience and learn skills: ⚔️ Command, 🛡️ Defense, 🧭 Logistics and 📜 Governance. You start with your faction's Legendary Lord and can recruit more, one per city.
- **Items** come in four slots (weapon, armour, banner, mount) and four rarities (Common, Rare, Epic, Legendary). Equip them, melt them down for resources, or sell them for gold.
- **Adventures** appear on the map. Send a Lord on one to earn experience, gold, resources and items.
- **🏛️ Ruins and other places to explore:** about 60 sites are scattered across the world: ruins, tombs, shipwrecks, old battlefields, monster lairs and standing stones. Each can be explored once by a Lord.
  - **🕯️ Careful search:** safer, smaller rewards.
  - **🔥 Bold delve:** richer finds, but a risk of wounds and curses.
- A wounded Lord can be revived for resources or gold, or recovers on his own after 36 game hours.

---

## The world map

The map covers the whole Warhammer world, inspired by the Immortal Empires campaign of *Total War: Warhammer III*. It includes the Empire, Bretonnia, Kislev, Norsca, the Chaos Wastes, the World's Edge Mountains, the Dark Lands, Cathay, the Southern Realms, Araby, Nehekhara, the Southlands, Lustria, Naggaroth, Ulthuan and Albion. You can pan and pinch-zoom it, and switch overlays for borders, taint and terrain.

- **Movement:** each kind of terrain has its own movement cost.
- **🌊 Sea lanes** connect the continents. Armies from a city with a **⚓ Harbour** can sail them.
- **Seeing armies:** your own marches appear as dotted lines. You see AI armies on the move within your cities' sight, which is 3 tiles plus 1 per Watchtower level, and always see your allies' armies.

### Factions of the world
Up to twenty AI factions share the map with you: 🐐 Beastmen, 🔥 Warriors of Chaos, 🦇 Vampire Counts, ⚒️ Dwarfs, 🌳 Wood Elves, 🐺 Norsca, ⚜️ Bretonnia, ❄️ Kislev, the Southern Realms, Dark Elves, Lizardmen, Vampire Coast, Tomb Kings, Chaos Dwarfs, Ogre Kingdoms, Cathay, Rival Greenskins, 🦅 The Empire, 🦢 High Elves and 🐀 Skaven. Your own faction is always left out (see [The four factions](#the-four-factions)).

Beastmen and Chaos are always hostile. The others are open to diplomacy, and each has its own temperament: the Dwarfs keep a Book of Grudges, the Wood Elves resent armies marching through Athel Loren, and Norsca raids the richest cities.

### 🐀 The Skaven
The ratmen of the Under-Empire hold Skavenblight in the Tilean marshes, the Hell Pit in the north, and warrens under the World's Edge Mountains and the Badlands, including one beside Karak Eight Peaks.

- **Units:** Skavenslaves and Clanrats in great numbers, backed by Warplock Jezzails, Plague Monks, Rat Ogres, the Doomwheel and the Warp Lightning Cannon.
- **The Under-Empire:** once your beginner protection ends, new warrens surface every day or two, 6–12 tiles from one of your cities (richer cities attract them more). Raze them before they grow and raid you.
- **Warpstone hunger:** if you hold a ☄️ Warpstone Crater, the Skaven target it far more often than other holdings, and come from further away to take it.
- **Treachery:** you can sign treaties with them, but each day there's a chance they tear up every treaty at once. The chance is high (30%) when your army at home looks weak compared with their strength, and low (3%) otherwise.
- **Relations:** they start hostile to everyone, and the Dwarfs hate them most. They also fight the Rival Greenskins, the Empire, Kislev, Cathay, the Lizardmen and the AI Dwarfs.

### Diplomacy
Open 🤝 **Diplomacy** from the top bar.

- **Attitude:** each faction's attitude towards you, from −100 to +100, is built from listed reasons you can inspect. These include racial history, gifts, shared enemies, raids against them and broken promises. Most reasons fade over time.
- **Stance:** a faction goes to **War** when its attitude falls to −50 or below, unless you have a non-aggression pact. Only an alliance makes it an **Ally**.
- **Treaties:** non-aggression pact, trade agreement, military access, defensive pact and alliance. Each needs a minimum attitude. Your chance of agreement improves with a better attitude, a sweetener of gold, and your **reputation** for keeping your word. Breaking a treaty hurts your reputation with everyone.
- **Gifts:** resources or gold improve attitude, with diminishing returns.
- **📨 Inbox:** AI factions send you proposals, demands for tribute, and requests, such as raze a common enemy or deliver resources. Accepting or refusing changes your relations.
- **War score, peace and surrender:** victories against a faction raise your war score. A beaten faction may offer peace or surrender with tribute, and you can offer peace yourself. Peace begins with a truce.
- **Allies** send tribute every 12 game hours, may send relief armies when you are besieged, and join the **Grand Alliance** against Chaos.

### AI factions that grow on their own
- **Growth:** AI settlements level up over time. Factions that hold more land grow faster.
- **What slows them:** your raids stall a settlement's growth, and sacking a capital cripples its whole faction for a while.
- **War between AI factions:** strong factions found new settlements and march against their enemies. Battles near you are reported.
- **Capitals and collapse:** a faction that loses its capital eventually names a new one. If it loses everything, it is gone for good.
- **Keeping pace with you:** AI growth slows sharply, then stops, once it gets too far ahead of your own development. The allowed gap depends on difficulty.
- **Rankings:** the **Powers of the Old World** panel ranks every faction by strength.

### Sites and landmarks
- **Neutral sites:** Ancient Groves, Clay Quarries, Old Dwarf Mines, Fertile Valleys, Holy Shrines, Desert Oases, Wild Horse Plains, Wizard's Towers, Trade Ports and Warpstone Craters. Each is guarded by beasts; win an assault to claim it for one of your cities.
- **⭐ Landmarks:** 12 legendary places, such as Karak Eight Peaks, Mordheim, Black Fire Pass, the Black Pyramid of Nagash and the Oak of Ages. Each gives a realm-wide bonus while you hold it.
- **Defending holdings:** every holding has **free militia**, which grows with the Keep and Walls of the city that owns it. You can station extra troops there. Enemy factions at war with you will try to take holdings back.

---

## Defending your realm

- **Grace period:** raids begin on day 15 on Normal (adjustable). Chaos raids begin with the invasion.
- **🛡️ Free militia:** every city has militia that cost no upkeep and refill over time. Their number grows with the city's Walls: 90 at level 10 and 170 at level 20. They defend against raids and sieges and join sallies.
- **🗼 Watchtowers:** level 1 reveals where a raid comes from, level 3 estimates its size, and level 6 shows its full makeup.
- **Other defences:** 🛡️ Walls, 🕳️ the Cranny (which also hides some gold) and your Lord's Defense skill all reduce the damage raids do. Raiders who win steal some of your unhidden gold, and may tear down buildings.
- **🪤 The Trapper:** traps capture up to 35% of an attacking army before the battle. You can ransom the captives for gold, release them for better relations, or execute them for Renown.

---

## Growing your realm

### More cities
You can rule up to **8 cities**:
- Earn Renown, train 3 Settlers in a Residence, and found a new city on empty land.
- Have a Lord win an assault on an enemy settlement and claim it.
- Take an enemy capital with a siege.

New cities are safe from raids for 3 game days.

### 🔬 Research tree
Each faction has 20 technologies in four branches:

- 🌾 **Economy:** production, construction speed, storage.
- ⚔️ **Military:** training speed, and bonuses for each troop type.
- 🏛️ **Realm:** march speed, agent success, walls, Renown, veterancy and army upkeep.
- 💰 **Treasury:** taxes, plunder gold, selling prices, mercenary upkeep, market prices and gold hidden from raiders.

Each branch unlocks tier by tier, and deeper tiers need a higher-level research building.

### 🎪 Feasts
The Town Hall can hold a **Feast** (24 game hours) or, from level 10, a **Great Festival** (60 game hours, with +10% production while it lasts). Both pay out a burst of Renown.

---

## Agents

Recruit spies to act in the shadows. The Empire has 🕵️ **Witch Hunters**, the High Elves have 🪄 **Loremasters** and the Greenskins have 🍄 **Goblin Shamans**. You can have one agent per city plus one, up to 4.

| Mission | Effect |
|---|---|
| 💥 Sabotage walls | Removes 3–6 wall levels for 24 game hours. Time your assault to match. |
| 🗡️ Thin the garrison | Kills 10–20% of the defenders |
| 🌀 Sow dissent | Stops the settlement growing for 48 game hours and knocks it back |

The chance of success is shown before you send an agent. A failed mission can wound or kill the agent.

---

## The War Against Chaos

The Chaos Citadel is very strong, so the campaign gives you ways to weaken it and reach it. The war begins with the **Dark Omens**, the day before the Chaos invasion. Your faction's voice guides you: the Grand Theogonist for the Empire, Teclis for the High Elves and Grimgor for the Greenskins. Everything is tracked in the **📜 War journal** at the top of the Map tab, with hints and "📍 Show" buttons.

### Eleven objectives
| Objective | How | Effect on the Citadel |
|---|---|---|
| 🌀 Rift of Blood | Win an assault | Defenders −10% defense |
| 🌀 Rift of Rot | Win an assault | Regrows at half speed |
| 🌀 Rift of Change | Win an assault | Walls −4 |
| 🌀 Rift of Excess | Win an assault | Chaos raids 30% smaller |
| 👹 Four Chaos Heralds | Win an assault on each | −1 Citadel level each |
| 💀 Three corrupted relics | Explore the hiding place with a Lord, then destroy the relic at a Temple of level 5 | Smaller Citadel garrison |

Every objective also shrinks the Citadel's garrison. Completing all eleven roughly halves its strength.

### Roads north
Marches to the far north use your faction's road automatically whenever it is faster.

| Faction | Road | How to open it |
|---|---|---|
| 🦅 Empire | ❄️ **Ice Road of Kislev** | Stay out of war with Kislev. Kislevite troops also join your Citadel battles. |
| 🦢 High Elves | 🔥 **Phoenix Gate** | Hold any Landmark, or perform the Gate Rite (Academy level 5, one game day) |
| 👹 Greenskins | 🕳️ **The Underway** | Hold an Old Dwarf Mine. During a WAAAGH! extra Orc warbands join your Citadel battles. |
| ⚒️ Dwarfs | 🕳️ **Ungdrin Ankor** | Hold an Old Dwarf Mine or Karak Eight Peaks |

### 🤝 The Grand Alliance
Every faction allied with you sends about half of its strongest army to fight beside you whenever you assault the Citadel or a Chaos Champion. The battle forecast shows who is joining.

---

## The endgame

1. **The Chaos invasion** begins on day 30 on Normal (adjustable, or switched off in Settings). New Chaos warbands appear, Chaos raids begin and corruption spreads faster.
2. **Victory:** sack the **Citadel of the Dread Warlord** in the Chaos Wastes. A victory screen shows your score, your rank and full campaign statistics.
3. **The Dark Gods answer:** after your victory, Champions of **Khorne, Nurgle, Tzeentch and Slaanesh** arrive one at a time, each with its own trait:
   - Khorne's raids hit harder.
   - Nurgle's army regrows twice as fast.
   - Tzeentch's lair has stronger walls.
   - Slaanesh's raiders arrive sooner.

   Each Champion you slay gives a Legendary item and Renown.
4. **The final battle:** after all four Champions fall, **Archaon the Everchosen** comes for you. Defeat him to avert the End Times and complete your campaign.

### Score and the Hall of Legends
- **Score:** counts victories, Champions slain, battles, kills, sacks, sites, cities, Lords, objectives, gold earned and Legendary items. It is multiplied by difficulty.
- **Ranks:** from 🪖 Militia Captain up to 🌅 Legend of the End Times.
- **🏛️ Hall of Legends:** keeps your best campaigns on your device, even after you reset your save.

---

## Settings, difficulty and game speed

### Difficulty presets

| Difficulty | Raids start | Raid gap | Chaos invasion | AI siege gap | Enemy demolition | How far the AI can outgrow you |
|---|---|---|---|---|---|---|
| 🕊️ Easy | Day 20 | 36 game hours | Day 40 | 7 days | 50% | +2 levels |
| ⚔️ Normal | Day 15 | 24 game hours | Day 30 | 4.5 days | 100% | +4 levels |
| 🔥 Hard | Day 10 | 16 game hours | Day 25 | 3 days | 150% | +7 levels |
| 💀 Brutal | Day 7 | 10 game hours | Day 20 | 2 days | 200% | +10 levels |

Every setting can also be adjusted on its own in **⚙️ Settings**, including raid size, AI growth speed, the day Beastmen raids begin and the day the Chaos invasion begins.

### Other settings
- **🕊️ Peaceful mode** (off by default): no raids or sieges, and incoming armies turn back. Build your empire in peace.
- **⏸️ Pause the clock** (off by default): the in-game days stop advancing, but you can still build, train and move armies. Useful when you take a break.
- **🐐 Beastmen raids** and **☠️ Chaos invasion & raids:** switch either one off completely.

### Game speed
Set the speed to **1×, 5×, 10×, 50×, 100×, 250×, 500×, 750× or 1000×** at any time. It speeds up production, construction, training and marching, and timers already running are adjusted automatically.

---

## Saving your progress

- The game saves automatically to your browser's storage on this device.
- In **⚙️ Settings**, tap **📤 Copy save code** to back up your campaign. Use **📥 Load save code** to restore it, or to move it to another device or browser.
- Your save is tied to the place you open the game from: the local file, the GitHub Pages link and a Claude artifact link each count as different places. Use a save code to move your campaign between them.
- Safari may clear website data that hasn't been used for several weeks. Adding the game to your Home Screen and keeping a backup code protects you against this.

---

*GrimFall is an unofficial fan project inspired by Games Workshop's Warhammer Fantasy Battles, Creative Assembly's Total War: Warhammer, and Travian. It is not affiliated with or endorsed by any of them.*
