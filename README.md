# The Exenia Campaign

The Exenia Campaign is strategic map campaign system for four players in [Star Wars: X-Wing Second Edition](https://www.fantasyflightgames.com/en/products/x-wing-second-edition/).

## Overview

[Watch the opening crawl!](https://njablonski.github.io/ExeniaCampaign/)

In the Exenia Campaign, each players controls a carrier starship with a large complement of classic Star Wars starfighters from the original trilogy and [Legends](https://starwars.fandom.com/wiki/Star_Wars_Legends) stories. The campaign plays out over a series of strategic turns, during which players will move their carriers, sortie their starfighters, resolve battles with games of [Star Wars: X-Wing Second Edition](https://www.fantasyflightgames.com/en/products/x-wing-second-edition/), and attempt to collect enough fuel from Black Sun refineries to safely return to known space.

The campaign features two factions, the Rebel Alliance and the Galactic Empire, and players will each be part of a two-person team representing one of the factions.

Strategic turns are tracked on a hex map, which can be managed on [HexTML](https://hextml.playest.net/) using the [provided files](https://raw.githubusercontent.com/njablonski/ExeniaCampaign/master/assets/starting_map.html), or tracked with pen and paper or other software.

## Map

The size of the map is 68 hexes, arranged in alternating rows of length 8 and 9.

See the example map below, which shows the state of the map at the beginning of the campaign.

![](./intro/initial_conditions.png)

## Icons

![](https://github.com/njablonski/ExeniaCampaign/blob/master/assets/icon-summary-3.png?raw=true)

## Setup

During setup, each player chooses which carrier they will control and customizes their starfighter squadrons. You can randomize which player controls which carrier by having all players roll a d100, then in order of results from highest to lowest roll a d4, then a d3, then a d2, assigning remaining carriers at each roll to numbers on the next dice.

### Rebel Carriers

- _**Paradise**_ ([Rebel MC80 Star Cruiser](https://starwars.fandom.com/wiki/MC80_Home_One_type_Star_Cruiser))
- _**Pursuit**_ ([Rebel MC80 Star Cruiser](https://starwars.fandom.com/wiki/MC80_Home_One_type_Star_Cruiser))

### Imperial Carriers

- _**ISD Gauntlet**_ ([Imperial Star Destroyer](https://starwars.fandom.com/wiki/Imperial-class_Star_Destroyer))
- _**ISD Nemesis**_ ([Imperial Star Destroyer](https://starwars.fandom.com/wiki/Imperial-class_Star_Destroyer))

The players who control the _**Paradise**_ and the _**Pursuit**_ will form the Rebel team, and the players who control the _**Gauntlet**_ and the _**Nemesis**_ will form the Imperial team.

Once carriers have been chosen, each team should work together to assign starfighter wings to their carriers. There are four Rebel starfighter wings and four Imperial starfighter wings. Each carrier can host two starfighter wings, and the different wings have different available starfighter types.

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

## Exenia Battle Format

The Exenia campaign resolves battles through games of [Star Wars: X-Wing Second Edition](https://www.fantasyflightgames.com/en/products/x-wing-second-edition/). Each game you play represents a battle that has been triggered by events in the current strategic turn, and the outcome of the game will determine the outcome of the battle.

The Exenia Campaign aims to tell a new, thematic Legends story, and to be a fresh, newbie-friendly way to experience the Star Wars universe through the X-Wing miniatures game. To this end, the Exenia Campaign uses a special restricted format for [Star Wars: X-Wing Second Edition](https://www.fantasyflightgames.com/en/products/x-wing-second-edition/). The rules of this format are as follows:

- Your list may only include ship types available to your starfighter wings involved in the strategic campaign battle that the game represents.
- The points limit for your list is determined by the _Readiness_ of your involved starfighter wings. The limit is:
  - 175 points for a **Reinforced** wing.
  - 150 points for a **Ready** wing.
  - 125 points for a **Weakened** wing.
- When two allied wings participate in the same battle, they may each bring a list of up to 100 points, regardless of their _Readiness_.
- You may not take any unique named pilots or upgrades (cards with a • next to their name).

These rules enhance the verisimilitude of the story as it unfolds in the strategic game, disincentivizes netdecking behavior, and levels the playing field for players who may not be familiar with the metagame of popular formats.
