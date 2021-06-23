# Changelogs

_note: minor changes won't be listed as they are only data changes_

## V2

### 2.2

### new Field

- `cards/{cardId}`, `sets/{set}/{card-localId}`: Added a `legal` field like the `sets/{set}` one

### 2.1

### new Field

- `sets/{set}`: Added `normal, revere, holo, firstEdition` fields in the `cardCount` field

### 2.0

## new Endpoint

- cards
  - fetch the list of every cards of the TCG
- cards/{cardId}
  - fetch the informations about a specific card from the TCG
- categories
  - fetch the differents categories of cards
- categories/{category}
  - fetch the cards from a category
- hp
  - Fetch the differents cards HPs
- hp/{hp}
  - Fetch the cards with {hp} HP
- illustrators
  - Fetch all the TCG illustrators
- illustrators/{illustrator}
  - Fetch all the cards made by the illustrator
- rarities
  - Fetch all the rarities
- rarities/{rarity}
  - Fetch the card with the specified rarity
- retreats
  - Fetch the differents rarity count on cards
- retreats/{retreat}
  - Fetch the cards with the defined rarity
- series
  - Fetch the different series released
- series/{serie}
  - Fetch the informations about a specific serie
- sets
  - Fetch the differents sets releases
- sets/{set}
  - Fetch the informations about a specific set
- sets/{set}/{card-localId}
  - FEtch the informations about a card by using its set and localId
- types
  - Fetch the different types
- types/{type}
  - Fetch the cards with the specified type


## V1

_won't backtrack to V1 Changelog sorry_
