# Unsanctioned Diagram Note & Collection Of Thoughts
##### BACKGROUND:
- It's been over 10 years since I have used any UML diagram so this is a collection of:
  - references and
  - newly created referecne materials
  - ideations
 
##### REFERENCE LINKS:
- [Learn UML-2](https://github.com/imalitavakoli/learn-uml2)

## Thoughts
- Servers/Website/Code
  - `FUTURE` - can this be distributed by design? or migrated into that direction
  - 
- Delegates/Users -> create a profile (on-chain?) -> add to indexer?
  - would/could end up being a very large project but perfect for connecting community members if users are allowed to create profiles
  - account recovery
  - unique individual nft with open policy where only wallet holder can modify data therein
  - what is the cleanest, most minimal, interface for selecting search filters?
  - 
- GDPR, other laws; what determines laws, server location or user location?
  - where to host out of?
- Smart Contract pays for Tx <-- put info somewhere else


## Needed
### For Broad Use:
- translation tool

### Classes:
#### `Delegates`

- Attributes:
  - static -> `language` : `Lang`
  - dynamic -> `ecosystemRoles` (optional) : `ecosystemRole` `String`
  - dynamic -> `geoLocale` (optional) : `Locale` `String`
  - dynamic -> `areaOfInterests` (optional) : `AreasOfInterest` `String`
  - dynamic -> `intitiatives` (optional) : `String` 
  - dynamic -> `organization` (optional) : `String`
- Actions:
  - `createProfile`
  - `registerAsDrep`
  - `search`
    - Filter by:
      - `Lang`
      - `Locale`
      - `Endorsement`
      - `Qualification`
      - `Role`
      - `AreaOfInterest`
      - Other possibilities
        - any sub-field (i.e. Organization, Y/N Vote-Percentage)
        - combination with priority set
    - `print to file` search results -> text tree
    - `min/max results` for search return
#### `DReps`
- Attributes:
  - static -> `drepID` :  `DrepID`
  - static -> `name` : `GivenName`
  - static -> `language` : `Lang`
  - dynamic -> `geoLocale` : `Locale`
  - dynamic -> `areasOfInterest` : `AreaOfInterest`
  - dynamic -> `qualifications` : `Qualification` -> `Reference`
  - dynamic -> `endorsments` : `Endorsement` -> `Reference`
  - dynamic -> `ecosystemRoles` : `Role`
  - dynamic -> `activityMap` : `Activity`
- Actions:
  - `createDrepProfile`
  - `modifyDrepProfile`
  - `deregister`
  - 
#### Generic User
- Attributes


















-
