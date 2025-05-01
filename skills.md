```mermaid
flowchart TD
   M["Mysticism"] --> SP(["Spell Casting"])
   L["Lore"] --> SC
   SP --> EM(["Elemental Mastery"])
   SP --> DMN(["Demonlogy"])
   SP --> En(["Enchanting"])

   TNK["Tinkering"] --> BL(["Blacksmithing"])
   TNK --> C(["Carpentry"])
   ST(["Stonework"]) --> BL
   BL --> EM
   C --> AC(["Automaton Crafting"])
   BL --> AC
   EN --> AC

   MT["Military Training"] --> SC(["Seigecraft"])
   MT --> SM(["Seamanship"])
   SM --> EM
   MT --> MC(["Melee Combat"])
   SM --> CO(["Command"])
   SC --> CO(["Command"])
   CO --> DMN

   ART["Art"] --> LP(["Lockpicking"])
   SH["Sleight of Hand"] --> LP
   SH --> ES(["Espionage"])
   LP --> ES(["Espionage"])
   ART --> MM(["Marksmanship"])

   AH["Animal Handling"] --> RDG(["Riding"])
   AH --> WS(["Wilderness Survival")]
   WS --> DV(["Divination"])
   RDG --> DR(["Dragonology"])
   EM --> DR
   DR --> EM

   HB["Herbalism"] --> PSN(["Poisons"])
   HB --> FA(["First Aid"])
   FA --> HR(["Healing Rituals"])
   HR --> NCR(["Necromancy"])
   DMN --> NCR
   NCR --> DMN

   ALC["Alchemy"] --> PHM(["Pharmacology")]
   ALC --> EXP(["Explosives"])
   BL --> EXP

   ATH["Athletics"] --> UC(["Unarmed Combat"])
   ATH --> RDG
   ATH --> ES
   ATH --> MC

   DV --> PW(["Planeswalking"])
   TNG["Tongues"] --> DP(["Diplomacy"])
   RW["Realmwise"] --> DP
   RW --> GG(["Geography"])
   GG --> PW
   SC --> PW
   DP --> ES

   DMN --> PW

```
