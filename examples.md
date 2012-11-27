# Examples of syntax

** This is a work in progress **

The examples below are subject to change but gives you an idea of how we think.

## Basic syntax examples

\#heading , ATX-style headers without whitespace between bracket and header is regarded an entity start, a new data object. Rendered to HTML only text following entity-type; \#entity-type Some name , will be rendered

\*keyname\* will be considered keys for a key-value pair if following a \#entity-start

Lists following a \#entity-start are considered as lists that should render to data entitie

A list with entries starting with \*keyname\* will be regarded as an array of key-value pairs

## NPC Example

This is a short NPC writeup

\#npc Dunker Donovan (Fighter, Lvl 3)

Dunker is an able fighter despite his young age. He grew up in the village of Worton in Hale where his father worked as a blacksmith.

\##stats

*strengt* 16, *dexterity* 14, *constitution* 12, *wisdom* 13, *intelligence* 11, *charisma* 7

\##skills

*brawling* 7, *acrobatics* 6, *climb* 4, *perception* 5, *ride* 4

\##feats

- Improved Unarmed Strike
- Stunning Fist

\##items

- Longsword
- Chainmail

## Adventure template

In this example we're writing an adventure with a few scenes. We've divided it into chapters and we're linking in npcs and locations from our master campaign. We've also defined one adventure specific location.

\#adventure Into the wild

\## Introduction

\## GM notes

\##chapter The great forest

\###scene First encounter

[location][location_id]
[somenpc][npc_id]
[anothernpc][npc_id]

\###scene Second encounter

\####location Under the huge oak tree

"At the next crossroad you see a ....

\##chapter The river

\###scene Crossing

The river is really wide and wild. You estimate it to be at least 70 feet. There are trees on both sides.

- [] Throw rope. A very hard check
- [] Shoot the rope across. Very hard

\###scene The accident

- - -
Renders into
- - -

# Into the wild

## Introduction

## GM notes

## The great forest

### First encounter (scene)

[location](location_id)
[somenpc](npc_id)
[anothernpc](npc_id)

### Second encounter (scene)

#### Under the huge oak tree (location)

"At the next crossroad you see a ....

## The river

### Crossing

### The accident
