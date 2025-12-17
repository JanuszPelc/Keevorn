# Keevorn

A single-player dungeon crawler card game by Janusz Pelc.

- Fight monsters and manage your inventory
- Master skills and potions to survive
- Read scrolls to face your fortune
- Uncover synergies to defy the odds

---

## The adventurer's essentials

You need a standard deck of cards and two Jokers. To track Health, use paper, a life counter, or a d20.

Cards ranked 5–10 are Weapons. Cards ranked 2–4 are Potions. Together, these are the tools of your trade.

### Depth

You start at the ground level (Depth 0). Each time you descend Stairs, a Joker is removed from the game and tension increases. The Depth equals the number of removed Jokers. With two Jokers, the Depth progression is 0, 1, 2.

### Health

Health determines whether you live or die. It starts at its maximum (20). Whenever you gain Health, ignore any excess. If your Health ever drops below 1, you die and the game ends immediately.

### Hands

There are two **Hands** to equip Weapons to:

- Your red Hand holds up to two red Weapons (♥ or ♦)
- Your black Hand holds up to two black Weapons (♠ or ♣)

Equipped Weapons can only fight Monsters that match the color of the Hand. If a Hand is full, first discard any Weapon from it to make room before equipping.

<div style="page-break-before: always;"></div>

### Backpack

At any time, if the Room is not empty, you can:

- Pick any Weapon or Potion from the Room and store it in your Backpack. Your Backpack holds up to three cards. If your Backpack is full, you cannot store a card in it.
- Place any card from your Backpack into the Room. The Room holds a maximum of four cards. If the Room is full, you cannot place a card into it.

### Piles

| Name     | Purpose                               |
|----------|---------------------------------------|
| Floor    | Face-down pile from unvisited rooms   |
| Room     | Cards you must clear to proceed       |
| Hands    | Equipped Weapons you fight with       |
| Backpack | Your Weapon and Potion reserve        |
| Discard  | Face-down pile of discarded cards     |

### Example layout

![Example layout of the game area](example_layout.jpg)

<div style="page-break-before: always;"></div>

## Setup and exploration

1. Set your Health to its maximum (20).
2. Shuffle all cards face-down. This is your first Floor.
3. Prepare empty spaces for the Room, Hands, Backpack, and Discard piles.
4. Draw four cards from the Floor and place them face-up in front of you to form the Room.

### The Peddler's trade

You step into a bone-dry antechamber. It smells of dust, ancient paper, and ground stone. Something crunches beneath your boot. A hooded peddler appears, willing to trade Weapons for anything else you don't need.

For each non-Weapon card you may wish to trade, place it on the bottom of the Floor, then reveal cards from the top until you find a Weapon. Add it to the Room and put all revealed non-Weapon cards on the bottom of the Floor.

The peddler vanishes. You are on your own now.

### Exploring a Room

While there are cards in the Room, select and **Play** one card. Cards can only be Played from the Room.

When the Room is cleared:

- If the Floor is empty, **you escape.**
- Otherwise, **Enter** the next Room.

### Entering a Room

To **Enter** a new Room, draw up to four cards from the Floor (or fewer, if the Floor runs out). Place them face-up in front of you to form the Room.

<div style="page-break-before: always;"></div>

## Playing rank 2–4 cards (Potions)

Potions are mysterious brews that affect your Health the moment you drink them.

To play a Potion, discard it and apply the effect based on its color:

- Red (♥ or ♦) - **Elixir:** Gain Health equal to the card's rank
- Black (♠ or ♣) - **Bane:** Lose Health equal to the card's rank

## Playing rank 5–10 cards (Weapons)

You may equip a Weapon only by playing it from the Room. You cannot equip from the Backpack.

### Spades ♠ (Attack skill)

An ebon shovel that can be equipped to your black Hand.

Its Attack skill only applies during combat, where Spade Weapons in the Room may join the fight regardless of the Monster's color. If there are no Monsters in the Room, the skill cannot be used.

### Clubs ♣ (Probe skill)

A knotted staff of dark wood that can be equipped to your black Hand.

To use its Probe skill, discard the Club Weapon from the Room and peek at the top card of the Floor. You may place the probed card into the Room or return it to the top of the Floor. If the Floor is empty, the skill cannot be used.

### Hearts ♥ (Heal skill)

A sanguine scepter that can be equipped to your red Hand.

To use its Heal skill, discard the Heart Weapon from the Room and gain Health equal to the card's rank.

### Diamonds ♦ (Bury skill)

A faceted crystalline dagger that can be equipped to your red Hand.

To use its Bury skill, discard the Diamond Weapon from the Room and move another card from the Room to the bottom of the Floor. If there are no other cards in the Room, the skill cannot be used.

<div style="page-break-before: always;"></div>

## Playing Face cards (Monsters)

Jack, Queen, and King are Monsters with strength 11, 12, and 13 respectively. When you play a Monster from the Room, you must fight it.

### Combat

1. Select any Weapons from the Hand that matches the Monster's color. You may also select any Spade Weapons from the Room regardless of the Monster's color. Selected cards occupy their slots until combat ends.
2. Sum the ranks of the selected cards to get your attack power.
3. Compare your attack power to the Monster's strength:
   - If your attack power is lower, you lose Health equal to the difference.
   - If your attack power is higher, you win. If selected cards contain any Spade, also gain Health equal to the difference.
   - If they are equal, this is a clean kill.
