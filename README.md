# Improved Town Layouts

![Photo credit: Kale on Discord](docs/itl_kale.png)
_Photo credit: Kale on Discord_

A house replacement set using default graphics with new rules and features.

## Features
### Better downtowns and suburbs
- High-density residential and commercial buildings only grow within the coverage area of a passenger station
- Downtown buildings cluster together
  - Pre-skyscraper brick buildings cluster separately from skyscrapers, so some cities have a separate "Old" and "New Town"
  - Note: A gap in passenger station coverage will block the cluster from expanding in that direction, since buildings may only grow within 2 tiles of another in its cluster
- Downtowns stay proportional to the town
  - Each office building requires houses for its workers, so the towers won't overrun the suburbs

### Historic Preservation
- All buildings have longer lifespans to reduce the churn of constant rebuilding
- Historic downtown buildings are kept in some towns, but demolished in others
- Landmark buildings last forever

### Landmark buildings
- Landmarks lend character to your city and often generate increased passenger traffic
- Some landmarks only grow in Cities (Hotel, Spa)
- Some landmarks only grow when the town has enough population (Stadium, University, Courthouse)
- All landmarks are kept from appearing too often, either some distance apart or only one per town

### Start as early as 1700
- Introduction dates range from 1700 to 2000, allowing a slow progression over time
- Old houses accept Wood (until 1850) and Coal (until 1945) for fuel
- Early buildings have reduced population to allow older, slower vehicles to keep up with demand
  - 1700-1850: 1/4 population
  - 1850-1950: 1/2 population

### Supports Waste & Recycling
**Requires Improved Town Industries**
- When used with Improved Town Industries, houses generate Waste

## Compatibilities
- Compatible with all industry sets and GameScripts (please report any problems)
- Uses only base game sprites, thus compatible with any base graphics set including Original TTD, OpenGFX, aBase, zBase, and NightGFX
- Requires OpenTTD version 1.10.0, JGR version 0.34, or better.

## Parameters
Use additional sprites. Default off.
- Use Bank sprites
  - Adds the Bank sprites as a University (temperate bank sprite) and a Courthouse (sub-arctic bank sprite)
  - Not recommended if playing with an industry set which includes banks
- Use FIRS Hotel sprites
  - Adds the sub-arctic Hotel sprite as a Spa
  - Not recommended if playing with FIRS, which also uses this sprite
- Use sub-tropical sprites
  - Adds the sub-tropical church sprite as an additional Church type
  - Adds one of the flats sprites as a random sprite of the Warehouse

## Limitations / Not in Scope
- This is a house replacement set. It does not improve the behavior of other NewGRF houses, how towns build roads, or [town growth](https://wiki.openttd.org/en/Manual/Towns#town-growth)
- This set is intended for the Temperate climate. It does not include snow-aware sprites, because they do not exist for most buildings.
