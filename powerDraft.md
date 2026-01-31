# Power Draft

# Abstract

A draft procedure for 4 players using the pool of cards for 8 players draft.
The participants pick their cards but also simulate missing players by removing
cards from the pool. Procedure is designed to be used with cube boosters
or repacks but there is no technical limitation to use it with real products.

# Motivation

When drafting with 4 players using procedure designed for 8 players,
two problems arise.

1. Smaller card pool. This limits the number of possible strategies or even
makes some kind of decks impossible to create due to the halved card
availability.
2. Some card *buckets* are picked by one player only. In most of draftable card
games, cards are divided into specific *buckets*, houses in Game of Thrones
LCG, colors in Magic: The Gathering, etc. With 4 players, there is a high
chance a bucket is uncontested: all cards from the bucket go to one player.
This is not desired.

This procedure uses the same card pool as for 8 players and simulates
the missing players actions during the draft process.

# Draft Round

8 boosters required per round. 

## Draft Step

The draft step replaces two picks made in the standard draft procedure.

Right to left direction of drafting is assumed in this description. Left to
right direction follows the same rules with the left and right words swapped.

Each players is staring the draft step with two incoming booster to their
right.

```
-------------
|           |
|  Removed  |
|  Pile     |
|           |
|           |
|           |
-------------

-------------       -------------   -------------
|           |       |           |   |           |
|  Picked   |       |  First    |   |  Second   |
|  Cards    |       |  Incoming |   |  Incoming |
|           |       |  Booster  |   |  Booster  |
|           |       |           |   |           |
|           |       |           |   |           |
-------------       -------------   -------------
```

Fig. 1. A player's perspective of the table state before a draft step.

Each player performs the following actions simultaneously.

1. Take the first incoming booster.
2. Pick one card.
3. Put one card from the booster to the removed pile.
4. Pass the booster to the left.
5. Take the second incoming booster.
6. Pick a card.
7. Put one card from the booster to the removed pile.
8. Pass the booster to the left.

Incoming boosters MUST be separated at all times, also when moved to the left
for the next player.

After the draft step, the number of cards in each booster is decreased by 2.
Each player picked 2 cards and each player removed 2 cards from the total card
pool.

## Last Draft Step

When a booster consists of odd number of cards, in the last draft step each
incoming booster consists of 1 card only. Each player pics the card from the
first incoming booster and remove the card from the second incoming booster.

# Comparison to Standard Draft Procedure

In first step of Power Draft, the player chooses the best (based on their
judgement) card from first booster. Then from second booster, the same player
also chooses the best card. This is the key difference compared to standard
draft, where in fist two picks the player can choose the best card from first
booster (opened by them) and then the second best card from second booster
(a booster opened by a player to their left or right).

In Power Draft odd picks end up picked by the players and even picks end up in
the removed pile. This allows the decks to have higher power level than in
standard draft, hence the name, Power Draft.

```
+-------------------+----------+----------------------+
| Power Draft       |          | Standard Draft       |
+-------------------+----------+----------------------+
| Draft | Card from | Booster  | Card from | Player's |
| Step  | Booster   |          | Booster   | Pick     |
+-------+-----------+----------+-----------+----------+
| 1     | 1         | A        | 1         | 1        |
|       | 1         |  B       | 2         | 2        |
| 2     | 3         |   C      | 3         | 3        |
|       | 3         |    D     | 4         | 4        |
| 3     | 5         |     E    | 5         | 5        |
|       | 5         |      F   | 6         | 6        |
| 4     | 7         |       G  | 7         | 7        |
|       | 7         |        H | 8         | 8        |
| 5     | 9         | A        | 9         | 9        |
|       | 9         |  B       | 10        | 10       |
| 6     | 11        |   C      | 11        | 11       |
|       | 11        |    D     | 12        | 12       |
| 7     | 13        |     E    | 13        | 13       |
|       | 13        |      F   | 14        | 14       |
+-------+-----------+----------+-----------+----------+
```

Table 1. Pics from one player's perspective.

# Variant: 20 Card Boosters

When drafting from bigger boosters, for example 20 card booster, to save the
time, players pick two cards from each booster during Draft Step. 

Each player performs the following actions simultaneously (see Fig. 1 for table
state before the draft step).

1. Take the first incoming booster.
2. Pick two cards.
3. Put two cards from the booster to the removed pile.
4. Pass the booster to the left.
5. Take the second incoming booster.
6. Pick two cards.
7. Put two cards from the booster to the removed pile.
8. Pass the booster to the left.

# Variant: Bins for Removed Cards

During drafting, each player puts the cards removed by them to a separate bin.
As a result, each player will have a set of cards picked by them and a bin of
cards removed by them.

After playing with the picked cards players can use the bins with removed cards
and build decks from those. Each player can use the bin created by them or the
bins can be assigned randomly to the players.

The usage of a container for each players's bin is recommended to save table
space and limit the possibility of mixing the bins.
