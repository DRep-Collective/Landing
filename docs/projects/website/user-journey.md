# Website/App User Journey, etc.
#### This document uses the following items as reference:
```
To view any of the links below please right-click, or long-press if on mobile, and open in new tab
```
- [Current demo/WIP website](https://preview-drep.vercel.app/)
- [CIP-???](https://github.com/Alpine-Oracle/CIPs/tree/CIP-0152/CIP-DRep-Credential)
- [Cardano Ecosystem Map - Roles & Sectors Definitions - Defintions v1.1 - `PDF`](https://github.com/DRep-Collective/Landing/blob/main/docs/projects/website/supporting-files/Cardano%20Ecosystem%20Map%20-%20Roles%20%26%20Sectors%20Definitions%20-%20Defintions%20v1.1.pdf)
- [Ecosystem Mapping Metadata Standard - `PDF`](https://github.com/DRep-Collective/Landing/blob/main/docs/projects/website/supporting-files/Ecosystem%20Mapping%20Metadata%20Standard.pdf)
- [Initial Wireframes using Pencil - `png`](https://github.com/DRep-Collective/Landing/blob/main/docs/projects/website/supporting-files/initial-wireframe-pencil.png)
- [ROLE `defined` via `essif-lab`](https://essif-lab.github.io/framework/docs/terms/role-name)
---

## USER JOURNEY (as discussed)
```
All pages should have a Wallet Connect feature in the upper-right hand corner
```
### USERS
```
The users and items listed below will be the basis for the user selection (i.e. pages available) upon
launching the app or visiting the website
```
- [DReps](https://github.com/DRep-Collective/Landing/blob/main/docs/projects/website/user-journey.md#dreps)
- [Endorsers](https://github.com/DRep-Collective/Landing/blob/main/docs/projects/website/user-journey.md#endorsers)
- [Delegates](https://github.com/DRep-Collective/Landing/blob/main/docs/projects/website/user-journey.md#delegates)
- [Cardano Community Members](https://github.com/DRep-Collective/Landing/blob/main/docs/projects/website/user-journey.md#community-members)
- [General](https://github.com/DRep-Collective/Landing/blob/main/docs/projects/website/user-journey.md#general)

---

#### DREPS:
```
"Locked" means the field is not available without a minted credential.

"Semi-locked" means the item may pull information from data associated with the onchain DRep ID
but will present empty fields associated with credential minting anf profile expansion
```
##### ACTIONS/OPTIONS AVAILABLE
- Create Credential
	- see [here](https://preview-drep.vercel.app/drep/create-credential) for req’d fields.
- Profile Page
  ```
  Should be able to see without Credential, though data may be missing, locked or unavailable
  ```
	- endorsements (locked)
	- vote history
	- rewards to date (locked)
	- personal profile (semi-locked)
- Post A Ballot Note (locked)
	- see [here](https://preview-drep.vercel.app/drep/create-ballot-note) for fields
- Ecosystem Map
  ```
  Searchability of metadata and data fieldss is still being discussed, as bloat, misspellings and
  lanugauge can impact self-reported data entries
  ```
  - search -> see self-reported roles and sectors from [here](https://preview-drep.vercel.app/drep/create-credential)
  
- Collective Specific (locked):
	- Benefits
	- Support - Legal, Social, etc.
- Internal Collective Voting (locked)

---

#### ENDORSERS:

##### ACTIONS/OPTIONS AVAILABLE
- Registration/Verification
- Ecosystem Map
- Create Endorsement Credential (for DRep(s))
- Profile (listing Endorsements)

---

#### DELEGATES:
```
Items with a "?" indicates these are posssibilities but need to be discussed with the dev team and others
```
##### ACTIONS/OPTIONS AVAILABLE
- Ecosystem Map
	- view/search DReps
- Delegate Function
- Create Profile? 
	- (User Regulated) Would allow connection to other registered delegates
- Direct Message DRep (?)

---

#### COMMUNITY MEMBERS:
```
A view only role
```
##### ACTIONS/OPTIONS AVAILABLE
- Ecosystem Map

---

#### GENERAL:
```
May be considered an ABOUT page/option
```
##### ACTIONS/OPTIONS AVAILABLE
- Resources - maybe add **`ROLES & definitions`** HERE
- Links
- About
- ToS
- PrivPol
- Disclaimer
- Bug Report

---
