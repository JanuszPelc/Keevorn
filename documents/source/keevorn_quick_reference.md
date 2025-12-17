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