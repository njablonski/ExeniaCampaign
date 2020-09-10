# The Exenia Campaign

The Exenia Campaign is strategic map campaign system for four players in [Star Wars: X-Wing Second Edition](https://www.fantasyflightgames.com/en/products/x-wing-second-edition/).

* [Overview](#overview)
* [Map](#map)
* [Icons](#icons)
* [Key Concepts](#key-concepts)
   * [Fuel](#fuel)
   * [Supply](#supply)
   * [Readiness](#readiness)
* [Setup](#setup)
   * [Rebel Carriers](#rebel-carriers)
   * [Imperial Carriers](#imperial-carriers)
   * [Rebel Starfighter Wings](#rebel-starfighter-wings)
   * [Imperial Starfighter Wings](#imperial-starfighter-wings)
* [Carrier Status Sheet](#carrier-status-sheet)
* [Exenia Battle Format](#exenia-battle-format)

***

<br/>

## Overview

[Watch the opening crawl!](https://njablonski.github.io/ExeniaCampaign/)

In the Exenia Campaign, each player controls a Carrier starship with a large complement of classic Star Wars starfighters from the original trilogy and [Legends](https://starwars.fandom.com/wiki/Star_Wars_Legends) stories. The campaign plays out over a series of strategic turns, during which players will move their Carriers, sortie their Starfighter Wings, resolve battles with games of [Star Wars: X-Wing Second Edition](https://www.fantasyflightgames.com/en/products/x-wing-second-edition/), and attempt to collect enough fuel from Black Sun refineries to safely return to known space.

The campaign features two factions, the Rebel Alliance and the Galactic Empire, and players will each be part of a two-person team representing one of the factions.

Strategic turns are tracked on a hex map, which can be managed on [HexTML](https://hextml.playest.net/) using the [provided files](https://raw.githubusercontent.com/njablonski/ExeniaCampaign/master/assets/starting_map.html), or tracked with pen and paper or other software.

***

<br/>

## Map

The size of the map is 68 hexes, arranged in alternating rows of length 8 and 9.

See the example map below, which shows the state of the map at the beginning of the campaign.

![](./intro/initial_conditions.png)

***

<br/>

## Icons

![](https://github.com/njablonski/ExeniaCampaign/blob/master/assets/icon-summary-3.png?raw=true)

***

<br/>

## Key Concepts

The following terms and concepts are important to understand when playing the Exenia Campaign.

### Fuel

The objective of the Exenia Campaign is to collect enough Coaxium hyperdrive fuel from the Black Sun Refineries to return both of your team's carriers to the known galaxy. Fuel is collected by Carriers or Starfighter Wings that control Refineries during the _Resource Collection_ phase of a strategic turn.

Fuel can be spent during the _Carrier Movement_ phase of a strategic turn to increase your carrier's hyperdrive speed, which allows it to move an additional hex.

### Supply

Supply represents various consumable resources. The forces in the Exenia Campaign are far away from typical Rebel or Imperial supply lines, and must be judicious about their use of scarce supplies. Additional supplies can be gathered by Carriers or Starfighter Wings that control Fabricator Outposts during the _Resource Collection_ phase of a strategic turn.

In the _Battle Resolution_ phase of a strategic turn, players can spend supply on _Ordnance_ and _Personnel_ to allow their starfighters to take additional upgrades.

In the _Strategic Preparations_ phase, Carriers that were not involved in battles and Starfighter Wings that did not Sortie can spend supply on _Maintenance_ to increase their _Readiness_.

### Readiness

Readiness represents the condition of equipment and personnel needed to operate a Carrier or Starfighter Wing. There are four levels of readiness, each with its own affect on a Carrier or Starfighter Wing:

<table class="tg">
<thead>
  <tr>
    <th class="tg-0lax"></th>
    <th class="tg-0lax"><b>3. Reinforced</b></th>
    <th class="tg-0lax"><b>2. Ready</b></th>
    <th class="tg-0lax"><b>1. Weakened</b></th>
    <th class="tg-0lax"><b>0. Grounded</b></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0lax"><b>Effect on a Carrier</td>
    <td class="tg-0lax">May sortie 2 Starfighter Wings</b></td>
    <td class="tg-0lax">May sortie 2 Starfighter Wings</b></td>
    <td class="tg-0lax">May sortie 1 Starfighter Wing</b></td>
    <td class="tg-0lax">Carrier is destroyed</b></td>
  </tr>
  <tr>
    <td class="tg-0lax"><b>Effect on a Starfighter Wing</b></td>
    <td class="tg-0lax">May field up to 170 points in battle</b></td>
    <td class="tg-0lax">May field up to 150 points in battle</b></td>
    <td class="tg-0lax">May field up to 130 points in battle</b></td>
    <td class="tg-0lax">Cannot sortie</b></td>
  </tr>
</tbody>
</table>

When the Galactic Empire or Rebel Alliance lose a battle, all of that team's involved Carriers and Starfighter Wings go down one level of _Readiness_.

If a Starfighter Wing does not sortie, it can spend 1 supply on _Maintenance_ to increase its _Readiness_ one level in the _Strategic Preparations_ phase. Similarly, in the _Strategic Preparations_ phase, if a Carrier was not involved in a battle during the current strategic turn, it can spend 1 supply on _Maintenance_ to increase its _Readiness_ one level.


***

<br/>

## Setup

During setup, each player chooses which Carrier and Starfighter Wings he will control. You can randomize which player controls which carrier by having all players roll a d100, then in order of results from highest to lowest roll a d4, then a d3, then a d2, assigning remaining Carriers at each roll to numbers on the next dice.

### Rebel Carriers

- _**Paradise**_ ([Rebel MC80 Star Cruiser](https://starwars.fandom.com/wiki/MC80_Home_One_type_Star_Cruiser))
- _**Pursuit**_ ([Rebel MC80 Star Cruiser](https://starwars.fandom.com/wiki/MC80_Home_One_type_Star_Cruiser))

### Imperial Carriers

- _**ISD Gauntlet**_ ([Imperial Star Destroyer](https://starwars.fandom.com/wiki/Imperial-class_Star_Destroyer))
- _**ISD Nemesis**_ ([Imperial Star Destroyer](https://starwars.fandom.com/wiki/Imperial-class_Star_Destroyer))

The players who control the _**Paradise**_ and the _**Pursuit**_ will form the Rebel team, and the players who control the _**Gauntlet**_ and the _**Nemesis**_ will form the Imperial team.

Once Carriers have been chosen, each team should work together to assign Starfighter Wings to their Carriers. There are four Rebel Starfighter Wings and four Imperial Starfighter Wings. Each Carrier can host two Starfighter Wings. Once each team has assigned Starfighter Wings to their Carriers, you're ready to record your initial status and begin the first strategic turn.

### Rebel Starfighter Wings

<table class="tg">
<thead>
  <tr>
    <th class="tg-73oq">Name</th>
    <th class="tg-73oq" colspan="3">Starfighter Types</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0pky"><b><i>Danger Wing</b></i></td>
    <td class="tg-0pky">T-65 X-Wing</td>
    <td class="tg-0pky">BTL-A4 Y-Wing</td>
    <td class="tg-0pky">Z-95 Headhunter</td>
  </tr>
  <tr>
    <td class="tg-0pky"><b><i>Enigma Wing</td>
    <td class="tg-0pky">T-65 X-Wing</td>
    <td class="tg-0pky">A/SF-01 B-Wing</td>
    <td class="tg-0pky">RZ-1 A-Wing</td>
  </tr>
  <tr>
    <td class="tg-0pky"><b><i>Outlaw Wing</b></i></td>
    <td class="tg-0pky">T-65 X-Wing</td>
    <td class="tg-0pky">RZ-1 A-Wing</td>
    <td class="tg-0pky">Z-95 Headhunter</td>
  </tr>
  <tr>
    <td class="tg-0lax"><b><i>Dynamo Wing</b></i></td>
    <td class="tg-0lax">T-65 X-Wing</td>
    <td class="tg-0lax">BTL-A4 Y-Wing</td>
    <td class="tg-0lax">A/SF-01 B-Wing</td>
  </tr>
</tbody>
</table>

### Imperial Starfighter Wings

<table class="tg">
<thead>
  <tr>
    <th class="tg-73oq">Name</th>
    <th class="tg-73oq" colspan="3">Starfighter Types</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0pky"><b><i>Alpha Wing</b></i></td>
    <td class="tg-0pky">TIE/LN Fighter</td>
    <td class="tg-0pky">TIE/X1 Advanced</td>
    <td class="tg-0pky">TIE/IN Interceptor</td>
  </tr>
  <tr>
    <td class="tg-0pky"><b><i>Beta Wing</b></i></td>
    <td class="tg-0pky">TIE/LN Fighter</td>
    <td class="tg-0pky">TIE/SA Bomber</td>
    <td class="tg-0pky">TIE/PH Phantom</td>
  </tr>
  <tr>
    <td class="tg-0pky"><b><i>Gamma Wing</b></i></td>
    <td class="tg-0pky"><span style="font-weight:400;font-style:normal">TIE/LN Fighter</span></td>
    <td class="tg-0pky"><span style="font-weight:400;font-style:normal">TIE/PH Phantom</span></td>
    <td class="tg-0pky"><span style="font-weight:400;font-style:normal">TIE/IN Interceptor</span></td>
  </tr>
  <tr>
    <td class="tg-0lax"><b><i>Delta Wing</b></i></td>
    <td class="tg-0lax"><span style="font-weight:400;font-style:normal">TIE/LN Fighter</span></td>
    <td class="tg-0lax"><span style="font-weight:400;font-style:normal">TIE/X1 Advanced</span></td>
    <td class="tg-0lax"><span style="font-weight:400;font-style:normal">TIE/SA Bomber</span></td>
  </tr>
</tbody>
</table>

***

<br/>

## Carrier Status Sheet

Throughout the game, players will need to track the status of their Carriers and Starfighter Wings. This status will change from one strategic turn to the next. To track the status of a Carrier, you need to record its location, readiness, fuel, supply, and the readiness of its Starfighter Wings. See the example Carrier status sheet below.

<table class="tg">
  <tr>
    <td class="tg-0pky"><span style="font-weight:bold"><b>Name</b></span></td>
    <td class="tg-c3ow" colspan="2">ISD Gauntlet</td>
  </tr>
  <tr>
    <td class="tg-0pky"><span style="font-weight:bold"><b>Location</b></span></td>
    <td class="tg-c3ow" colspan="2">Hex 35</td>
  </tr>
  <tr>
    <td class="tg-0pky"><span style="font-weight:bold"><b>Fuel</b></span></td>
    <td class="tg-c3ow" colspan="2">1</td>
  </tr>
  <tr>
    <td class="tg-0pky"><span style="font-weight:bold"><b>Supply</b></span></td>
    <td class="tg-c3ow" colspan="2">1</td>
  </tr>
  <tr>
    <td class="tg-0lax"><span style="font-weight:bold"><b>Readiness</b></span></td>
    <td class="tg-baqh" colspan="2">Ready</td>
  </tr>
  <tr>
    <td class="tg-0lax" rowspan="3"><span style="font-weight:bold"><b>Fighter Wings</b></span></td>
    <td class="tg-0lax"><span style="font-weight:bold"><b>Name</b></span></td>
    <td class="tg-0lax"><span style="font-weight:bold"><b>Readiness</b></span></td>
  </tr>
  <tr>
    <td class="tg-0lax">Beta Wing<br/><br/>Gamma Wing</td>
    <td class="tg-0lax">Ready<br/><br/>Ready</td>
  </tr>
</table>

***

<br/>

## Exenia Battle Format

The Exenia campaign resolves battles through games of [Star Wars: X-Wing Second Edition](https://www.fantasyflightgames.com/en/products/x-wing-second-edition/). Each game you play represents a battle that has been triggered by events in the current strategic turn, and the outcome of the game will determine the outcome of the battle.

The Exenia Campaign aims to tell a new, thematic Legends story, and to be a fresh, newbie-friendly way to experience the Star Wars universe through the X-Wing miniatures game. To this end, the Exenia Campaign uses a special restricted format for [Star Wars: X-Wing Second Edition](https://www.fantasyflightgames.com/en/products/x-wing-second-edition/). The rules of this format are as follows:

- Your list may only include ship types available to your Starfighter Wings involved in the strategic campaign battle that the game represents.
- The points limit for your list is determined by the _Readiness_ of your Starfighter Wing. The limit is:
  - 170 points for a **Reinforced** wing.
  - 150 points for a **Ready** wing.
  - 130 points for a **Weakened** wing.
- When two allied wings participate in the same battle, they may each bring a list of up to half the points limit determined by their _Readiness_, plus 10.
- You may not take any unique named pilots or upgrades (cards with a • next to their name).
- Taking upgrades may require spending strategic campaign resources.
  - You can always take Talent upgrades.
  - To take [Crew](https://xwing-miniatures-second-edition.fandom.com/wiki/Category:Crew_Upgrades), Gunner, [Astromech](https://xwing-miniatures-second-edition.fandom.com/wiki/Category:Astromech_Upgrades), or Modification upgrades requires than you spend 1 supply on _Personnel_ for the battle.
  - To take Missile, Torpedo, [Device](https://xwing-miniatures-second-edition.fandom.com/wiki/Category:Device_Upgrades), or Turret upgrades requires that you spend 1 supply on _Ordnance_ for the battle.

These rules enhance the verisimilitude of the story as it unfolds in the strategic game, disincentivizes netdecking behavior, and levels the playing field for players who may not be familiar with the metagame of popular formats.