4. Discard the selected cards and the Monster.

You may choose to fight barehanded, in which case your attack power is 0 and you lose Health equal to the Monster's full strength.

## Playing Aces (Scrolls)

Aces are arcane Scrolls that reveal your Fortune. To read a Scroll, discard an Ace, then draw a card from the Floor and place it face-up in the Room. If the Floor is empty, just discard the Ace and skip the Fortune step.

### Your Fortune

The drawn card remains in the Room, and determines which Fortune you must face, resolving it immediately. Fortunes are:

- ♠ Spades - **Pain:** Lose Health equal to three times the Depth
- ♣ Clubs - **Loss:** Discard any card from your Backpack
- ♥ Hearts - **Vigor:** Gain Health equal to three times the Depth
- ♦ Diamonds - **Relief:** Discard any Monster or Potion in the Room
- Joker - **Surprise:** Discard any number of cards from the Room

At the ground level (Depth 0), Pain and Vigor do not affect your Health.

<div style="page-break-before: always;"></div>

## Playing Jokers (Stairs)

Jokers cannot be played. They stay in the Room until all other cards are cleared, unless an effect moves or discards them. When only Jokers remain in the Room, you have found the Stairs and the current Floor ends. Possible cases are:

- **One Joker:** Remove it from the game. Shuffle the Floor and Discard piles together to form a new Floor pile, then **Enter** the first Room.
- **More than one Joker:** Immediately proceed to the Secret Floor section below.

### Secret Floor

Multiple stairways converge into a gloomy passage. You've found a Secret Floor, a rare detour from the main dungeon.

Take all Jokers from the Room. Choose whichever pile (Floor or Discard) looks larger to you and insert the Jokers into that pile at random places, so they aren't all together.

Shuffle the Floor and Discard piles together to form a new Floor pile, then **Enter** the first Room. A Wishing Well awaits here.

Upon entering the first Room, your number of wishes equals 1 plus the Depth. For each wish, name any Fortune and resolve it.

## The end of the journey

The game ends when:

- You clear all Rooms and survive Keevorn.
- You die. The journey is the reward.

And here's the secret of Keevorn: luck deals, skill wins.

## House rules

- On a coffee-break? Pick a Depth and play without Jokers.
- Up for relaxed play? Treat Potions as Weapons.
- Feeling brave or fragile? Lower or raise the maximum Health.
- Craving a longer and grimmer journey? Use more Jokers.
- Chasing bragging rights? Brag about your clean kills.

These are just starting points. Make the game your own!

<div style="page-break-before: always;"></div>

## Quick reference

| Concept  | Rule                                                          |
|----------|---------------------------------------------------------------|
| Depth    | Number of Jokers removed from the game (0, 1, 2)              |
| Health   | Starts at 20, cannot exceed 20, you die below 1               |
| Hands    | Each one holds up to two Weapons, red and black separately    |
| Backpack | Holds up to three Weapons or Potions                          |

| Rank       | Type     | Mechanics                                            |
|------------|----------|------------------------------------------------------|
| 2–4        | Potions  | Red heals, black hurts (by card's rank)              |
| 5–10       | Weapons  | Equip to color-matching Hand, or use unique Skills   |
| Face cards | Monsters | Strength: Jack 11, Queen 12, King 13                 |
| Ace        | Scrolls  | Draw a card and face your Fortune                    |
| Joker      | Stairs   | Single leads to next Floor, multiple to Secret Floor |

| Suit       | Skill  | Fortune  | Resolution                                  | Color |
|------------|--------|----------|---------------------------------------------|-------|
| Spades ♠   | Attack | Pain     | Lose Health equal to three times the Depth  | Black |
| Clubs ♣    | Probe  | Loss     | Discard any card from your Backpack         | Black |
| Hearts ♥   | Heal   | Vigor    | Gain Health equal to three times the Depth  | Red   |
| Diamonds ♦ | Bury   | Relief   | Discard any Monster or Potion in the Room   | Red   |
| Joker      | —      | Surprise | Discard any number of cards from the Room   | —     |

| Fighting   | Room   | Hand     | Selected       | Case    | Health                      |
|------------|--------|----------|----------------|---------|-----------------------------|
| Q♠ (12)    | 7♠     | 5♣       | 5♣ + 7♠        | 12 = 12 | No change (clean kill)      |
| J♠ (11)    | —      | 9♠, 10♣  | 10♣            | 10 < 11 | Lose 1 (9♠ saved for later) |
| K♣ (13)    | 7♣     | 5♣, 6♠   | 5♣ + 6♠        | 11 < 13 | Lose 2 (7♣ can't join)      |
| J♣ (11)    | —      | —        | —              | 0 < 11  | Lose 11 (barehanded)        |
| K♠ (13)    | —      | 7♠, 8♣   | 7♠ + 8♣        | 15 > 13 | Gain 2 (♠ bonus)            |
| Q♥ (12)    | 9♠     | 6♥, 8♦   | 6♥ + 8♦ + 9♠   | 23 > 12 | Gain 11 (♠ bonus)           |
| Q♥ (12)    | 9♠     | 6♥, 8♦   | 6♥ + 8♦        | 14 > 12 | No change (no ♠ selected)   |

Keevorn · Released December 2025 · MIT License · [github.com/JanuszPelc/Keevorn](https://github.com/JanuszPelc/Keevorn)