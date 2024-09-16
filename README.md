# dungeon mastr rules

## types of player

- dungeon mastr
- player
- NPC
- AI hybrids

## characters

- each player can have one character alive at any one time
- when a character is dead a new one can be rerolled
- each player is generated deterministically from a nostr ID
- the genesis of each player is a marked transaction

## determinism

- the state of the game can be deterministically determined from the testnet4 blockchain
- all major events generate a block tx

## money

- 1 copper coin = 100 testnet satoshis
- 1 silver = 100 copper
- 1 gold = 100 silver
- platinum is reserved

## rules

- rules begin to match as far as possible ADND rules
- rules can be adjusted every 2016 blocks

## combat

- combat and xp will match ADND
- if combat is agreed, the tx that forms the contract is the source of entropy for the outcome
- each nostr user's whole history is recorded in the testnet block chain
