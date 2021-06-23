# TCGdex/distribution

The raw TCGdex API files.

More informations at https://github.com/tcgdex/cards-database#pokemon-tcgdex

## Versioning

Each changes made to the API is a new "version" depicted as such:

- MAJOR => Breaking change to the database, a new folder name `v{MAJOR}` is created
- MINOR => non-breaking change is made
  - new field/subfield is added
  - optional field is now always present
- PATCH
  - data added/patched/removed

_see the [CHANGELOGS](./CHANGELOGS.md) file to get the full list of changes_

## Support

the older API is supported 6 months after a new MAJOR release has been out to allow developpers to update to the new API.

_note: the 6 month support start after the [officials SDK](https://github.com/tcgdex/cards-database/blob/master/README.md#sdks-api-wrapper-but-sdk-is-way-cooler-) have their version up too._

## Issues reporting

Please report any issues here https://github.com/tcgdex/cards-database/issues
