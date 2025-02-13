# CIP-119 METADATA AND REQUESTED AMENDMENT
- Just a reference doc

## REFERENCES

- [CIP-119](https://github.com/cardano-foundation/CIPs/tree/master/CIP-0119)
  - Like [CIP-108](https://github.com/cardano-foundation/CIPs/tree/master/CIP-0108), this CIP also extends the potential vocabulary of [CIP-100's](https://github.com/cardano-foundation/CIPs/tree/master/CIP-0100) `body` property.
- [Proposed CIP-119 Amendment (internal name CIP-148)](https://drep-eco.vercel.app/cip148)
- [Schema.org](https://schema.org/)

## TABLE

| CIP Version     | Field Name        | Sub-Properties                          |    Identifiers                                | Max Char       | Description                                                                  |
| :-------------: |  ----------       | ---------------                         | -------------                                 | :-----------:  | ------------                                                                 |
| 119             | `paymentAddress`  |                                         |                                               |                | • Bech32 encoded payment address                                               |
|                 | `givenName`       |                                         |                                               | 80             | • Inherited from [`person`](https://schema.org/Person) <br>  • Compulsory <br> • MUST NOT support markdown text styling         |
|                 | `image`           |                                         |                                               |                | • Inherited from [`person`](https://schema.org/Person) <br>  • MUST contain a fully described [`imageObject`](https://schema.org/ImageObject) property                                                                             |
|                 | `imageObject`     |                                         |                                               |                | • Must be (one): <br> - `base64 encoded` image in its [contentUrl](https://github.com/schemaorg/schemaorg/issues/2696) property in a [dataURI](https://en.wikipedia.org/wiki/Data_URI_scheme) <br> - `contentUrl` MUST contain the `URL` where the image can be found and the `sha256` property MUST be populated with the `SHA256 hash of the image file`                                                                             |
|                 | `objectives`      |                                         |                                               | 1000           | • What a person `believes` and wants to `achieve`                                                                             |
|                 | `motivations`     |                                         |                                               | 1000           | • Why want to be a DRep <br> • Personal and professional experiences                                                                             |
|                 | `qualifications`  |                                         |                                               | 1000           | • List the qualifications <br> • Distinct from the properties of a `Person` listed as `knows` and `knowsAbout`                                                                             |
|                 | `references`      | • `@type` <br> • `label` <br> • `URI`   | • @type <br> `"identity"` <br> `"link"`       |                | • Extends the references property from [CIP-100](https://github.com/cardano-foundation/CIPs/tree/master/CIP-0100)                                                                             |
|                 |                   |                                         | `@type: Link`                                 |                | • `Label` SHOULD describe the source of the `url` <br> • Label of each `Link` SHOULD NOT be left blank <br> • `Each Link` MUST have exactly `one uri` (as specified in [CIP-100](https://github.com/cardano-foundation/CIPs/tree/master/CIP-0100))                                                                             |
|                 |                   |                                         | `@type: Identiy`                              |                | • A way for DReps to prove that they are who they say they are <br> • Addresses of most active social media account <br> • Must reference DRep ID in a prominent place at the locations listed                                                                             |
|                 |                   |                                         |                                               |                |                                                                              |
|                 |                   |                                         |                                               |                |                                                                              |
|                 |                   |                                         |                                               |                |                                                                              |
|                 |                   |                                         |                                               |                |                                                                              |
|                 |                   |                                         |                                               |                |                                                                              |
|                 |                   |                                         |                                               |                |                                                                              |
|                 |                   |                                         |                                               |                |                                                                              |
|                 |                   |                                         |                                               |                |                                                                              |
|                 |                   |                                         |                                               |                |                                                                              |
|                 |                   |                                         |                                               |                |                                                                              |
|                 |                   |                                         |                                               |                |                                                                              |
|                 |                   |                                         |                                               |                |                                                                              |
|                 |                   |                                         |                                               |                |                                                                              |
|                 |                   |                                         |                                               |                |                                                                              |
|                 |                   |                                         |                                               |                |                                                                              |
|                 |                   |                                         |                                               |                |                                                                              |
|                 |                   |                                         |                                               |                |                                                                              |
|                 |                   |                                         |                                               |                |                                                                              |
|                 |                   |                                         |                                               |                |                                                                              |
|                 |                   |                                         |                                               |                |                                                                              |
|                 |                   |                                         |                                               |                |                                                                              |
|                 |                   |                                         |                                               |                |                                                                              |
|                 |                   |                                         |                                               |                |                                                                              |
|                 |                   |                                         |                                               |                |                                                                              |
|                 |                   |                                         |                                               |                |                                                                              |
|                 |                   |                                         |                                               |                |                                                                              |
|                 |                   |                                         |                                               |                |                                                                              |
|                 |                   |                                         |                                               |                |                                                                              |
|                 |                   |                                         |                                               |                |                                                                              |
|                 |                   |                                         |                                               |                |                                                                              |

## QUESTIONS


## MEETINGS
