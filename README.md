# Elysium for DeCiv Redux

## Mod Info

- Mod Version: 1.1.0-beta03
- Required Base Game Version: 4.12.4~
- Dependencies: [DeCiv Redux](https://github.com/SpacedOutChicken/DeCiv-Redux)

## Introduction

Lead Elysium, a rare democracy in the middle of a nuclear wasteland, \
whose citizens would proudly and fiercely defend her constitution and civil liberties, \
regardless of their harsh situation.

## Elysium

### Profile

- Leader: The Chancellor
- Preferred Victory Type: Cultural
- Start Bias: Coast

### Uniques

#### Land of the Free, Home of the Brave

<img src="docs/Elysium.png" alt="Icon of Elysium" height="50" />

- Starts with Constitution adopted (thus cannot adopt Supremacy)
- +15% Strength when fighting in Friendly Land tiles
- -15% Strength when fighting in Enemy Land tiles
- +15% Production when constructing Military units in all non-occupied cities when at war
- Water cost of purchasing Military units -15% when at war
- Cannot build Enslaved units
- Cannot build Prison Camp, Work Camp, or Council buildings

### Unique Buildings

#### Constitution of Elysium

<img src="Images/BuildingIcons/Constitution of Elysium.png" alt="Icon of the Constitution of Elysium" height="50" />

- Unique Wonder
- Can only be built in capital
- +1 Culture from all specialists in this city
- 2 free Medic units appear
- Gain a free Food Store and Stele of Constitution in this city

#### Elysian Parliament

<img src="Images/BuildingIcons/Elysian Parliament.png" alt="Icon of the Parliament" height="50" />

- Replaces Congress and also technically replaces the Council at the same time
- Beta 3 update: Renamed from Parliament so Elysium no longer steals a UB from Commonwealth
- Production cost increased to 150
- Lost
  - -10% unhappiness from population in all cities
- Gained
  - -5% unhappiness from population in all cities connected to capital
  - +25% Production towards any buildings that already exist in the capital
  - +25% Great Person generation in all cities connected to capital
  - +10% growth in all cities connected to capital

#### Stele of Constitution

<img src="Images/BuildingIcons/Stele of Constitution.png" alt="Icon of a Stele of Constitution" height="50" />

- Replaces Monument
  - Requires Construction instead of being available on Turn 1
  - Can only be built in cities connected to capital
  - +1 Local Happiness per 8 population in this city
  - Destroyed when the city is captured

#### Court

<img src="Images/BuildingIcons/Court.png" alt="Icon of a Court" height="50" />

- Standalone building that is a pseudo-replacement for the Prison Camp
- Gained
  - +1 Culture
  - +1 Maintenance Cost
  - Only available in cities with a Stele of Constitution
- Lost
  - Can only be built in annexed city
  - Provides 1 Slave
  - -1 Food

#### Immigration Office

<img src="Images/BuildingIcons/Immigration Office.png" alt="Icon of a Refugee Center" height="50" />

- Standalone building that is a pseudo-replacement for the Work Camp (avoiding penalties from certain policies)
- Beta 3 Update: Renamed from Refugee Center so Elysium no longer steals a UB from Commonwealth
- Gained
  - +1 Culture
  - +15% Culture
  - +1 Administrator slot
  - +1 population
  - Unsellable
- Lost
  - +1 Production in this city with Power
  - +2 Production in this city with Slaves
  - +1 Production
  - +15% Production
  - +1 Engineer slot

### Unique Units

#### Medic

<img src="docs/Medic.png" alt="Icon of a Medic" height="50" />

- Replaces Crossbowman
- Upgrades to Support
- Gained
  - 20 Ranged Strength (vs. 18)
  - 2 Range (vs. 1)
  - -1 Sight penalty
  - All adjacent units heal +10 HP when healing in Friendly Land tiles
- TBA

#### Support

<img src="docs/Support.png" alt="Icon of a Support" height="50" />

- Replaces Conscript
- Can upgraded from Medic
- Upgrades to NBC Support
- Gained
  - 30 Ranged Strength
  - 2 Range
  - -1 Sight penalty
  - 24 Defense Strength (vs. 30)
  - All adjacent units heal +10 HP when healing in Friendly Land tiles
- TBA

#### NBC Support

<img src="docs/NBC Support.png" alt="Icon of a NBC Support" height="50" />

- Replaces NBC Conscript
- Can upgrade from Support
- Gained
  - 35 Ranged Strength
  - 2 Range
  - All adjacent units heal +10 HP when healing in Friendly Land tiles
  - Can upgrade to Black Ops
- TBA
